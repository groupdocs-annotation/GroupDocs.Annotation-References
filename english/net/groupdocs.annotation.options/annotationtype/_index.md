---
title: Enum AnnotationType
second_title: GroupDocs.Annotation for .NET API Reference
description: GroupDocs.Annotation.Options.AnnotationType enum. Enumeration that decribes annotation types supported by GroupDocs.Annotation for .NET
type: docs
weight: 320
url: /net/groupdocs.annotation.options/annotationtype/
---
## AnnotationType enumeration

Enumeration that decribes annotation types supported by GroupDocs.Annotation for .NET

```csharp
[Flags]
public enum AnnotationType
```

### Values

| Name | Value | Description |
| --- | --- | --- |
| None | `0` | Default value |
| Area | `2` | The area annotation type that highlights rectangular area within the document page |
| Arrow | `4` | The annotation type that draws an arrow on the document page |
| Distance | `8` | The annotation type that measures distance between elements of a document page |
| Ellipse | `10` | The annotation of elliptic form that marks parts of document content |
| Link | `20` | The annotation type that represents a hyperlink to a remote resource |
| Point | `40` | The point annotation type that sticks a comment to an any place within document page |
| Polyline | `80` | The polyline annotation type that allows add drawing shapes and freehand lines to a document page |
| ResourcesRedaction | `100` | The annotation type that hides textual content behind black rectangle |
| TextField | `200` | The text field annotation type represents textual comment inside colored frame |
| TextHighlight | `400` | The annotation type that highlights and comments selected text |
| TextRedaction | `800` | The annotation type that fills part of selected text with black rectangle. |
| TextReplacement | `1000` | The annotation type that replaces original text with other provided text fragment |
| TextStrikeout | `2000` | The annotation type that marks text fragment with a strikethrough styling |
| TextUnderline | `4000` | The annotation type that marks text with a underline styling |
| Watermark | `8000` | The annotation type that adds textual watermark over document page |
| Image | `10000` | The annotation type that adds image overlay over document page content |
| Dropdown | `20000` | The component type that adds dropdown component for pdf document **only** |
| Checkbox | `21000` | The annotation type that adds checkbox for pdf document |
| Button | `22000` | The annotation type that adds button for pdf document |
| TextSquiggly | `2500` | The annotation type that squiggly and comments selected text |
| SearchText | `2700` | The annotation type that search fragment text in document |
| All | `7FFFFFFF` | All |

## Remarks

**Learn more**

* [How to annotate documents in C#](https://docs.groupdocs.com/display/annotationnet/Add+annotation+to+the+document)
* [How to add area annotations in C#](https://docs.groupdocs.com/display/annotationnet/Add+area+annotation)
* [How to add arrow annotations in C#](https://docs.groupdocs.com/display/annotationnet/Add+arrow+annotation)
* [How to add distance annotations in C#](https://docs.groupdocs.com/display/annotationnet/Add+distance+annotation)
* [How to add ellipse annotations in C#](https://docs.groupdocs.com/display/annotationnet/Add+ellipse+annotation)
* [How to add link annotations in C#](https://docs.groupdocs.com/display/annotationnet/Add+link+annotation)
* [How to add point annotations in C#](https://docs.groupdocs.com/display/annotationnet/Add+point+annotation)
* [How to add polyline annotations in C#](https://docs.groupdocs.com/display/annotationnet/Add+polyline+annotation)
* [How to add resource redaction annotations in C#](https://docs.groupdocs.com/display/annotationnet/Add+resource+redaction+annotation)
* [How to add text field annotations in C#](https://docs.groupdocs.com/display/annotationnet/Add+text+field+annotation)
* [How to add highlight annotations in C#](https://docs.groupdocs.com/display/annotationnet/Add+highlight+annotation)
* [How to add text redaction annotations in C#](https://docs.groupdocs.com/display/annotationnet/Add+text+redaction+annotation)
* [How to add replacement annotations in C#](https://docs.groupdocs.com/display/annotationnet/Add+replacement+annotation)
* [How to add strikeout annotations in C#](https://docs.groupdocs.com/display/annotationnet/Add+strikeout+annotation)
* [How to add underline annotations in C#](https://docs.groupdocs.com/display/annotationnet/Add+underline+annotation)
* [How to add watermark annotations in C#](https://docs.groupdocs.com/display/annotationnet/Add+watermark+annotation)
* [How to add image annotations in C#](https://docs.groupdocs.com/display/annotationnet/Add+image+annotation)

### See Also

* namespace [GroupDocs.Annotation.Options](../../groupdocs.annotation.options/)
* assembly [GroupDocs.Annotation](../../)


