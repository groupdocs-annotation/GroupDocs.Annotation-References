---
title: Class AnnotationBase
second_title: GroupDocs.Annotation for .NET API Reference
description: GroupDocs.Annotation.Models.AnnotationModels.AnnotationBase class. Base class for all annotation types. Contains basic annotation information
type: docs
weight: 200
url: /net/groupdocs.annotation.models.annotationmodels/annotationbase/
---
## AnnotationBase class

Base class for all annotation types. Contains basic annotation information

```csharp
public abstract class AnnotationBase : ICloneable, IEquatable<AnnotationBase>
```

## Properties

| Name | Description |
| --- | --- |
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
| virtual [Clone](../../groupdocs.annotation.models.annotationmodels/annotationbase/clone/)() | Returns new instance with the same values |
| [Equals](../../groupdocs.annotation.models.annotationmodels/annotationbase/equals/#equals)(AnnotationBase) | Compares Base Annotations using IEquatable Equals method |
| override [Equals](../../groupdocs.annotation.models.annotationmodels/annotationbase/equals/#equals_1)(object) | Compares Base Annotations using standard object Equals method |
| override [GetHashCode](../../groupdocs.annotation.models.annotationmodels/annotationbase/gethashcode/)() | Returns HashCode of AnnotationBase Message, PageNumber and Type Properties |

### See Also

* namespace [GroupDocs.Annotation.Models.AnnotationModels](../../groupdocs.annotation.models.annotationmodels/)
* assembly [GroupDocs.Annotation](../../)


