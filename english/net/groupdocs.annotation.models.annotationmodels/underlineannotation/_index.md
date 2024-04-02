---
title: Class UnderlineAnnotation
second_title: GroupDocs.Annotation for .NET API Reference
description: GroupDocs.Annotation.Models.AnnotationModels.UnderlineAnnotation class. Represents underline annotation properties
type: docs
weight: 750
url: /net/groupdocs.annotation.models.annotationmodels/underlineannotation/
---
## UnderlineAnnotation class

Represents underline annotation properties

```csharp
public class UnderlineAnnotation : AnnotationBase, IEquatable<UnderlineAnnotation>, 
    IUnderlineAnnotation
```

## Constructors

| Name | Description |
| --- | --- |
| [UnderlineAnnotation](underlineannotation/)() | Initializes new instance of `UnderlineAnnotation` class. |

## Properties

| Name | Description |
| --- | --- |
| [BackgroundColor](../../groupdocs.annotation.models.annotationmodels/underlineannotation/backgroundcolor/) { get; set; } | Gets or sets underline annotation text background color |
| [CreatedOn](../../groupdocs.annotation.models.annotationmodels/annotationbase/createdon/) { get; set; } | Gets or sets annotation creation date |
| [FontColor](../../groupdocs.annotation.models.annotationmodels/underlineannotation/fontcolor/) { get; set; } | Gets or sets underline annotation text color |
| [Id](../../groupdocs.annotation.models.annotationmodels/annotationbase/id/) { get; set; } | Gets or sets annotation unique identifier. This field is auto-incremented. |
| [Message](../../groupdocs.annotation.models.annotationmodels/annotationbase/message/) { get; set; } | Gets or sets annotation message |
| [Opacity](../../groupdocs.annotation.models.annotationmodels/underlineannotation/opacity/) { get; set; } | Gets or sets underline annotation opacity |
| [PageNumber](../../groupdocs.annotation.models.annotationmodels/annotationbase/pagenumber/) { get; set; } | Page number where the annotation should be located |
| [Points](../../groupdocs.annotation.models.annotationmodels/underlineannotation/points/) { get; set; } | Gets or sets collection of points that describe rectangles with text |
| [Replies](../../groupdocs.annotation.models.annotationmodels/annotationbase/replies/) { get; set; } | The list of replies (comments) attached to the annotation |
| [StateBeforeAnnotation](../../groupdocs.annotation.models.annotationmodels/annotationbase/statebeforeannotation/) { get; set; } | Stores the previous state of the text. State that was before annotating |
| [Type](../../groupdocs.annotation.models.annotationmodels/annotationbase/type/) { get; set; } | Gets or sets annotation type |
| [UnderlineColor](../../groupdocs.annotation.models.annotationmodels/underlineannotation/underlinecolor/) { get; set; } | Gets or sets underline annotation color |
| [User](../../groupdocs.annotation.models.annotationmodels/annotationbase/user/) { get; set; } | Gets or sets annotation author |

## Methods

| Name | Description |
| --- | --- |
| override [Clone](../../groupdocs.annotation.models.annotationmodels/underlineannotation/clone/)() | Returns new instance with the same values |
| [Equals](../../groupdocs.annotation.models.annotationmodels/annotationbase/equals/)(AnnotationBase) | Compares Base Annotations using IEquatable Equals method |
| override [Equals](../../groupdocs.annotation.models.annotationmodels/underlineannotation/equals/#equals_2)(object) | Compares underline annotation using standard object Equals method |
| [Equals](../../groupdocs.annotation.models.annotationmodels/underlineannotation/equals/#equals_1)(UnderlineAnnotation) | Compares underline annotation using IEquatable Equals method |
| override [GetHashCode](../../groupdocs.annotation.models.annotationmodels/underlineannotation/gethashcode/)() | Returns HashCode of the underline annotation |

## Remarks

**Learn more**

* More about annotation types and annotating PDF and Microsoft Word documents, Excel spreadsheets and PowerPoint Presentations: [How to annotate documents using GroupDocs.Annotation for .NET](https://docs.groupdocs.com/display/annotationnet/Add+annotation+to+the+document)
* More about adding underline annotations to documents of various types: [How to add underline annotations in C#](https://docs.groupdocs.com/display/annotationnet/Add+underline+annotation)

### See Also

* class [AnnotationBase](../annotationbase/)
* interface [IUnderlineAnnotation](../../groupdocs.annotation.models.annotationmodels.interfaces.annotations/iunderlineannotation/)
* namespace [GroupDocs.Annotation.Models.AnnotationModels](../../groupdocs.annotation.models.annotationmodels/)
* assembly [GroupDocs.Annotation](../../)


