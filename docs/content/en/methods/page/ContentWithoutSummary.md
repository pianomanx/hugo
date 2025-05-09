---
title: ContentWithoutSummary
description: Returns the rendered content of the given page, excluding the content summary.
categories: []
keywords: []
params:
  functions_and_methods:
    returnType: template.HTML
    signatures: [PAGE.ContentWithoutSummary]
---

{{< new-in 0.134.0 />}}

Applicable when using manual or automatic [content summaries], the `ContentWithoutSummary` method on a `Page` object renders Markdown and shortcodes to HTML, excluding the content summary from the result.

[content summaries]: /content-management/summaries/#manual-summary

```go-html-template
{{ .ContentWithoutSummary }}
```

The `ContentWithoutSummary` method returns the same as `Content` if you define the content summary in front matter.
