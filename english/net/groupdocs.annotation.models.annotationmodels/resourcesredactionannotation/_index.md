---
title: Class ResourcesRedactionAnnotation
second_title: GroupDocs.Annotation for .NET API Reference
description: GroupDocs.Annotation.Models.AnnotationModels.ResourcesRedactionAnnotation class. Represents resources redaction annotation properties
type: docs
weight: 730
url: /net/groupdocs.annotation.models.annotationmodels/resourcesredactionannotation/
---
## ResourcesRedactionAnnotation class

Represents resources redaction annotation properties

```csharp
public class ResourcesRedactionAnnotation : AnnotationBase, 
    IEquatable<ResourcesRedactionAnnotation>, IResourcesRedactionAnnotation
```

## Constructors

| Name | Description |
| --- | --- |
| [ResourcesRedactionAnnotation](resourcesredactionannotation/)() | Initializes new instance of `ResourcesRedactionAnnotation` class. |

## Properties

| Name | Description |
| --- | --- |
| [Box](../../groupdocs.annotation.models.annotationmodels/resourcesredactionannotation/box/) { get; set; } | Gets or sets resource redaction annotation position |
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
| override [Clone](../../groupdocs.annotation.models.annotationmodels/resourcesredactionannotation/clone/)() | Returns new instance with the same values |
| [Equals](../../groupdocs.annotation.models.annotationmodels/annotationbase/equals/)(AnnotationBase) | Compares Base Annotations using IEquatable Equals method |
| override [Equals](../../groupdocs.annotation.models.annotationmodels/resourcesredactionannotation/equals/#equals_2)(object) | Compares resource redaction annotation using standard object Equals method |
| [Equals](../../groupdocs.annotation.models.annotationmodels/resourcesredactionannotation/equals/#equals_1)(ResourcesRedactionAnnotation) | Compares resource redaction annotation using IEquatable Equals method |
| override [GetHashCode](../../groupdocs.annotation.models.annotationmodels/resourcesredactionannotation/gethashcode/)() | Returns HashCode of the resource redaction annotation |

## Remarks

**Learn more**

* More about annotation types and annotating PDF and Microsoft Word documents, Excel spreadsheets and PowerPoint Presentations: [How to annotate documents using GroupDocs.Annotation for .NET](https://docs.groupdocs.com/display/annotationnet/Add+annotation+to+the+document)
* More about adding resource redaction annotations to documents of various types: [How to add resource redaction annotations in C#](https://docs.groupdocs.com/display/annotationnet/Add+resource+redaction+annotation)

### See Also

* class [AnnotationBase](../annotationbase/)
* interface [IResourcesRedactionAnnotation](../../groupdocs.annotation.models.annotationmodels.interfaces.annotations/iresourcesredactionannotation/)
* namespace [GroupDocs.Annotation.Models.AnnotationModels](../../groupdocs.annotation.models.annotationmodels/)
* assembly [GroupDocs.Annotation](../../)


