---
title: Class AreaAnnotation
second_title: GroupDocs.Annotation for .NET API Reference
description: GroupDocs.Annotation.Models.AnnotationModels.AreaAnnotation class. Represents area annotation properties
type: docs
weight: 210
url: /net/groupdocs.annotation.models.annotationmodels/areaannotation/
---
## AreaAnnotation class

Represents area annotation properties

```csharp
public class AreaAnnotation : AnnotationBase, IAreaAnnotation, IEquatable<AreaAnnotation>
```

## Constructors

| Name | Description |
| --- | --- |
| [AreaAnnotation](areaannotation/)() | Initializes new instance of `AreaAnnotation` class. |

## Properties

| Name | Description |
| --- | --- |
| [BackgroundColor](../../groupdocs.annotation.models.annotationmodels/areaannotation/backgroundcolor/) { get; set; } | Gets or sets area annotation background color |
| [Box](../../groupdocs.annotation.models.annotationmodels/areaannotation/box/) { get; set; } | Gets or sets area annotation position |
| [CreatedOn](../../groupdocs.annotation.models.annotationmodels/annotationbase/createdon/) { get; set; } | Gets or sets annotation creation date |
| [Id](../../groupdocs.annotation.models.annotationmodels/annotationbase/id/) { get; set; } | Gets or sets annotation unique identifier. This field is auto-incremented. |
| [Message](../../groupdocs.annotation.models.annotationmodels/annotationbase/message/) { get; set; } | Gets or sets annotation message |
| [Opacity](../../groupdocs.annotation.models.annotationmodels/areaannotation/opacity/) { get; set; } | Gets or sets area annotation opacity |
| [PageNumber](../../groupdocs.annotation.models.annotationmodels/annotationbase/pagenumber/) { get; set; } | Page number where the annotation should be located |
| [PenColor](../../groupdocs.annotation.models.annotationmodels/areaannotation/pencolor/) { get; set; } | Gets or sets area annotation pen color |
| [PenStyle](../../groupdocs.annotation.models.annotationmodels/areaannotation/penstyle/) { get; set; } | Gets or sets area annotation pen style |
| [PenWidth](../../groupdocs.annotation.models.annotationmodels/areaannotation/penwidth/) { get; set; } | Gets or sets area annotation pen width |
| [Replies](../../groupdocs.annotation.models.annotationmodels/annotationbase/replies/) { get; set; } | The list of replies (comments) attached to the annotation |
| [StateBeforeAnnotation](../../groupdocs.annotation.models.annotationmodels/annotationbase/statebeforeannotation/) { get; set; } | Stores the previous state of the text. State that was before annotating |
| [Type](../../groupdocs.annotation.models.annotationmodels/annotationbase/type/) { get; set; } | Gets or sets annotation type |
| [User](../../groupdocs.annotation.models.annotationmodels/annotationbase/user/) { get; set; } | Gets or sets annotation author |

## Methods

| Name | Description |
| --- | --- |
| override [Clone](../../groupdocs.annotation.models.annotationmodels/areaannotation/clone/)() | Returns new instance of the area annotation with the same values |
| [Equals](../../groupdocs.annotation.models.annotationmodels/annotationbase/equals/)(AnnotationBase) | Compares Base Annotations using IEquatable Equals method |
| [Equals](../../groupdocs.annotation.models.annotationmodels/areaannotation/equals/#equals_1)(AreaAnnotation) | Compares area annotation using IEquatable Equals method |
| override [Equals](../../groupdocs.annotation.models.annotationmodels/areaannotation/equals/#equals_2)(object) | Compares area annotation using standard object Equals method |
| override [GetHashCode](../../groupdocs.annotation.models.annotationmodels/areaannotation/gethashcode/)() | Returns HashCode of Area Annotation instance |

## Remarks

**Learn more**

* More about annotation types and annotating PDF and Microsoft Word documents, Excel spreadsheets and PowerPoint Presentations: [How to annotate documents using GroupDocs.Annotation for .NET](https://docs.groupdocs.com/display/annotationnet/Add+annotation+to+the+document)
* More about adding area annotations to documents of various types: [How to add area annotations in C#](https://docs.groupdocs.com/display/annotationnet/Add+area+annotation)

### See Also

* class [AnnotationBase](../annotationbase/)
* interface [IAreaAnnotation](../../groupdocs.annotation.models.annotationmodels.interfaces.annotations/iareaannotation/)
* namespace [GroupDocs.Annotation.Models.AnnotationModels](../../groupdocs.annotation.models.annotationmodels/)
* assembly [GroupDocs.Annotation](../../)


