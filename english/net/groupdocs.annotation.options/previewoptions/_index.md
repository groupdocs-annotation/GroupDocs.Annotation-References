---
title: Class PreviewOptions
second_title: GroupDocs.Annotation for .NET API Reference
description: GroupDocs.Annotation.Options.PreviewOptions class. Represents document preview options
type: docs
weight: 1030
url: /net/groupdocs.annotation.options/previewoptions/
---
## PreviewOptions class

Represents document preview options.

```csharp
public class PreviewOptions
```

## Constructors

| Name | Description |
| --- | --- |
| [PreviewOptions](previewoptions/#constructor)(CreatePageStream) | Initializes a new instance of `PreviewOptions` class. |
| [PreviewOptions](previewoptions/#constructor_1)(CreatePageStream, ReleasePageStream) | Initializes a new instance of `PreviewOptions` class. |

## Properties

| Name | Description |
| --- | --- |
| [CreatePageStream](../../groupdocs.annotation.options/previewoptions/createpagestream/) { get; set; } | Delegate which defines method to create output page preview stream. |
| [Height](../../groupdocs.annotation.options/previewoptions/height/) { get; set; } | Page preview height. |
| [PageNumbers](../../groupdocs.annotation.options/previewoptions/pagenumbers/) { get; set; } | Page numbers that will be previewed. |
| [PreviewFormat](../../groupdocs.annotation.options/previewoptions/previewformat/) { get; set; } | Preview image format. |
| [ReleasePageStream](../../groupdocs.annotation.options/previewoptions/releasepagestream/) { get; set; } | Delegate which defines method to remove output page preview stream |
| [RenderAnnotations](../../groupdocs.annotation.options/previewoptions/renderannotations/) { get; set; } | The property that controls whether annotations will be generated on the preview. Default State - true. |
| [RenderComments](../../groupdocs.annotation.options/previewoptions/rendercomments/) { get; set; } | The property that controls whether comments will be generated on the preview. Default State - true. Now Supported only in MS Word document |
| [Resolution](../../groupdocs.annotation.options/previewoptions/resolution/) { get; set; } | Gets or sets the resolution for generated images, in dots per inch. |
| [Width](../../groupdocs.annotation.options/previewoptions/width/) { get; set; } | Page preview width. |
| [WorksheetColumns](../../groupdocs.annotation.options/previewoptions/worksheetcolumns/) { get; set; } | Worksheet columns to generate. Generation proceeds in the specified order. |

### See Also

* namespace [GroupDocs.Annotation.Options](../../groupdocs.annotation.options/)
* assembly [GroupDocs.Annotation](../../)


