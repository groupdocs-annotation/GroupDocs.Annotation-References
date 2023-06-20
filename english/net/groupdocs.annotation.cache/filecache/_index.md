---
title: Class FileCache
second_title: GroupDocs.Annotation for .NET API Reference
description: GroupDocs.Annotation.Cache.FileCache class. Class that allows to work with the local ondisk cache
type: docs
weight: 1280
url: /net/groupdocs.annotation.cache/filecache/
---
## FileCache class

Class that allows to work with the local on-disk cache.

```csharp
public class FileCache : ICache
```

## Constructors

| Name | Description |
| --- | --- |
| [FileCache](filecache/#constructor)() | Initializes new instance of `FileCache` class. |
| [FileCache](filecache/#constructor_1)(string) | Initializes new instance of `FileCache` class. |

## Methods

| Name | Description |
| --- | --- |
| [GetKeys](../../groupdocs.annotation.cache/filecache/getkeys/)(string) | Returns all file names that contains filter in filename. |
| [Set](../../groupdocs.annotation.cache/filecache/set/)(string, object) | Serializes data to the local disk. |
| [TryGetValue](../../groupdocs.annotation.cache/filecache/trygetvalue/)(string, out object) | Deserializes data associated with this key if present. |

### See Also

* interface [ICache](../icache/)
* namespace [GroupDocs.Annotation.Cache](../../groupdocs.annotation.cache/)
* assembly [GroupDocs.Annotation](../../)


