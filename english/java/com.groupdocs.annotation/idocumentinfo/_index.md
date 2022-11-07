---
title: IDocumentInfo
second_title: GroupDocs.Annotation for Java API Reference
description: Information about document
type: docs
weight: 13
url: /java/com.groupdocs.annotation/idocumentinfo/
---```
public interface IDocumentInfo
```

Information about document
## Methods

| Method | Description |
| --- | --- |
| [getFileType()](#getFileType--) | Document type |
| [setFileType(FileType value)](#setFileType-com.groupdocs.annotation.options.FileType-) | Document type |
| [getPageCount()](#getPageCount--) | Number of pages |
| [setPageCount(int value)](#setPageCount-int-) | Number of pages |
| [getPagesInfo()](#getPagesInfo--) | Pages Info |
| [setPagesInfo(List<PageInfo> value)](#setPagesInfo-java.util.List-com.groupdocs.annotation.models.PageInfo--) | Pages Info |
| [getSize()](#getSize--) | File size |
| [setSize(long value)](#setSize-long-) | File size |
### getFileType() {#getFileType--}
```
public abstract FileType getFileType()
```


Document type

**Returns:**
[FileType](../../com.groupdocs.annotation.options/filetype) - 
### setFileType(FileType value) {#setFileType-com.groupdocs.annotation.options.FileType-}
```
public abstract void setFileType(FileType value)
```


Document type

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [FileType](../../com.groupdocs.annotation.options/filetype) |  |

### getPageCount() {#getPageCount--}
```
public abstract int getPageCount()
```


Number of pages

**Returns:**
int - 
### setPageCount(int value) {#setPageCount-int-}
```
public abstract void setPageCount(int value)
```


Number of pages

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getPagesInfo() {#getPagesInfo--}
```
public abstract List<PageInfo> getPagesInfo()
```


Pages Info

**Returns:**
java.util.List<com.groupdocs.annotation.models.PageInfo> - 
### setPagesInfo(List<PageInfo> value) {#setPagesInfo-java.util.List-com.groupdocs.annotation.models.PageInfo--}
```
public abstract void setPagesInfo(List<PageInfo> value)
```


Pages Info

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.util.List<com.groupdocs.annotation.models.PageInfo> |  |

### getSize() {#getSize--}
```
public abstract long getSize()
```


File size

**Returns:**
long - 
### setSize(long value) {#setSize-long-}
```
public abstract void setSize(long value)
```


File size

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | long |  |

