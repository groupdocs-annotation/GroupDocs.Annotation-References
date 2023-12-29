---
title: Class StrikeoutAnnotation
second_title: GroupDocs.Annotation for .NET API Reference
description: GroupDocs.Annotation.Models.AnnotationModels.StrikeoutAnnotation class. Represents strikeout annotation properties
type: docs
weight: 720
url: /net/groupdocs.annotation.models.annotationmodels/strikeoutannotation/
---
## StrikeoutAnnotation class

Represents strikeout annotation properties

```csharp
public class StrikeoutAnnotation : AnnotationBase, IEquatable<StrikeoutAnnotation>, 
    IStrikeoutAnnotation
```

## Constructors

| Name | Description |
| --- | --- |
| [StrikeoutAnnotation](strikeoutannotation/)() | Initializes new instance of `StrikeoutAnnotation` class. |

## Properties

| Name | Description |
| --- | --- |
| [BackgroundColor](../../groupdocs.annotation.models.annotationmodels/strikeoutannotation/backgroundcolor/) { get; set; } | Gets or sets strikeout annotation text background color |
| [CreatedOn](../../groupdocs.annotation.models.annotationmodels/annotationbase/createdon/) { get; set; } | Gets or sets annotation creation date |
| [FontColor](../../groupdocs.annotation.models.annotationmodels/strikeoutannotation/fontcolor/) { get; set; } | Gets or sets strikeout annotation text font color |
| [Id](../../groupdocs.annotation.models.annotationmodels/annotationbase/id/) { get; set; } | Gets or sets annotation unique identifier. This field is auto-incremented. |
| [Message](../../groupdocs.annotation.models.annotationmodels/annotationbase/message/) { get; set; } | Gets or sets annotation message |
| [Opacity](../../groupdocs.annotation.models.annotationmodels/strikeoutannotation/opacity/) { get; set; } | Gets or sets strikeout annotation opacity |
| [PageNumber](../../groupdocs.annotation.models.annotationmodels/annotationbase/pagenumber/) { get; set; } | Page number where the annotation should be located |
| [Points](../../groupdocs.annotation.models.annotationmodels/strikeoutannotation/points/) { get; set; } | Gets or sets collection of points that describe rectangles with text |
| [Replies](../../groupdocs.annotation.models.annotationmodels/annotationbase/replies/) { get; set; } | The list of replies (comments) attached to the annotation |
| [StateBeforeAnnotation](../../groupdocs.annotation.models.annotationmodels/annotationbase/statebeforeannotation/) { get; set; } |  |
| [Type](../../groupdocs.annotation.models.annotationmodels/annotationbase/type/) { get; set; } | Gets or sets annotation type |
| [User](../../groupdocs.annotation.models.annotationmodels/annotationbase/user/) { get; set; } | Gets or sets annotation author |

## Methods

| Name | Description |
| --- | --- |
| override [Clone](../../groupdocs.annotation.models.annotationmodels/strikeoutannotation/clone/)() | Returns new instance with the same values |
| [Equals](../../groupdocs.annotation.models.annotationmodels/annotationbase/equals/)(AnnotationBase) | Compares Base Annotations using IEquatable Equals method |
| override [Equals](../../groupdocs.annotation.models.annotationmodels/strikeoutannotation/equals/#equals_2)(object) | Compares strikeout annotation using standard object Equals method |
| [Equals](../../groupdocs.annotation.models.annotationmodels/strikeoutannotation/equals/#equals_1)(StrikeoutAnnotation) | Compares strikeout annotation using IEquatable Equals method |
| override [GetHashCode](../../groupdocs.annotation.models.annotationmodels/strikeoutannotation/gethashcode/)() | Returns HashCode of the strikeout annotation |

## Remarks

**Learn more**

* More about annotation types and annotating PDF and Microsoft Word documents, Excel spreadsheets and PowerPoint Presentations: [How to annotate documents using GroupDocs.Annotation for .NET](https://docs.groupdocs.com/display/annotationnet/Add+annotation+to+the+document)
* More about adding strikeout annotations to documents of various types: [How to add strikeout annotations in C#](https://docs.groupdocs.com/display/annotationnet/Add+strikeout+annotation)

### See Also

* class [AnnotationBase](../annotationbase/)
* interface [IStrikeoutAnnotation](../../groupdocs.annotation.models.annotationmodels.interfaces.annotations/istrikeoutannotation/)
* namespace [GroupDocs.Annotation.Models.AnnotationModels](../../groupdocs.annotation.models.annotationmodels/)
* assembly [GroupDocs.Annotation](../../)


