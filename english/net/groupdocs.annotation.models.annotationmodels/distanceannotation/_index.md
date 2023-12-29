---
title: Class DistanceAnnotation
second_title: GroupDocs.Annotation for .NET API Reference
description: GroupDocs.Annotation.Models.AnnotationModels.DistanceAnnotation class. Represents distance annotation properties
type: docs
weight: 230
url: /net/groupdocs.annotation.models.annotationmodels/distanceannotation/
---
## DistanceAnnotation class

Represents distance annotation properties

```csharp
public class DistanceAnnotation : AnnotationBase, IDistanceAnnotation, 
    IEquatable<DistanceAnnotation>
```

## Constructors

| Name | Description |
| --- | --- |
| [DistanceAnnotation](distanceannotation/)() | Initializes new instance of `DistanceAnnotation` class. |

## Properties

| Name | Description |
| --- | --- |
| [Box](../../groupdocs.annotation.models.annotationmodels/distanceannotation/box/) { get; set; } | Gets or sets distance annotation position |
| [CreatedOn](../../groupdocs.annotation.models.annotationmodels/annotationbase/createdon/) { get; set; } | Gets or sets annotation creation date |
| [Id](../../groupdocs.annotation.models.annotationmodels/annotationbase/id/) { get; set; } | Gets or sets annotation unique identifier. This field is auto-incremented. |
| [Message](../../groupdocs.annotation.models.annotationmodels/annotationbase/message/) { get; set; } | Gets or sets annotation message |
| [Opacity](../../groupdocs.annotation.models.annotationmodels/distanceannotation/opacity/) { get; set; } | Gets or sets distance annotatio opacity |
| [PageNumber](../../groupdocs.annotation.models.annotationmodels/annotationbase/pagenumber/) { get; set; } | Page number where the annotation should be located |
| [PenColor](../../groupdocs.annotation.models.annotationmodels/distanceannotation/pencolor/) { get; set; } | Gets or sets distance annotatio pen color |
| [PenStyle](../../groupdocs.annotation.models.annotationmodels/distanceannotation/penstyle/) { get; set; } | Gets or sets distance annotatio pen style |
| [PenWidth](../../groupdocs.annotation.models.annotationmodels/distanceannotation/penwidth/) { get; set; } | Gets or sets distance annotatio pen width |
| [Replies](../../groupdocs.annotation.models.annotationmodels/annotationbase/replies/) { get; set; } | The list of replies (comments) attached to the annotation |
| [StateBeforeAnnotation](../../groupdocs.annotation.models.annotationmodels/annotationbase/statebeforeannotation/) { get; set; } |  |
| [Type](../../groupdocs.annotation.models.annotationmodels/annotationbase/type/) { get; set; } | Gets or sets annotation type |
| [User](../../groupdocs.annotation.models.annotationmodels/annotationbase/user/) { get; set; } | Gets or sets annotation author |

## Methods

| Name | Description |
| --- | --- |
| override [Clone](../../groupdocs.annotation.models.annotationmodels/distanceannotation/clone/)() | Returns new instance with the same values |
| [Equals](../../groupdocs.annotation.models.annotationmodels/annotationbase/equals/)(AnnotationBase) | Compares Base Annotations using IEquatable Equals method |
| [Equals](../../groupdocs.annotation.models.annotationmodels/distanceannotation/equals/#equals_1)(DistanceAnnotation) | Compares distance annotation using IEquatable Equals method |
| override [Equals](../../groupdocs.annotation.models.annotationmodels/distanceannotation/equals/#equals_2)(object) | Compares distance annotation using standard object Equals method |
| override [GetHashCode](../../groupdocs.annotation.models.annotationmodels/distanceannotation/gethashcode/)() | Returns HashCode of the distance annotation |

## Remarks

**Learn more**

* More about annotation types and annotating PDF and Microsoft Word documents, Excel spreadsheets and PowerPoint Presentations: [How to annotate documents using GroupDocs.Annotation for .NET](https://docs.groupdocs.com/display/annotationnet/Add+annotation+to+the+document)
* More about adding distance annotations to documents of various types: [How to add distance annotations in C#](https://docs.groupdocs.com/display/annotationnet/Add+distance+annotation)

### See Also

* class [AnnotationBase](../annotationbase/)
* interface [IDistanceAnnotation](../../groupdocs.annotation.models.annotationmodels.interfaces.annotations/idistanceannotation/)
* namespace [GroupDocs.Annotation.Models.AnnotationModels](../../groupdocs.annotation.models.annotationmodels/)
* assembly [GroupDocs.Annotation](../../)


