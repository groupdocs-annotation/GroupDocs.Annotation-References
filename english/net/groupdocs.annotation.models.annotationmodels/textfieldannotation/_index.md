---
title: Class TextFieldAnnotation
second_title: GroupDocs.Annotation for .NET API Reference
description: GroupDocs.Annotation.Models.AnnotationModels.TextFieldAnnotation class. Represents text field annotation properties
type: docs
weight: 730
url: /net/groupdocs.annotation.models.annotationmodels/textfieldannotation/
---
## TextFieldAnnotation class

Represents text field annotation properties

```csharp
public class TextFieldAnnotation : AnnotationBase, IEquatable<TextFieldAnnotation>, 
    ITextFieldAnnotation
```

## Constructors

| Name | Description |
| --- | --- |
| [TextFieldAnnotation](textfieldannotation/)() | Initializes new instance of `TextFieldAnnotation` class. |

## Properties

| Name | Description |
| --- | --- |
| [BackgroundColor](../../groupdocs.annotation.models.annotationmodels/textfieldannotation/backgroundcolor/) { get; set; } | Gets or sets text field annotation background color |
| [Box](../../groupdocs.annotation.models.annotationmodels/textfieldannotation/box/) { get; set; } | Gets or sets text field annotation position |
| [CreatedOn](../../groupdocs.annotation.models.annotationmodels/annotationbase/createdon/) { get; set; } | Gets or sets annotation creation date |
| [FontColor](../../groupdocs.annotation.models.annotationmodels/textfieldannotation/fontcolor/) { get; set; } | Gets or sets text field annotation text font color |
| [FontFamily](../../groupdocs.annotation.models.annotationmodels/textfieldannotation/fontfamily/) { get; set; } | Gets or sets text field annotation text font family |
| [FontSize](../../groupdocs.annotation.models.annotationmodels/textfieldannotation/fontsize/) { get; set; } | Gets or sets text field annotation font size |
| [Id](../../groupdocs.annotation.models.annotationmodels/annotationbase/id/) { get; set; } | Gets or sets annotation unique identifier. This field is auto-incremented. |
| [Message](../../groupdocs.annotation.models.annotationmodels/annotationbase/message/) { get; set; } | Gets or sets annotation message |
| [Opacity](../../groupdocs.annotation.models.annotationmodels/textfieldannotation/opacity/) { get; set; } | Gets or sets text field annotation opacity |
| [PageNumber](../../groupdocs.annotation.models.annotationmodels/annotationbase/pagenumber/) { get; set; } | Page number where the annotation should be located |
| [PenColor](../../groupdocs.annotation.models.annotationmodels/textfieldannotation/pencolor/) { get; set; } | Gets or sets text field annotation pen color |
| [PenStyle](../../groupdocs.annotation.models.annotationmodels/textfieldannotation/penstyle/) { get; set; } | Gets or sets text field annotation pen style |
| [PenWidth](../../groupdocs.annotation.models.annotationmodels/textfieldannotation/penwidth/) { get; set; } | Gets or sets text field annotation pen width |
| [Replies](../../groupdocs.annotation.models.annotationmodels/annotationbase/replies/) { get; set; } | The list of replies (comments) attached to the annotation |
| [StateBeforeAnnotation](../../groupdocs.annotation.models.annotationmodels/annotationbase/statebeforeannotation/) { get; set; } | Stores the previous state of the text. State that was before annotating |
| [Text](../../groupdocs.annotation.models.annotationmodels/textfieldannotation/text/) { get; set; } | Gets or sets text field annotation text |
| [TextHorizontalAlignment](../../groupdocs.annotation.models.annotationmodels/textfieldannotation/texthorizontalalignment/) { get; set; } | Gets or sets horizontal alignment of the text |
| [Type](../../groupdocs.annotation.models.annotationmodels/annotationbase/type/) { get; set; } | Gets or sets annotation type |
| [User](../../groupdocs.annotation.models.annotationmodels/annotationbase/user/) { get; set; } | Gets or sets annotation author |

## Methods

| Name | Description |
| --- | --- |
| override [Clone](../../groupdocs.annotation.models.annotationmodels/textfieldannotation/clone/)() | Returns new instance with the same values |
| [Equals](../../groupdocs.annotation.models.annotationmodels/annotationbase/equals/)(AnnotationBase) | Compares Base Annotations using IEquatable Equals method |
| override [Equals](../../groupdocs.annotation.models.annotationmodels/textfieldannotation/equals/#equals_2)(object) | Compares text field annotation using standard object Equals method |
| [Equals](../../groupdocs.annotation.models.annotationmodels/textfieldannotation/equals/#equals_1)(TextFieldAnnotation) | Compares text field annotation using IEquatable Equals method |
| override [GetHashCode](../../groupdocs.annotation.models.annotationmodels/textfieldannotation/gethashcode/)() | Returns HashCode of the text field annotation |

## Remarks

**Learn more**

* More about annotation types and annotating PDF and Microsoft Word documents, Excel spreadsheets and PowerPoint Presentations: [How to annotate documents using GroupDocs.Annotation for .NET](https://docs.groupdocs.com/display/annotationnet/Add+annotation+to+the+document)
* More about adding text field annotations to documents of various types: [How to add text field annotations in C#](https://docs.groupdocs.com/display/annotationnet/Add+text+field+annotation)

### See Also

* class [AnnotationBase](../annotationbase/)
* interface [ITextFieldAnnotation](../../groupdocs.annotation.models.annotationmodels.interfaces.annotations/itextfieldannotation/)
* namespace [GroupDocs.Annotation.Models.AnnotationModels](../../groupdocs.annotation.models.annotationmodels/)
* assembly [GroupDocs.Annotation](../../)


