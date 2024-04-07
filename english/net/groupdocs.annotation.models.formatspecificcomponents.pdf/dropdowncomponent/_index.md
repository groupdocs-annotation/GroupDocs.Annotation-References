---
title: Class DropdownComponent
second_title: GroupDocs.Annotation for .NET API Reference
description: GroupDocs.Annotation.Models.FormatSpecificComponents.Pdf.DropdownComponent class. Represents dropdown component properties
type: docs
weight: 820
url: /net/groupdocs.annotation.models.formatspecificcomponents.pdf/dropdowncomponent/
---
## DropdownComponent class

Represents dropdown component properties

```csharp
public class DropdownComponent : AnnotationBase, IDropdownComponent
```

## Constructors

| Name | Description |
| --- | --- |
| [DropdownComponent](dropdowncomponent/)() | Initializes new instance of `DropdownComponent` class. |

## Properties

| Name | Description |
| --- | --- |
| [Box](../../groupdocs.annotation.models.formatspecificcomponents.pdf/dropdowncomponent/box/) { get; set; } | Gets or sets component position |
| [CreatedOn](../../groupdocs.annotation.models.annotationmodels/annotationbase/createdon/) { get; set; } | Gets or sets annotation creation date |
| [Id](../../groupdocs.annotation.models.annotationmodels/annotationbase/id/) { get; set; } | Gets or sets annotation unique identifier. This field is auto-incremented. |
| [Message](../../groupdocs.annotation.models.annotationmodels/annotationbase/message/) { get; set; } | Gets or sets annotation message |
| [Options](../../groupdocs.annotation.models.formatspecificcomponents.pdf/dropdowncomponent/options/) { get; set; } | List of options (drop down items) to be shown when component is clicked |
| [PageNumber](../../groupdocs.annotation.models.annotationmodels/annotationbase/pagenumber/) { get; set; } | Page number where the annotation should be located |
| [PenColor](../../groupdocs.annotation.models.formatspecificcomponents.pdf/dropdowncomponent/pencolor/) { get; set; } | Gets or sets component pen color |
| [PenStyle](../../groupdocs.annotation.models.formatspecificcomponents.pdf/dropdowncomponent/penstyle/) { get; set; } | Gets or sets component pen style |
| [PenWidth](../../groupdocs.annotation.models.formatspecificcomponents.pdf/dropdowncomponent/penwidth/) { get; set; } | Gets or sets component pen width |
| [Placeholder](../../groupdocs.annotation.models.formatspecificcomponents.pdf/dropdowncomponent/placeholder/) { get; set; } | Text to shown when no options has been selected yet |
| [Replies](../../groupdocs.annotation.models.annotationmodels/annotationbase/replies/) { get; set; } | The list of replies (comments) attached to the annotation |
| [SelectedOption](../../groupdocs.annotation.models.formatspecificcomponents.pdf/dropdowncomponent/selectedoption/) { get; set; } | Number of option to be selected by default |
| [StateBeforeAnnotation](../../groupdocs.annotation.models.annotationmodels/annotationbase/statebeforeannotation/) { get; set; } | Stores the previous state of the text. State that was before annotating |
| [Type](../../groupdocs.annotation.models.annotationmodels/annotationbase/type/) { get; set; } | Gets or sets annotation type |
| [User](../../groupdocs.annotation.models.annotationmodels/annotationbase/user/) { get; set; } | Gets or sets annotation author |

## Methods

| Name | Description |
| --- | --- |
| override [Clone](../../groupdocs.annotation.models.formatspecificcomponents.pdf/dropdowncomponent/clone/)() | Returns new Instance with same values |
| [Equals](../../groupdocs.annotation.models.annotationmodels/annotationbase/equals/)(AnnotationBase) | Compares Base Annotations using IEquatable Equals method |
| [Equals](../../groupdocs.annotation.models.formatspecificcomponents.pdf/dropdowncomponent/equals/#equals_1)(DropdownComponent) | Compares Dropdown component using IEquatable Equals method |
| override [Equals](../../groupdocs.annotation.models.formatspecificcomponents.pdf/dropdowncomponent/equals/#equals_2)(object) | Compares Dropdown Components using standard object Equals method |
| override [GetHashCode](../../groupdocs.annotation.models.formatspecificcomponents.pdf/dropdowncomponent/gethashcode/)() | Returns HashCode of Dropdown Component |

## Remarks

**Learn more**

* More about annotation types and annotating PDF: [How to annotate documents using GroupDocs.Annotation for .NET](https://docs.groupdocs.com/display/annotationnet/Add+annotation+to+the+document)
* More about adding dropdown components to PDF: [How to add dropdown component in C#](https://docs.groupdocs.com/display/annotationnet/Add+dropdown+component)

### See Also

* class [AnnotationBase](../../groupdocs.annotation.models.annotationmodels/annotationbase/)
* interface [IDropdownComponent](../../groupdocs.annotation.models.formatspecificcomponents.pdf.interfaces/idropdowncomponent/)
* namespace [GroupDocs.Annotation.Models.FormatSpecificComponents.Pdf](../../groupdocs.annotation.models.formatspecificcomponents.pdf/)
* assembly [GroupDocs.Annotation](../../)


