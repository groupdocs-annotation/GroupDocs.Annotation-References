---
title: Class LinkAnnotation
second_title: GroupDocs.Annotation for .NET API Reference
description: GroupDocs.Annotation.Models.AnnotationModels.LinkAnnotation class. Represents link annotation properties
type: docs
weight: 650
url: /net/groupdocs.annotation.models.annotationmodels/linkannotation/
---
## LinkAnnotation class

Represents link annotation properties

```csharp
public class LinkAnnotation : AnnotationBase, IEquatable<LinkAnnotation>, ILinkAnnotation
```

## Constructors

| Name | Description |
| --- | --- |
| [LinkAnnotation](linkannotation/)() | Initializes new instance of `LinkAnnotation` class. |

## Properties

| Name | Description |
| --- | --- |
| [BackgroundColor](../../groupdocs.annotation.models.annotationmodels/linkannotation/backgroundcolor/) { get; set; } | Gets or sets link annotation background color |
| [CreatedOn](../../groupdocs.annotation.models.annotationmodels/annotationbase/createdon/) { get; set; } | Gets or sets annotation creation date |
| [FontColor](../../groupdocs.annotation.models.annotationmodels/linkannotation/fontcolor/) { get; set; } | Gets or sets link annotation text color |
| [Id](../../groupdocs.annotation.models.annotationmodels/annotationbase/id/) { get; set; } | Gets or sets annotation unique identifier. This field is auto-incremented. |
| [Message](../../groupdocs.annotation.models.annotationmodels/annotationbase/message/) { get; set; } | Gets or sets annotation message |
| [Opacity](../../groupdocs.annotation.models.annotationmodels/linkannotation/opacity/) { get; set; } | Gets or sets link annotation opacity |
| [PageNumber](../../groupdocs.annotation.models.annotationmodels/annotationbase/pagenumber/) { get; set; } | Page number where the annotation should be located |
| [Points](../../groupdocs.annotation.models.annotationmodels/linkannotation/points/) { get; set; } | Gets or sets link annotation coordinates as an array of points |
| [Replies](../../groupdocs.annotation.models.annotationmodels/annotationbase/replies/) { get; set; } | The list of replies (comments) attached to the annotation |
| [StateBeforeAnnotation](../../groupdocs.annotation.models.annotationmodels/annotationbase/statebeforeannotation/) { get; set; } | Stores the previous state of the text. State that was before annotating |
| [Type](../../groupdocs.annotation.models.annotationmodels/annotationbase/type/) { get; set; } | Gets or sets annotation type |
| [Url](../../groupdocs.annotation.models.annotationmodels/linkannotation/url/) { get; set; } | Gets or sets annotation link url |
| [User](../../groupdocs.annotation.models.annotationmodels/annotationbase/user/) { get; set; } | Gets or sets annotation author |

## Methods

| Name | Description |
| --- | --- |
| override [Clone](../../groupdocs.annotation.models.annotationmodels/linkannotation/clone/)() | Returns new instance with the same values |
| [Equals](../../groupdocs.annotation.models.annotationmodels/annotationbase/equals/)(AnnotationBase) | Compares Base Annotations using IEquatable Equals method |
| [Equals](../../groupdocs.annotation.models.annotationmodels/linkannotation/equals/#equals_1)(LinkAnnotation) | Compares link annotation using IEquatable Equals method |
| override [Equals](../../groupdocs.annotation.models.annotationmodels/linkannotation/equals/#equals_2)(object) | Compares link annotation using standard object Equals method |
| override [GetHashCode](../../groupdocs.annotation.models.annotationmodels/linkannotation/gethashcode/)() | Returns HashCode of link annotation |

## Remarks

**Learn more**

* More about annotation types and annotating PDF and Microsoft Word documents, Excel spreadsheets and PowerPoint Presentations: [How to annotate documents using GroupDocs.Annotation for .NET](https://docs.groupdocs.com/display/annotationnet/Add+annotation+to+the+document)
* More about adding link annotations to documents of various types: [How to add link annotations in C#](https://docs.groupdocs.com/display/annotationnet/Add+link+annotation)

### See Also

* class [AnnotationBase](../annotationbase/)
* interface [ILinkAnnotation](../../groupdocs.annotation.models.annotationmodels.interfaces.annotations/ilinkannotation/)
* namespace [GroupDocs.Annotation.Models.AnnotationModels](../../groupdocs.annotation.models.annotationmodels/)
* assembly [GroupDocs.Annotation](../../)


