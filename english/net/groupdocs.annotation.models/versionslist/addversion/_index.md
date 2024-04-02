---
title: VersionsList.AddVersion
second_title: GroupDocs.Annotation for .NET API Reference
description: VersionsList method. Add list of the annotations
type: docs
weight: 40
url: /net/groupdocs.annotation.models/versionslist/addversion/
---
## AddVersion(List&lt;AnnotationBase&gt;) {#addversion}

Add list of the annotations.

```csharp
public void AddVersion(List<AnnotationBase> annotations)
```

| Parameter | Type | Description |
| --- | --- | --- |
| annotations | List`1 | List of the annocations to add. [`AnnotationBase`](../../../groupdocs.annotation.models.annotationmodels/annotationbase/) |

### See Also

* class [AnnotationBase](../../../groupdocs.annotation.models.annotationmodels/annotationbase/)
* class [VersionsList](../)
* namespace [GroupDocs.Annotation.Models](../../versionslist/)
* assembly [GroupDocs.Annotation](../../../)

---

## AddVersion(object, List&lt;AnnotationBase&gt;) {#addversion_1}

Add list of annotations per version ley

```csharp
public void AddVersion(object newVersionKey, List<AnnotationBase> annotations)
```

| Parameter | Type | Description |
| --- | --- | --- |
| newVersionKey | Object | Key of the version |
| annotations | List`1 | List of the annotations |

### Exceptions

| exception | condition |
| --- | --- |
| Exception | Throws an exception if version key already exists |

### See Also

* class [AnnotationBase](../../../groupdocs.annotation.models.annotationmodels/annotationbase/)
* class [VersionsList](../)
* namespace [GroupDocs.Annotation.Models](../../versionslist/)
* assembly [GroupDocs.Annotation](../../../)


