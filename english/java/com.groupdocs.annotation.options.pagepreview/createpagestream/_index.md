---
title: CreatePageStream
second_title: GroupDocs.Annotation for Java API Reference
description: Delegate that defines method to create output page preview stream.
type: docs
weight: 10
url: /java/com.groupdocs.annotation.options.pagepreview/createpagestream/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.Delegate, com.aspose.ms.System.MulticastDelegate
```
public abstract class CreatePageStream extends System.MulticastDelegate
```

Delegate that defines method to create output page preview stream.
## Constructors

| Constructor | Description |
| --- | --- |
| [CreatePageStream()](#CreatePageStream--) |  |
## Methods

| Method | Description |
| --- | --- |
| [invoke(int pageNumber)](#invoke-int-) |  |
| [beginInvoke(int pageNumber, System.AsyncCallback callback, Object state)](#beginInvoke-int-com.aspose.ms.System.AsyncCallback-java.lang.Object-) |  |
| [endInvoke(System.IAsyncResult result)](#endInvoke-com.aspose.ms.System.IAsyncResult-) |  |
### CreatePageStream() {#CreatePageStream--}
```
public CreatePageStream()
```


### invoke(int pageNumber) {#invoke-int-}
```
public abstract OutputStream invoke(int pageNumber)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pageNumber | int |  |

**Returns:**
java.io.OutputStream
### beginInvoke(int pageNumber, System.AsyncCallback callback, Object state) {#beginInvoke-int-com.aspose.ms.System.AsyncCallback-java.lang.Object-}
```
public final System.IAsyncResult beginInvoke(int pageNumber, System.AsyncCallback callback, Object state)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pageNumber | int |  |
| callback | com.aspose.ms.System.AsyncCallback |  |
| state | java.lang.Object |  |

**Returns:**
com.aspose.ms.System.IAsyncResult
### endInvoke(System.IAsyncResult result) {#endInvoke-com.aspose.ms.System.IAsyncResult-}
```
public final OutputStream endInvoke(System.IAsyncResult result)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| result | com.aspose.ms.System.IAsyncResult |  |

**Returns:**
java.io.OutputStream
