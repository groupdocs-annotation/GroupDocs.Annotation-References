---
title: ReleasePageStream
second_title: GroupDocs.Annotation for Java API Reference
description: Delegate that defines method to release output page preview stream.
type: docs
weight: 12
url: /java/com.groupdocs.annotation.options.pagepreview/releasepagestream/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.Delegate, com.aspose.ms.System.MulticastDelegate
```
public abstract class ReleasePageStream extends System.MulticastDelegate
```

Delegate that defines method to release output page preview stream.
## Constructors

| Constructor | Description |
| --- | --- |
| [ReleasePageStream()](#ReleasePageStream--) |  |
## Methods

| Method | Description |
| --- | --- |
| [invoke(int pageNumber, OutputStream pageStream)](#invoke-int-java.io.OutputStream-) |  |
| [beginInvoke(int pageNumber, OutputStream pageStream, System.AsyncCallback callback, Object state)](#beginInvoke-int-java.io.OutputStream-com.aspose.ms.System.AsyncCallback-java.lang.Object-) |  |
| [endInvoke(System.IAsyncResult result)](#endInvoke-com.aspose.ms.System.IAsyncResult-) |  |
### ReleasePageStream() {#ReleasePageStream--}
```
public ReleasePageStream()
```


### invoke(int pageNumber, OutputStream pageStream) {#invoke-int-java.io.OutputStream-}
```
public abstract void invoke(int pageNumber, OutputStream pageStream)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pageNumber | int |  |
| pageStream | java.io.OutputStream |  |

### beginInvoke(int pageNumber, OutputStream pageStream, System.AsyncCallback callback, Object state) {#beginInvoke-int-java.io.OutputStream-com.aspose.ms.System.AsyncCallback-java.lang.Object-}
```
public final System.IAsyncResult beginInvoke(int pageNumber, OutputStream pageStream, System.AsyncCallback callback, Object state)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pageNumber | int |  |
| pageStream | java.io.OutputStream |  |
| callback | com.aspose.ms.System.AsyncCallback |  |
| state | java.lang.Object |  |

**Returns:**
com.aspose.ms.System.IAsyncResult
### endInvoke(System.IAsyncResult result) {#endInvoke-com.aspose.ms.System.IAsyncResult-}
```
public final void endInvoke(System.IAsyncResult result)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| result | com.aspose.ms.System.IAsyncResult |  |

