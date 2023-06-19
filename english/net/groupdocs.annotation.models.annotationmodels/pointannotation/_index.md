---
title: Class PointAnnotation
second_title: GroupDocs.Annotation for .NET API Reference
description: GroupDocs.Annotation.Models.AnnotationModels.PointAnnotation class. Represents point annotation properties
type: docs
weight: 700
url: /net/groupdocs.annotation.models.annotationmodels/pointannotation/
---
## PointAnnotation class

Represents point annotation properties

```csharp
public class PointAnnotation : AnnotationBase, IEquatable<PointAnnotation>, IPointAnnotation
```

## Constructors

| Name | Description |
| --- | --- |
| [PointAnnotation](pointannotation/)() | Initializes new instance of `PointAnnotation` class. |

## Properties

| Name | Description |
| --- | --- |
| [Box](../../groupdocs.annotation.models.annotationmodels/pointannotation/box/) { get; set; } | Gets or sets point annotation position |
| [CreatedOn](../../groupdocs.annotation.models.annotationmodels/annotationbase/createdon/) { get; set; } | Gets or sets annotation creation date |
| [Id](../../groupdocs.annotation.models.annotationmodels/annotationbase/id/) { get; set; } | Gets or sets annotation unique identifier. This field is auto-incremented. |
| [Message](../../groupdocs.annotation.models.annotationmodels/annotationbase/message/) { get; set; } | Gets or sets annotation message |
| [PageNumber](../../groupdocs.annotation.models.annotationmodels/annotationbase/pagenumber/) { get; set; } | Page number where the annotation should be located |
| [Replies](../../groupdocs.annotation.models.annotationmodels/annotationbase/replies/) { get; set; } | The list of replies (comments) attached to the annotation |
| [StateBeforeAnnotation](../../groupdocs.annotation.models.annotationmodels/annotationbase/statebeforeannotation/) { get; set; } |  |
| [Type](../../groupdocs.annotation.models.annotationmodels/annotationbase/type/) { get; set; } | Gets or sets annotation type |
| [User](../../groupdocs.annotation.models.annotationmodels/annotationbase/user/) { get; set; } | Gets or sets annotation author |

## Methods

| Name | Description |
| --- | --- |
| override [Clone](../../groupdocs.annotation.models.annotationmodels/pointannotation/clone/)() | Returns new instance with the same values |
| [Equals](../../groupdocs.annotation.models.annotationmodels/annotationbase/equals/)(AnnotationBase) | Compares Base Annotations using IEquatable Equals method |
| override [Equals](../../groupdocs.annotation.models.annotationmodels/pointannotation/equals/#equals_2)(object) | Compares point annotation using standard object Equals method |
| [Equals](../../groupdocs.annotation.models.annotationmodels/pointannotation/equals/#equals_1)(PointAnnotation) | Compares point annotation using IEquatable Equals method |
| override [GetHashCode](../../groupdocs.annotation.models.annotationmodels/pointannotation/gethashcode/)() | Returns HashCode of the point annotation |

## Remarks

**Learn more**

* More about annotation types and annotating PDF and Microsoft Word documents, Excel spreadsheets and PowerPoint Presentations: [How to annotate documents using GroupDocs.Annotation for .NET](https://docs.groupdocs.com/display/annotationnet/Add+annotation+to+the+document)
* More about adding point annotations to documents of various types: [How to add point annotations in C#](https://docs.groupdocs.com/display/annotationnet/Add+point+annotation)

### See Also

* class [AnnotationBase](../annotationbase/)
* interface [IPointAnnotation](../../groupdocs.annotation.models.annotationmodels.interfaces.annotations/ipointannotation/)
* namespace [GroupDocs.Annotation.Models.AnnotationModels](../../groupdocs.annotation.models.annotationmodels/)
* assembly [GroupDocs.Annotation](../../)


