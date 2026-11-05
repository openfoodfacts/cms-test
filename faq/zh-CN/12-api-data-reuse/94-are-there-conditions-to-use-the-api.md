---
title: "使用 API 有什么条件吗？"
order: 94
lang: 英语-英国
category: 12-api-数据重用
breadcrumbs: [ '/en-gb/', '/en-gb/12-api-data-reuse/' ]
---

所有关于 API 使用方法的文档都可以在 API 文档页面找到，但这里做一个简要概述：

- Open Food Facts 数据库根据开放数据库许可证 (ODbL) 作为开放数据提供，有关法律详情，请参阅 https://world.openfoodfacts.org/terms-of-use。 这两个条件是归属和相同方式共享。 如果将 Open Food Facts 的数据与其他数据库的数据结合起来，那么 ODbL 要求生成的数据库也必须作为开放数据发布。 这也意味着，你只能将数据与允许此类重新分发的来源结合起来。

- 在执行 API 调用时，必须始终使用自定义 User-Agent 来识别您的应用程序。

- 每个 API 端点都强制执行速率限制。
