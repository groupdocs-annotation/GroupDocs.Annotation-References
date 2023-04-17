---
title: ICache
second_title: GroupDocs.Annotation for Java API Reference
description: Defines methods required for storing rendered document and document resources cache.
type: docs
weight: 11
url: /java/com.groupdocs.annotation.cache/icache/
---```
public interface ICache
```

Defines methods required for storing rendered document and document resources cache.
## Methods

| Method | Description |
| --- | --- |
| [set(String key, Object value)](#set-java.lang.String-java.lang.Object-) | Inserts a cache entry into the cache. |
| [getKeys(String filter)](#getKeys-java.lang.String-) | Returns all keys matching filter. |
### set(String key, Object value) {#set-java.lang.String-java.lang.Object-}
```
public abstract void set(String key, Object value)
```


Inserts a cache entry into the cache.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| key | java.lang.String | A unique identifier for the cache entry. |
| value | java.lang.Object | The object to insert. |

### getKeys(String filter) {#getKeys-java.lang.String-}
```
public abstract System.Collections.Generic.IGenericEnumerable<String> getKeys(String filter)
```


Returns all keys matching filter.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| filter | java.lang.String | The filter to use. |

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable<java.lang.String> - Keys matching the filter.
