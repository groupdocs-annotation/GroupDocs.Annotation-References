---
title: Class HighlightAnnotation
second_title: GroupDocs.Annotation for .NET API Reference
description: GroupDocs.Annotation.Models.AnnotationModels.HighlightAnnotation class. Represents highlight annotation properties
type: docs
weight: 250
url: /net/groupdocs.annotation.models.annotationmodels/highlightannotation/
---
## HighlightAnnotation class

Represents highlight annotation properties

```csharp
public class HighlightAnnotation : AnnotationBase, IEquatable<HighlightAnnotation>, 
    IHighlightAnnotation
```

## Constructors

| Name | Description |
| --- | --- |
| [HighlightAnnotation](highlightannotation/)() | Initializes new instance of `HighlightAnnotation` class. |

## Properties

| Name | Description |
| --- | --- |
| [BackgroundColor](../../groupdocs.annotation.models.annotationmodels/highlightannotation/backgroundcolor/) { get; set; } | Gets or sets highlight annotation background color |
| [CreatedOn](../../groupdocs.annotation.models.annotationmodels/annotationbase/createdon/) { get; set; } | Gets or sets annotation creation date |
| [FontColor](../../groupdocs.annotation.models.annotationmodels/highlightannotation/fontcolor/) { get; set; } | Gets or sets highlight annotation text font color |
| [Id](../../groupdocs.annotation.models.annotationmodels/annotationbase/id/) { get; set; } | Gets or sets annotation unique identifier. This field is auto-incremented. |
| [Message](../../groupdocs.annotation.models.annotationmodels/annotationbase/message/) { get; set; } | Gets or sets annotation message |
| [Opacity](../../groupdocs.annotation.models.annotationmodels/highlightannotation/opacity/) { get; set; } | Gets or sets highlight annotation opacity |
| [PageNumber](../../groupdocs.annotation.models.annotationmodels/annotationbase/pagenumber/) { get; set; } | Page number where the annotation should be located |
| [Points](../../groupdocs.annotation.models.annotationmodels/highlightannotation/points/) { get; set; } | Gets or sets collection of points that describe rectangles with text |
| [Replies](../../groupdocs.annotation.models.annotationmodels/annotationbase/replies/) { get; set; } | The list of replies (comments) attached to the annotation |
| [StateBeforeAnnotation](../../groupdocs.annotation.models.annotationmodels/annotationbase/statebeforeannotation/) { get; set; } |  |
| [Type](../../groupdocs.annotation.models.annotationmodels/annotationbase/type/) { get; set; } | Gets or sets annotation type |
| [User](../../groupdocs.annotation.models.annotationmodels/annotationbase/user/) { get; set; } | Gets or sets annotation author |

## Methods

| Name | Description |
| --- | --- |
| override [Clone](../../groupdocs.annotation.models.annotationmodels/highlightannotation/clone/)() | Returns new instance with the same values |
| [Equals](../../groupdocs.annotation.models.annotationmodels/annotationbase/equals/)(AnnotationBase) | Compares Base Annotations using IEquatable Equals method |
| [Equals](../../groupdocs.annotation.models.annotationmodels/highlightannotation/equals/#equals_1)(HighlightAnnotation) | Compares highlight annotation using IEquatable Equals method |
| override [Equals](../../groupdocs.annotation.models.annotationmodels/highlightannotation/equals/#equals_2)(object) | Compares highlight annotations using standard object Equals method |
| override [GetHashCode](../../groupdocs.annotation.models.annotationmodels/highlightannotation/gethashcode/)() | Returns HashCode of the highlight annotation |

## Remarks

**Learn more**

* More about annotation types and annotating PDF and Microsoft Word documents, Excel spreadsheets and PowerPoint Presentations: [How to annotate documents using GroupDocs.Annotation for .NET](https://docs.groupdocs.com/display/annotationnet/Add+annotation+to+the+document)
* More about adding highlight annotations to documents of various types: [How to add highlight annotations in C#](https://docs.groupdocs.com/display/annotationnet/Add+highlight+annotation)

### See Also

* class [AnnotationBase](../annotationbase/)
* interface [IHighlightAnnotation](../../groupdocs.annotation.models.annotationmodels.interfaces.annotations/ihighlightannotation/)
* namespace [GroupDocs.Annotation.Models.AnnotationModels](../../groupdocs.annotation.models.annotationmodels/)
* assembly [GroupDocs.Annotation](../../)


