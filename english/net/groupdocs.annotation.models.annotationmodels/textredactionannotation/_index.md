---
title: Class TextRedactionAnnotation
second_title: GroupDocs.Annotation for .NET API Reference
description: GroupDocs.Annotation.Models.AnnotationModels.TextRedactionAnnotation class. Represents text redaction annotation properties
type: docs
weight: 740
url: /net/groupdocs.annotation.models.annotationmodels/textredactionannotation/
---
## TextRedactionAnnotation class

Represents text redaction annotation properties

```csharp
public class TextRedactionAnnotation : AnnotationBase, IEquatable<TextRedactionAnnotation>, 
    ITextRedactionAnnotation
```

## Constructors

| Name | Description |
| --- | --- |
| [TextRedactionAnnotation](textredactionannotation/)() | Initializes new instance of `TextRedactionAnnotation` class. |

## Properties

| Name | Description |
| --- | --- |
| [CreatedOn](../../groupdocs.annotation.models.annotationmodels/annotationbase/createdon/) { get; set; } | Gets or sets annotation creation date |
| [FontColor](../../groupdocs.annotation.models.annotationmodels/textredactionannotation/fontcolor/) { get; set; } | Gets or sets text redaction annotation text font color |
| [Id](../../groupdocs.annotation.models.annotationmodels/annotationbase/id/) { get; set; } | Gets or sets annotation unique identifier. This field is auto-incremented. |
| [Message](../../groupdocs.annotation.models.annotationmodels/annotationbase/message/) { get; set; } | Gets or sets annotation message |
| [PageNumber](../../groupdocs.annotation.models.annotationmodels/annotationbase/pagenumber/) { get; set; } | Page number where the annotation should be located |
| [Points](../../groupdocs.annotation.models.annotationmodels/textredactionannotation/points/) { get; set; } | Gets or sets collection of points that describe rectangles with text |
| [Replies](../../groupdocs.annotation.models.annotationmodels/annotationbase/replies/) { get; set; } | The list of replies (comments) attached to the annotation |
| [StateBeforeAnnotation](../../groupdocs.annotation.models.annotationmodels/annotationbase/statebeforeannotation/) { get; set; } |  |
| [Type](../../groupdocs.annotation.models.annotationmodels/annotationbase/type/) { get; set; } | Gets or sets annotation type |
| [User](../../groupdocs.annotation.models.annotationmodels/annotationbase/user/) { get; set; } | Gets or sets annotation author |

## Methods

| Name | Description |
| --- | --- |
| override [Clone](../../groupdocs.annotation.models.annotationmodels/textredactionannotation/clone/)() | Returns new instance with the same values |
| [Equals](../../groupdocs.annotation.models.annotationmodels/annotationbase/equals/)(AnnotationBase) | Compares Base Annotations using IEquatable Equals method |
| override [Equals](../../groupdocs.annotation.models.annotationmodels/textredactionannotation/equals/#equals_2)(object) | Compares text redaction annotation using standard object Equals method |
| [Equals](../../groupdocs.annotation.models.annotationmodels/textredactionannotation/equals/#equals_1)(TextRedactionAnnotation) | Compares text redaction annotation using IEquatable Equals method |
| override [GetHashCode](../../groupdocs.annotation.models.annotationmodels/textredactionannotation/gethashcode/)() | Returns HashCode of the text redaction annotation |

## Remarks

**Learn more**

* More about annotation types and annotating PDF and Microsoft Word documents, Excel spreadsheets and PowerPoint Presentations: [How to annotate documents using GroupDocs.Annotation for .NET](https://docs.groupdocs.com/display/annotationnet/Add+annotation+to+the+document)
* More about adding text redaction annotations to documents of various types: [How to add text redaction annotations in C#](https://docs.groupdocs.com/display/annotationnet/Add+text+redaction+annotation)

### See Also

* class [AnnotationBase](../annotationbase/)
* interface [ITextRedactionAnnotation](../../groupdocs.annotation.models.annotationmodels.interfaces.annotations/itextredactionannotation/)
* namespace [GroupDocs.Annotation.Models.AnnotationModels](../../groupdocs.annotation.models.annotationmodels/)
* assembly [GroupDocs.Annotation](../../)


