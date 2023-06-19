---
title: Class ImageAnnotation
second_title: GroupDocs.Annotation for .NET API Reference
description: GroupDocs.Annotation.Models.AnnotationModels.ImageAnnotation class. Represents image annotation properties
type: docs
weight: 680
url: /net/groupdocs.annotation.models.annotationmodels/imageannotation/
---
## ImageAnnotation class

Represents image annotation properties

```csharp
public class ImageAnnotation : AnnotationBase, IAngle, IBox, IEquatable<ImageAnnotation>, IOpacity
```

## Constructors

| Name | Description |
| --- | --- |
| [ImageAnnotation](imageannotation/)() | Initializes new instance of `ImageAnnotation` class. |

## Properties

| Name | Description |
| --- | --- |
| [Angle](../../groupdocs.annotation.models.annotationmodels/imageannotation/angle/) { get; set; } | Gets or sets image annotation rotation angle |
| [Box](../../groupdocs.annotation.models.annotationmodels/imageannotation/box/) { get; set; } | Gets or sets image annotation position |
| [CreatedOn](../../groupdocs.annotation.models.annotationmodels/annotationbase/createdon/) { get; set; } | Gets or sets annotation creation date |
| [Id](../../groupdocs.annotation.models.annotationmodels/annotationbase/id/) { get; set; } | Gets or sets annotation unique identifier. This field is auto-incremented. |
| [ImageData](../../groupdocs.annotation.models.annotationmodels/imageannotation/imagedata/) { get; set; } | Gets or sets image annotation data |
| [ImageExtension](../../groupdocs.annotation.models.annotationmodels/imageannotation/imageextension/) { get; set; } | Gets or sets image annotation data |
| [ImagePath](../../groupdocs.annotation.models.annotationmodels/imageannotation/imagepath/) { get; set; } | Gets or sets image annotation path |
| [Message](../../groupdocs.annotation.models.annotationmodels/annotationbase/message/) { get; set; } | Gets or sets annotation message |
| [Opacity](../../groupdocs.annotation.models.annotationmodels/imageannotation/opacity/) { get; set; } | Gets or sets image annotation opacity |
| [PageNumber](../../groupdocs.annotation.models.annotationmodels/annotationbase/pagenumber/) { get; set; } | Page number where the annotation should be located |
| [Replies](../../groupdocs.annotation.models.annotationmodels/annotationbase/replies/) { get; set; } | The list of replies (comments) attached to the annotation |
| [StateBeforeAnnotation](../../groupdocs.annotation.models.annotationmodels/annotationbase/statebeforeannotation/) { get; set; } |  |
| [Type](../../groupdocs.annotation.models.annotationmodels/annotationbase/type/) { get; set; } | Gets or sets annotation type |
| [User](../../groupdocs.annotation.models.annotationmodels/annotationbase/user/) { get; set; } | Gets or sets annotation author |
| [ZIndex](../../groupdocs.annotation.models.annotationmodels/imageannotation/zindex/) { get; set; } | Gets or sets image annotation z-index. Default value is 0 |

## Methods

| Name | Description |
| --- | --- |
| override [Clone](../../groupdocs.annotation.models.annotationmodels/imageannotation/clone/)() | Returns new instance with the same values |
| [Equals](../../groupdocs.annotation.models.annotationmodels/annotationbase/equals/)(AnnotationBase) | Compares Base Annotations using IEquatable Equals method |
| [Equals](../../groupdocs.annotation.models.annotationmodels/imageannotation/equals/#equals_1)(ImageAnnotation) | Compares image annotation using IEquatable Equals method |
| override [Equals](../../groupdocs.annotation.models.annotationmodels/imageannotation/equals/#equals_2)(object) | Compares image annotation using standard object Equals method |
| override [GetHashCode](../../groupdocs.annotation.models.annotationmodels/imageannotation/gethashcode/)() | Returns HashCode of Image Annotation |
| [GetImage](../../groupdocs.annotation.models.annotationmodels/imageannotation/getimage/)() | Gets image object |

## Remarks

**Learn more**

* More about annotation types and annotating PDF and Microsoft Word documents, Excel spreadsheets and PowerPoint Presentations: [How to annotate documents using GroupDocs.Annotation for .NET](https://docs.groupdocs.com/display/annotationnet/Add+annotation+to+the+document)
* More about adding image annotations to documents of various types: [How to add image annotations in C#](https://docs.groupdocs.com/display/annotationnet/Add+image+annotation)

### See Also

* class [AnnotationBase](../annotationbase/)
* interface [IAngle](../../groupdocs.annotation.models.annotationmodels.interfaces.properties/iangle/)
* interface [IBox](../../groupdocs.annotation.models.annotationmodels.interfaces.properties/ibox/)
* interface [IOpacity](../../groupdocs.annotation.models.annotationmodels.interfaces.properties/iopacity/)
* namespace [GroupDocs.Annotation.Models.AnnotationModels](../../groupdocs.annotation.models.annotationmodels/)
* assembly [GroupDocs.Annotation](../../)


