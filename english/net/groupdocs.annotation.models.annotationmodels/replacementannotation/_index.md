---
title: Class ReplacementAnnotation
second_title: GroupDocs.Annotation for .NET API Reference
description: GroupDocs.Annotation.Models.AnnotationModels.ReplacementAnnotation class. Represents replacement annotation properties
type: docs
weight: 680
url: /net/groupdocs.annotation.models.annotationmodels/replacementannotation/
---
## ReplacementAnnotation class

Represents replacement annotation properties

```csharp
public class ReplacementAnnotation : AnnotationBase, IEquatable<ReplacementAnnotation>, 
    IReplacementAnnotation
```

## Constructors

| Name | Description |
| --- | --- |
| [ReplacementAnnotation](replacementannotation/)() | Initializes new instance of `ReplacementAnnotation` class. |

## Properties

| Name | Description |
| --- | --- |
| [BackgroundColor](../../groupdocs.annotation.models.annotationmodels/replacementannotation/backgroundcolor/) { get; set; } | Gets or sets replacement annotation background color |
| [CreatedOn](../../groupdocs.annotation.models.annotationmodels/annotationbase/createdon/) { get; set; } | Gets or sets annotation creation date |
| [FontColor](../../groupdocs.annotation.models.annotationmodels/replacementannotation/fontcolor/) { get; set; } | Gets or sets replacement annotation text color |
| [FontSize](../../groupdocs.annotation.models.annotationmodels/replacementannotation/fontsize/) { get; set; } | Gets or sets replacement annotation text size |
| [Id](../../groupdocs.annotation.models.annotationmodels/annotationbase/id/) { get; set; } | Gets or sets annotation unique identifier. This field is auto-incremented. |
| [Message](../../groupdocs.annotation.models.annotationmodels/annotationbase/message/) { get; set; } | Gets or sets annotation message |
| [Opacity](../../groupdocs.annotation.models.annotationmodels/replacementannotation/opacity/) { get; set; } | Gets or sets replacement annotation opacity |
| [PageNumber](../../groupdocs.annotation.models.annotationmodels/annotationbase/pagenumber/) { get; set; } | Page number where the annotation should be located |
| [Points](../../groupdocs.annotation.models.annotationmodels/replacementannotation/points/) { get; set; } | Gets or sets collection of points that describe rectangles with text |
| [Replies](../../groupdocs.annotation.models.annotationmodels/annotationbase/replies/) { get; set; } | The list of replies (comments) attached to the annotation |
| [StateBeforeAnnotation](../../groupdocs.annotation.models.annotationmodels/annotationbase/statebeforeannotation/) { get; set; } | Stores the previous state of the text. State that was before annotating |
| [TextToReplace](../../groupdocs.annotation.models.annotationmodels/replacementannotation/texttoreplace/) { get; set; } | Gets or sets text to be replaced with |
| [Type](../../groupdocs.annotation.models.annotationmodels/annotationbase/type/) { get; set; } | Gets or sets annotation type |
| [User](../../groupdocs.annotation.models.annotationmodels/annotationbase/user/) { get; set; } | Gets or sets annotation author |

## Methods

| Name | Description |
| --- | --- |
| override [Clone](../../groupdocs.annotation.models.annotationmodels/replacementannotation/clone/)() | Returns new instance with the same values |
| [Equals](../../groupdocs.annotation.models.annotationmodels/annotationbase/equals/)(AnnotationBase) | Compares Base Annotations using IEquatable Equals method |
| override [Equals](../../groupdocs.annotation.models.annotationmodels/replacementannotation/equals/#equals_2)(object) | Compares replacement annotation using standard object Equals method |
| [Equals](../../groupdocs.annotation.models.annotationmodels/replacementannotation/equals/#equals_1)(ReplacementAnnotation) | Compares replacement annotation using IEquatable Equals method |
| override [GetHashCode](../../groupdocs.annotation.models.annotationmodels/replacementannotation/gethashcode/)() | Returns HashCode of the replacement annotation |

## Remarks

**Learn more**

* More about annotation types and annotating PDF and Microsoft Word documents, Excel spreadsheets and PowerPoint Presentations: [How to annotate documents using GroupDocs.Annotation for .NET](https://docs.groupdocs.com/display/annotationnet/Add+annotation+to+the+document)
* More about adding replacement annotations to documents of various types: [How to add replacement annotations in C#](https://docs.groupdocs.com/display/annotationnet/Add+replacement+annotation)

### See Also

* class [AnnotationBase](../annotationbase/)
* interface [IReplacementAnnotation](../../groupdocs.annotation.models.annotationmodels.interfaces.annotations/ireplacementannotation/)
* namespace [GroupDocs.Annotation.Models.AnnotationModels](../../groupdocs.annotation.models.annotationmodels/)
* assembly [GroupDocs.Annotation](../../)


