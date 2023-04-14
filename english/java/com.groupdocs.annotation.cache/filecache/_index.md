---
title: FileCache
second_title: GroupDocs.Annotation for Java API Reference
description: Represents a local on-disk cache.
type: docs
weight: 10
url: /java/com.groupdocs.annotation.cache/filecache/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.annotation.cache.ICache](../../com.groupdocs.annotation.cache/icache)
```
public class FileCache implements ICache
```

Represents a local on-disk cache.
## Constructors

| Constructor | Description |
| --- | --- |
| [FileCache()](#FileCache--) | Initializes new instance of [FileCache](../../com.groupdocs.annotation.cache/filecache) class. |
| [FileCache(String path)](#FileCache-java.lang.String-) | Initializes new instance of [FileCache](../../com.groupdocs.annotation.cache/filecache) class. |
## Methods

| Method | Description |
| --- | --- |
| [getKeys(String filter)](#getKeys-java.lang.String-) | Returns all file names that contains filter in filename. |
| [set(String key, Object value)](#set-java.lang.String-java.lang.Object-) | Serializes data to the local disk. |
### FileCache() {#FileCache--}
```
public FileCache()
```


Initializes new instance of [FileCache](../../com.groupdocs.annotation.cache/filecache) class.

### FileCache(String path) {#FileCache-java.lang.String-}
```
public FileCache(String path)
```


Initializes new instance of [FileCache](../../com.groupdocs.annotation.cache/filecache) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| path | java.lang.String | Path where cache data will be saved |

### getKeys(String filter) {#getKeys-java.lang.String-}
```
public final System.Collections.Generic.IGenericEnumerable<String> getKeys(String filter)
```


Returns all file names that contains filter in filename.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| filter | java.lang.String | The filter to use. |

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable<java.lang.String> - File names that contains filter in filename.
### set(String key, Object value) {#set-java.lang.String-java.lang.Object-}
```
public final void set(String key, Object value)
```


Serializes data to the local disk.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| key | java.lang.String | An unique identifier for the cache entry. |
| value | java.lang.Object | The object to serialize. |

