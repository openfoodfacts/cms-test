# Crowdin Integration Guide

This repository uses [Crowdin](https://crowdin.com/) for managing translations of the CMS content.

## Setup

### 1. Create a Crowdin Project

1. Go to [Crowdin](https://crowdin.com/) and create an account if you don't have one
2. Create a new project for this repository
3. Note down your project ID

### 2. Configure the Project

1. Open the `crowdin.yml` file in the repository root
2. Replace `"YOUR_CROWDIN_PROJECT_ID_HERE"` with your actual Crowdin project ID (found in your Crowdin project settings URL)
3. In your Crowdin project settings, add the target languages:
   - German (de)
   - Spanish (es)
   - French (fr)
   - Italian (it)

### 3. Install Crowdin CLI

```bash
npm install -g @crowdin/cli
```

Or use other installation methods from the [official documentation](https://crowdin.github.io/crowdin-cli/).

### 4. Set Up Authentication

You need to authenticate with Crowdin to use the CLI. You can do this by setting the API token as an environment variable:

```bash
export CROWDIN_PERSONAL_TOKEN=your-api-token
```

Alternatively, you can add the token directly to the `crowdin.yml` file (not recommended for public repositories):

```yaml
api_token: "your-api-token"
```

You can generate a Personal Access Token in your Crowdin account settings under **Settings** → **API** → **Personal Access Tokens**.

## Usage

### Upload Source Files to Crowdin

Upload English source files to Crowdin for translation:

```bash
crowdin upload sources
```

### Download Translations

Download completed translations from Crowdin:

```bash
crowdin download
```

### Upload Translations (if needed)

If you already have translations in the repository that you want to upload to Crowdin:

```bash
crowdin upload translations
```

## Repository Structure

This repository follows a specific structure for multilingual content:

### FAQ Structure

```
faq/
├── en-gb/              # English source files
│   ├── 1-my-open-food-facts-account/
│   │   ├── 33-i-want-to-delete-my-account.md
│   │   └── index.qmd
│   └── ...
├── fr-fr/              # French translations
│   ├── 1-mon-compte/
│   │   ├── 33-je-souhaite-supprimer-mon-compte.md
│   │   └── index.qmd
│   └── ...
├── de-de/              # German translations
├── es-es/              # Spanish translations
└── it-it/              # Italian translations
```

**Note:** Files are matched by their numeric ID (e.g., `33-*.md`). The directory names and file titles may differ between languages, but the numeric IDs remain consistent.

### Main Content Files

- `index.qmd` - Main homepage content
- `notices.qmd` - Catalog/notices page
- `_quarto.yml` - Quarto site configuration

These files can be translated with language suffixes (e.g., `index.fr-fr.qmd`).

## Continuous Integration

To automate the translation workflow, you can:

1. Set up a GitHub Action to automatically upload sources when the English content changes
2. Set up a webhook to automatically create PRs when translations are completed in Crowdin
3. Use Crowdin's GitHub integration for seamless synchronization

Example GitHub Action workflow (`.github/workflows/crowdin.yml`):

```yaml
name: Crowdin Sync

on:
  push:
    branches: [main]
    paths:
      - 'faq/en-gb/**'
      - 'index.qmd'
      - 'notices.qmd'
      - '_quarto.yml'

jobs:
  sync:
    runs-on: ubuntu-latest
    steps:
      - uses: actions/checkout@v3
      - name: Crowdin push
        uses: crowdin/github-action@v1
        with:
          upload_sources: true
          download_translations: false
        env:
          CROWDIN_PROJECT_ID: ${{ secrets.CROWDIN_PROJECT_ID }}
          CROWDIN_PERSONAL_TOKEN: ${{ secrets.CROWDIN_PERSONAL_TOKEN }}
```

## Best Practices

1. **Always edit English (en-gb) source files** - Never edit translated files directly
2. **Use consistent numeric IDs** - Maintain the same numeric prefixes across all languages
3. **Review translations** - Use Crowdin's review features before downloading
4. **Keep context** - Add context and screenshots in Crowdin to help translators
5. **Regular updates** - Upload sources regularly and download translations frequently

## Support

For issues with:
- **Crowdin configuration**: Check the [Crowdin CLI documentation](https://crowdin.github.io/crowdin-cli/)
- **Translation quality**: Use Crowdin's review and discussion features
- **Technical issues**: Open an issue in this repository

## Resources

- [Crowdin Documentation](https://support.crowdin.com/)
- [Crowdin CLI](https://crowdin.github.io/crowdin-cli/)
- [Crowdin GitHub Integration](https://support.crowdin.com/github-integration/)
