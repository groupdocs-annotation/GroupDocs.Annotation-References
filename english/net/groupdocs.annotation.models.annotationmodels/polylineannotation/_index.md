---
title: Class PolylineAnnotation
second_title: GroupDocs.Annotation for .NET API Reference
description: GroupDocs.Annotation.Models.AnnotationModels.PolylineAnnotation class. Represents polyline annotation properties
type: docs
weight: 670
url: /net/groupdocs.annotation.models.annotationmodels/polylineannotation/
---
## PolylineAnnotation class

Represents polyline annotation properties

```csharp
public class PolylineAnnotation : AnnotationBase, IEquatable<PolylineAnnotation>, 
    IPolylineAnnotation
```

## Constructors

| Name | Description |
| --- | --- |
| [PolylineAnnotation](polylineannotation/)() | Initializes new instance of [`AreaAnnotation`](../areaannotation/) class. |

## Properties

| Name | Description |
| --- | --- |
| [Box](../../groupdocs.annotation.models.annotationmodels/polylineannotation/box/) { get; set; } | Gets or sets polyline annotation position |
| [CreatedOn](../../groupdocs.annotation.models.annotationmodels/annotationbase/createdon/) { get; set; } | Gets or sets annotation creation date |
| [Id](../../groupdocs.annotation.models.annotationmodels/annotationbase/id/) { get; set; } | Gets or sets annotation unique identifier. This field is auto-incremented. |
| [Message](../../groupdocs.annotation.models.annotationmodels/annotationbase/message/) { get; set; } | Gets or sets annotation message |
| [Opacity](../../groupdocs.annotation.models.annotationmodels/polylineannotation/opacity/) { get; set; } | Gets or sets polyline annotation opacity |
| [PageNumber](../../groupdocs.annotation.models.annotationmodels/annotationbase/pagenumber/) { get; set; } | Page number where the annotation should be located |
| [PenColor](../../groupdocs.annotation.models.annotationmodels/polylineannotation/pencolor/) { get; set; } | Gets or sets polyline annotation pen color |
| [PenStyle](../../groupdocs.annotation.models.annotationmodels/polylineannotation/penstyle/) { get; set; } | Gets or sets polyline annotation pen style |
| [PenWidth](../../groupdocs.annotation.models.annotationmodels/polylineannotation/penwidth/) { get; set; } | Gets or sets polyline annotation pen width |
| [Replies](../../groupdocs.annotation.models.annotationmodels/annotationbase/replies/) { get; set; } | The list of replies (comments) attached to the annotation |
| [StateBeforeAnnotation](../../groupdocs.annotation.models.annotationmodels/annotationbase/statebeforeannotation/) { get; set; } | Stores the previous state of the text. State that was before annotating |
| [SvgPath](../../groupdocs.annotation.models.annotationmodels/polylineannotation/svgpath/) { get; set; } | Gets or sets polyline annotation SVG path |
| [Type](../../groupdocs.annotation.models.annotationmodels/annotationbase/type/) { get; set; } | Gets or sets annotation type |
| [User](../../groupdocs.annotation.models.annotationmodels/annotationbase/user/) { get; set; } | Gets or sets annotation author |

## Methods

| Name | Description |
| --- | --- |
| override [Clone](../../groupdocs.annotation.models.annotationmodels/polylineannotation/clone/)() | Returns new instance with the same values |
| [Equals](../../groupdocs.annotation.models.annotationmodels/annotationbase/equals/)(AnnotationBase) | Compares Base Annotations using IEquatable Equals method |
| override [Equals](../../groupdocs.annotation.models.annotationmodels/polylineannotation/equals/#equals_2)(object) | Compares polyline annotation using standard object Equals method |
| [Equals](../../groupdocs.annotation.models.annotationmodels/polylineannotation/equals/#equals_1)(PolylineAnnotation) | Compares polyline annotation using IEquatable Equals method |
| override [GetHashCode](../../groupdocs.annotation.models.annotationmodels/polylineannotation/gethashcode/)() | Returns HashCode of the polyline annotation |

## Remarks

**Learn more**

* More about annotation types and annotating PDF and Microsoft Word documents, Excel spreadsheets and PowerPoint Presentations: [How to annotate documents using GroupDocs.Annotation for .NET](https://docs.groupdocs.com/display/annotationnet/Add+annotation+to+the+document)
* More about adding polyline annotations to documents of various types: [How to add polyline annotations in C#](https://docs.groupdocs.com/display/annotationnet/Add+polyline+annotation)

### See Also

* class [AnnotationBase](../annotationbase/)
* interface [IPolylineAnnotation](../../groupdocs.annotation.models.annotationmodels.interfaces.annotations/ipolylineannotation/)
* namespace [GroupDocs.Annotation.Models.AnnotationModels](../../groupdocs.annotation.models.annotationmodels/)
* assembly [GroupDocs.Annotation](../../)


