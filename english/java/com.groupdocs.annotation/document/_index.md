---
title: Document
second_title: GroupDocs.Annotation for Java API Reference
description: Represents document properties
type: docs
weight: 12
url: /java/com.groupdocs.annotation/document/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.io.Closeable
```
public class Document implements Closeable
```

Represents document properties
## Constructors

| Constructor | Description |
| --- | --- |
| [Document(InputStream stream)](#Document-java.io.InputStream-) | Initializes new instance of [Document](../../com.groupdocs.annotation/document) class. |
| [Document(InputStream stream, String password)](#Document-java.io.InputStream-java.lang.String-) | Initializes new instance of [Document](../../com.groupdocs.annotation/document) class. |
## Methods

| Method | Description |
| --- | --- |
| [setCache(ICache value)](#setCache-com.groupdocs.annotation.cache.ICache-) |  |
| [getName()](#getName--) | Document name |
| [setName(String value)](#setName-java.lang.String-) | Document name |
| [getStreamSize()](#getStreamSize--) | Document size |
| [createStream()](#createStream--) | Creates Document input stream |
| [getPassword()](#getPassword--) | Document password |
| [setPassword(String value)](#setPassword-java.lang.String-) |  |
| [getRotation()](#getRotation--) | Document Rotation |
| [setRotation(Byte value)](#setRotation-java.lang.Byte-) | Document Rotation |
| [getProcessPages()](#getProcessPages--) | Document pages |
| [setProcessPages(int value)](#setProcessPages-int-) | Document pages |
| [generatePreview(PreviewOptions previewOptions)](#generatePreview-com.groupdocs.annotation.options.pagepreview.PreviewOptions-) | Generates document pages preview. |
| [getDocumentInfo()](#getDocumentInfo--) | Gets information about document - document type and size, pages count etc. |
| [close()](#close--) |  |
### Document(InputStream stream) {#Document-java.io.InputStream-}
```
public Document(InputStream stream)
```


Initializes new instance of [Document](../../com.groupdocs.annotation/document) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.InputStream | The document stream. |

### Document(InputStream stream, String password) {#Document-java.io.InputStream-java.lang.String-}
```
public Document(InputStream stream, String password)
```


Initializes new instance of [Document](../../com.groupdocs.annotation/document) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.InputStream | The document stream. |
| password | java.lang.String | The document password. |

### setCache(ICache value) {#setCache-com.groupdocs.annotation.cache.ICache-}
```
public final void setCache(ICache value)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [ICache](../../com.groupdocs.annotation.cache/icache) |  |

### getName() {#getName--}
```
public final String getName()
```


Document name

**Returns:**
java.lang.String - 
### setName(String value) {#setName-java.lang.String-}
```
public final void setName(String value)
```


Document name

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getStreamSize() {#getStreamSize--}
```
public final long getStreamSize()
```


Document size

**Returns:**
long - 
### createStream() {#createStream--}
```
public final InputStream createStream()
```


Creates Document input stream

**Returns:**
java.io.InputStream
### getPassword() {#getPassword--}
```
public final String getPassword()
```


Document password

**Returns:**
java.lang.String
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getRotation() {#getRotation--}
```
public final Byte getRotation()
```


Document Rotation

**Returns:**
java.lang.Byte - 
### setRotation(Byte value) {#setRotation-java.lang.Byte-}
```
public final void setRotation(Byte value)
```


Document Rotation

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.Byte |  |

### getProcessPages() {#getProcessPages--}
```
public final int getProcessPages()
```


Document pages

**Returns:**
int - 
### setProcessPages(int value) {#setProcessPages-int-}
```
public final void setProcessPages(int value)
```


Document pages

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### generatePreview(PreviewOptions previewOptions) {#generatePreview-com.groupdocs.annotation.options.pagepreview.PreviewOptions-}
```
public final void generatePreview(PreviewOptions previewOptions)
```


Generates document pages preview.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| previewOptions | [PreviewOptions](../../com.groupdocs.annotation.options.pagepreview/previewoptions) | The document preview options |

### getDocumentInfo() {#getDocumentInfo--}
```
public final IDocumentInfo getDocumentInfo()
```


Gets information about document - document type and size, pages count etc.

**Returns:**
[IDocumentInfo](../../com.groupdocs.annotation/idocumentinfo) - 
### close() {#close--}
```
public void close()
```




