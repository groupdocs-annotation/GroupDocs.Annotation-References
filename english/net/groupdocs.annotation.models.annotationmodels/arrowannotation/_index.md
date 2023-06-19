---
title: Class ArrowAnnotation
second_title: GroupDocs.Annotation for .NET API Reference
description: GroupDocs.Annotation.Models.AnnotationModels.ArrowAnnotation class. Represents arrow annotation properties
type: docs
weight: 640
url: /net/groupdocs.annotation.models.annotationmodels/arrowannotation/
---
## ArrowAnnotation class

Represents arrow annotation properties

```csharp
public class ArrowAnnotation : AnnotationBase, IArrowAnnotation, IEquatable<ArrowAnnotation>
```

## Constructors

| Name | Description |
| --- | --- |
| [ArrowAnnotation](arrowannotation/)() | Initializes new instance of `ArrowAnnotation` class. |

## Properties

| Name | Description |
| --- | --- |
| [Box](../../groupdocs.annotation.models.annotationmodels/arrowannotation/box/) { get; set; } | Gets or sets arrow annotation position |
| [CreatedOn](../../groupdocs.annotation.models.annotationmodels/annotationbase/createdon/) { get; set; } | Gets or sets annotation creation date |
| [Id](../../groupdocs.annotation.models.annotationmodels/annotationbase/id/) { get; set; } | Gets or sets annotation unique identifier. This field is auto-incremented. |
| [Message](../../groupdocs.annotation.models.annotationmodels/annotationbase/message/) { get; set; } | Gets or sets annotation message |
| [Opacity](../../groupdocs.annotation.models.annotationmodels/arrowannotation/opacity/) { get; set; } | Gets or sets arrow annotation opacity |
| [PageNumber](../../groupdocs.annotation.models.annotationmodels/annotationbase/pagenumber/) { get; set; } | Page number where the annotation should be located |
| [PenColor](../../groupdocs.annotation.models.annotationmodels/arrowannotation/pencolor/) { get; set; } | Gets or sets arrow annotation pen color |
| [PenStyle](../../groupdocs.annotation.models.annotationmodels/arrowannotation/penstyle/) { get; set; } | Gets or sets arrow annotation pen style |
| [PenWidth](../../groupdocs.annotation.models.annotationmodels/arrowannotation/penwidth/) { get; set; } | Gets or sets arrow annotation pen width |
| [Replies](../../groupdocs.annotation.models.annotationmodels/annotationbase/replies/) { get; set; } | The list of replies (comments) attached to the annotation |
| [StateBeforeAnnotation](../../groupdocs.annotation.models.annotationmodels/annotationbase/statebeforeannotation/) { get; set; } |  |
| [Type](../../groupdocs.annotation.models.annotationmodels/annotationbase/type/) { get; set; } | Gets or sets annotation type |
| [User](../../groupdocs.annotation.models.annotationmodels/annotationbase/user/) { get; set; } | Gets or sets annotation author |

## Methods

| Name | Description |
| --- | --- |
| override [Clone](../../groupdocs.annotation.models.annotationmodels/arrowannotation/clone/)() | Returns new instance with same values |
| [Equals](../../groupdocs.annotation.models.annotationmodels/annotationbase/equals/)(AnnotationBase) | Compares Base Annotations using IEquatable Equals method |
| [Equals](../../groupdocs.annotation.models.annotationmodels/arrowannotation/equals/#equals_1)(ArrowAnnotation) | Compares area annotation using IEquatable Equals method |
| override [Equals](../../groupdocs.annotation.models.annotationmodels/arrowannotation/equals/#equals_2)(object) | Compares arrow annotation using standard object Equals method |
| override [GetHashCode](../../groupdocs.annotation.models.annotationmodels/arrowannotation/gethashcode/)() | Returns HashCode of the arrow annotation |

## Remarks

**Learn more**

* More about annotation types and annotating PDF and Microsoft Word documents, Excel spreadsheets and PowerPoint Presentations: [How to annotate documents using GroupDocs.Annotation for .NET](https://docs.groupdocs.com/display/annotationnet/Add+annotation+to+the+document)
* More about adding arrow annotations to documents of various types: [How to add arrow annotations in C#](https://docs.groupdocs.com/display/annotationnet/Add+arrow+annotation)

### See Also

* class [AnnotationBase](../annotationbase/)
* interface [IArrowAnnotation](../../groupdocs.annotation.models.annotationmodels.interfaces.annotations/iarrowannotation/)
* namespace [GroupDocs.Annotation.Models.AnnotationModels](../../groupdocs.annotation.models.annotationmodels/)
* assembly [GroupDocs.Annotation](../../)


