---
title: PreviewOptions.PreviewOptions
second_title: GroupDocs.Annotation for .NET API Reference
description: PreviewOptions constructor. Initializes a new instance of PreviewOptions class
type: docs
weight: 10
url: /net/groupdocs.annotation.options/previewoptions/previewoptions/
---
## PreviewOptions(CreatePageStream) {#constructor}

Initializes a new instance of [`PreviewOptions`](../) class.

```csharp
public PreviewOptions(CreatePageStream createPageStream)
```

| Parameter | Type | Description |
| --- | --- | --- |
| createPageStream | CreatePageStream | Delegate which defines method to create output page preview stream. |

### See Also

* delegate [CreatePageStream](../../createpagestream/)
* class [PreviewOptions](../)
* namespace [GroupDocs.Annotation.Options](../../previewoptions/)
* assembly [GroupDocs.Annotation](../../../)

---

## PreviewOptions(CreatePageStream, ReleasePageStream) {#constructor_1}

Initializes a new instance of [`PreviewOptions`](../) class.

```csharp
public PreviewOptions(CreatePageStream createPageStream, ReleasePageStream releasePageStream)
```

| Parameter | Type | Description |
| --- | --- | --- |
| createPageStream | CreatePageStream | Delegate which defines method to create output page preview stream. |
| releasePageStream | ReleasePageStream | Delegate which defines method to release output page preview stream. |

### See Also

* delegate [CreatePageStream](../../createpagestream/)
* delegate [ReleasePageStream](../../releasepagestream/)
* class [PreviewOptions](../)
* namespace [GroupDocs.Annotation.Options](../../previewoptions/)
* assembly [GroupDocs.Annotation](../../../)


