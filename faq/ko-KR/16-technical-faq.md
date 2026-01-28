---
title: "{{< fa brands github size=2x >}} 기술 FAQ"
description: "질문 1개"
lang: 영어-영국
order: 16
category-level: 0
icon: 브랜드 깃허브
---

{{< fa "브랜드" "깃허브" size=3배 >}}

## 소스 문자열을 변경할 때 모든 언어 파일을 업데이트해야 할까요?

아니요, 그렇지 않습니다. 영어 버전만 업데이트하면 됩니다.

- PR을 작성하세요

병합이 완료되면 crowdin-trigger를 수동으로 리베이스하고, GitHub Actions에 의해 실행되는 Crowdin 번역 시스템이 다른 언어에 대한 번역을 자동으로 처리할 것입니다.

그러면 GitHub 봇이 자동으로 새로운 PR을 생성하고, 저희는 그 PR을 검토합니다.

---

