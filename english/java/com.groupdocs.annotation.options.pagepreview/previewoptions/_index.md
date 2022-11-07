---
title: PreviewOptions
second_title: GroupDocs.Annotation for Java API Reference
description: Represents document preview options.
type: docs
weight: 11
url: /java/com.groupdocs.annotation.options.pagepreview/previewoptions/
---
**Inheritance:**
java.lang.Object
```
public class PreviewOptions
```

Represents document preview options.
## Constructors

| Constructor | Description |
| --- | --- |
| [PreviewOptions(CreatePageStream createPageStream)](#PreviewOptions-com.groupdocs.annotation.options.pagepreview.CreatePageStream-) | Initializes a new instance of [PreviewOptions](../../com.groupdocs.annotation.options.pagepreview/previewoptions) class. |
| [PreviewOptions(CreatePageStream createPageStream, ReleasePageStream releasePageStream)](#PreviewOptions-com.groupdocs.annotation.options.pagepreview.CreatePageStream-com.groupdocs.annotation.options.pagepreview.ReleasePageStream-) | Initializes a new instance of [PreviewOptions](../../com.groupdocs.annotation.options.pagepreview/previewoptions) class. |
## Methods

| Method | Description |
| --- | --- |
| [getCreatePageStream()](#getCreatePageStream--) | Delegate which defines method to create output page preview stream. |
| [setCreatePageStream(CreatePageStream value)](#setCreatePageStream-com.groupdocs.annotation.options.pagepreview.CreatePageStream-) | Delegate which defines method to create output page preview stream. |
| [getReleasePageStream()](#getReleasePageStream--) | Delegate which defines method to remove output page preview stream |
| [setReleasePageStream(ReleasePageStream value)](#setReleasePageStream-com.groupdocs.annotation.options.pagepreview.ReleasePageStream-) | Delegate which defines method to remove output page preview stream |
| [getWidth()](#getWidth--) | Page preview width. |
| [setWidth(int value)](#setWidth-int-) | Page preview width. |
| [getHeight()](#getHeight--) | Page preview height. |
| [setHeight(int value)](#setHeight-int-) | Page preview height. |
| [getPageNumbers()](#getPageNumbers--) | Page numbers that will be previewed. |
| [setPageNumbers(int[] value)](#setPageNumbers-int---) | Page numbers that will be previewed. |
| [getPreviewFormat()](#getPreviewFormat--) | Preview image format. |
| [setPreviewFormat(int value)](#setPreviewFormat-int-) | Preview image format. |
| [getResolution()](#getResolution--) |  |
| [setResolution(int value)](#setResolution-int-) |  |
| [getRenderComments()](#getRenderComments--) | The property that controls whether comments will be generated on the preview. |
| [setRenderComments(boolean value)](#setRenderComments-boolean-) | The property that controls whether comments will be generated on the preview. |
| [getRenderAnnotations()](#getRenderAnnotations--) | The property that controls whether annotations will be generated on the preview. |
| [setRenderAnnotations(boolean value)](#setRenderAnnotations-boolean-) | The property that controls whether annotations will be generated on the preview. |
| [getWorksheetColumns()](#getWorksheetColumns--) | Worksheet columns to generate. |
| [getWorksheetColumnsInternal()](#getWorksheetColumnsInternal--) |  |
| [setWorksheetColumns(List<WorksheetColumnsRange> value)](#setWorksheetColumns-java.util.List-com.groupdocs.annotation.options.pagepreview.WorksheetColumnsRange--) | Worksheet columns to generate. |
| [setWorksheetColumnsInternal(System.Collections.Generic.List<WorksheetColumnsRange> value)](#setWorksheetColumnsInternal-com.aspose.ms.System.Collections.Generic.List-com.groupdocs.annotation.options.pagepreview.WorksheetColumnsRange--) |  |
### PreviewOptions(CreatePageStream createPageStream) {#PreviewOptions-com.groupdocs.annotation.options.pagepreview.CreatePageStream-}
```
public PreviewOptions(CreatePageStream createPageStream)
```


Initializes a new instance of [PreviewOptions](../../com.groupdocs.annotation.options.pagepreview/previewoptions) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| createPageStream | [CreatePageStream](../../com.groupdocs.annotation.options.pagepreview/createpagestream) | Delegate which defines method to create output page preview stream. |

### PreviewOptions(CreatePageStream createPageStream, ReleasePageStream releasePageStream) {#PreviewOptions-com.groupdocs.annotation.options.pagepreview.CreatePageStream-com.groupdocs.annotation.options.pagepreview.ReleasePageStream-}
```
public PreviewOptions(CreatePageStream createPageStream, ReleasePageStream releasePageStream)
```


Initializes a new instance of [PreviewOptions](../../com.groupdocs.annotation.options.pagepreview/previewoptions) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| createPageStream | [CreatePageStream](../../com.groupdocs.annotation.options.pagepreview/createpagestream) | Delegate which defines method to create output page preview stream. |
| releasePageStream | [ReleasePageStream](../../com.groupdocs.annotation.options.pagepreview/releasepagestream) | Delegate which defines method to release output page preview stream. |

### getCreatePageStream() {#getCreatePageStream--}
```
public final CreatePageStream getCreatePageStream()
```


Delegate which defines method to create output page preview stream.

**Returns:**
[CreatePageStream](../../com.groupdocs.annotation.options.pagepreview/createpagestream) - 
### setCreatePageStream(CreatePageStream value) {#setCreatePageStream-com.groupdocs.annotation.options.pagepreview.CreatePageStream-}
```
public final void setCreatePageStream(CreatePageStream value)
```


Delegate which defines method to create output page preview stream.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [CreatePageStream](../../com.groupdocs.annotation.options.pagepreview/createpagestream) |  |

### getReleasePageStream() {#getReleasePageStream--}
```
public final ReleasePageStream getReleasePageStream()
```


Delegate which defines method to remove output page preview stream

**Returns:**
[ReleasePageStream](../../com.groupdocs.annotation.options.pagepreview/releasepagestream) - 
### setReleasePageStream(ReleasePageStream value) {#setReleasePageStream-com.groupdocs.annotation.options.pagepreview.ReleasePageStream-}
```
public final void setReleasePageStream(ReleasePageStream value)
```


Delegate which defines method to remove output page preview stream

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [ReleasePageStream](../../com.groupdocs.annotation.options.pagepreview/releasepagestream) |  |

### getWidth() {#getWidth--}
```
public final int getWidth()
```


Page preview width.

**Returns:**
int - 
### setWidth(int value) {#setWidth-int-}
```
public final void setWidth(int value)
```


Page preview width.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getHeight() {#getHeight--}
```
public final int getHeight()
```


Page preview height.

**Returns:**
int - 
### setHeight(int value) {#setHeight-int-}
```
public final void setHeight(int value)
```


Page preview height.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getPageNumbers() {#getPageNumbers--}
```
public final int[] getPageNumbers()
```


Page numbers that will be previewed.

**Returns:**
int[] - 
### setPageNumbers(int[] value) {#setPageNumbers-int---}
```
public final void setPageNumbers(int[] value)
```


Page numbers that will be previewed.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int[] |  |

### getPreviewFormat() {#getPreviewFormat--}
```
public final int getPreviewFormat()
```


Preview image format.

**Returns:**
int - 
### setPreviewFormat(int value) {#setPreviewFormat-int-}
```
public final void setPreviewFormat(int value)
```


Preview image format.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getResolution() {#getResolution--}
```
public int getResolution()
```




**Returns:**
int
### setResolution(int value) {#setResolution-int-}
```
public void setResolution(int value)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getRenderComments() {#getRenderComments--}
```
public final boolean getRenderComments()
```


The property that controls whether comments will be generated on the preview. Default State - true. Now Supported only in MS Word document

**Returns:**
boolean - 
### setRenderComments(boolean value) {#setRenderComments-boolean-}
```
public final void setRenderComments(boolean value)
```


The property that controls whether comments will be generated on the preview. Default State - true. Now Supported only in MS Word document

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getRenderAnnotations() {#getRenderAnnotations--}
```
public final boolean getRenderAnnotations()
```


The property that controls whether annotations will be generated on the preview. Default State - true.

**Returns:**
boolean - 
### setRenderAnnotations(boolean value) {#setRenderAnnotations-boolean-}
```
public final void setRenderAnnotations(boolean value)
```


The property that controls whether annotations will be generated on the preview. Default State - true.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getWorksheetColumns() {#getWorksheetColumns--}
```
public final List<WorksheetColumnsRange> getWorksheetColumns()
```


Worksheet columns to generate. Generation proceeds in the specified order.

**Returns:**
java.util.List<com.groupdocs.annotation.options.pagepreview.WorksheetColumnsRange> - 
### getWorksheetColumnsInternal() {#getWorksheetColumnsInternal--}
```
public System.Collections.Generic.List<WorksheetColumnsRange> getWorksheetColumnsInternal()
```




**Returns:**
com.aspose.ms.System.Collections.Generic.List<com.groupdocs.annotation.options.pagepreview.WorksheetColumnsRange>
### setWorksheetColumns(List<WorksheetColumnsRange> value) {#setWorksheetColumns-java.util.List-com.groupdocs.annotation.options.pagepreview.WorksheetColumnsRange--}
```
public final void setWorksheetColumns(List<WorksheetColumnsRange> value)
```


Worksheet columns to generate. Generation proceeds in the specified order.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.util.List<com.groupdocs.annotation.options.pagepreview.WorksheetColumnsRange> |  |

### setWorksheetColumnsInternal(System.Collections.Generic.List<WorksheetColumnsRange> value) {#setWorksheetColumnsInternal-com.aspose.ms.System.Collections.Generic.List-com.groupdocs.annotation.options.pagepreview.WorksheetColumnsRange--}
```
public void setWorksheetColumnsInternal(System.Collections.Generic.List<WorksheetColumnsRange> value)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | com.aspose.ms.System.Collections.Generic.List<com.groupdocs.annotation.options.pagepreview.WorksheetColumnsRange> |  |

