---
title: Annotator
second_title: GroupDocs.Annotation for Java API Reference
description: Represents main class that controls document annotating process.
type: docs
weight: 10
url: /java/com.groupdocs.annotation/annotator/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable, java.io.Closeable
```
public class Annotator implements System.IDisposable, Closeable
```

Represents main class that controls document annotating process.
## Constructors

| Constructor | Description |
| --- | --- |
| [Annotator(String filePath)](#Annotator-java.lang.String-) | Initialise annotator class which accept document path |
| [Annotator(String filePath, LoadOptions loadOptions)](#Annotator-java.lang.String-com.groupdocs.annotation.options.LoadOptions-) | Initialise annotator class which accept document path |
| [Annotator(String filePath, AnnotatorSettings settings)](#Annotator-java.lang.String-com.groupdocs.annotation.AnnotatorSettings-) | Initialise annotator class which accept document path |
| [Annotator(String filePath, LoadOptions loadOptions, AnnotatorSettings settings)](#Annotator-java.lang.String-com.groupdocs.annotation.options.LoadOptions-com.groupdocs.annotation.AnnotatorSettings-) | Initialise annotator class which accept document path |
| [Annotator(InputStream inputStream)](#Annotator-java.io.InputStream-) | Initialise annotator class which accept document stream |
| [Annotator(InputStream inputStream, LoadOptions loadOptions)](#Annotator-java.io.InputStream-com.groupdocs.annotation.options.LoadOptions-) | Initialise annotator class which accept document stream |
| [Annotator(InputStream inputStream, AnnotatorSettings settings)](#Annotator-java.io.InputStream-com.groupdocs.annotation.AnnotatorSettings-) | Initialise annotator class which accept document stream |
| [Annotator(InputStream inputStream, LoadOptions loadOptions, AnnotatorSettings settings)](#Annotator-java.io.InputStream-com.groupdocs.annotation.options.LoadOptions-com.groupdocs.annotation.AnnotatorSettings-) | Initialise annotator class which accept inputStream stream |
## Methods

| Method | Description |
| --- | --- |
| [getDocument()](#getDocument--) | Document |
| [getRotation()](#getRotation--) | Document Rotation |
| [setRotation(Byte value)](#setRotation-java.lang.Byte-) | Document Rotation |
| [getProcessPages()](#getProcessPages--) | Document pages |
| [setProcessPages(int value)](#setProcessPages-int-) | Document pages |
| [save()](#save--) | Saves document after adding, updating or removing annotations. |
| [save(SaveOptions saveOptions)](#save-com.groupdocs.annotation.options.export.SaveOptions-) | Saves document after adding, updating or removing annotations. |
| [save(OutputStream document)](#save-java.io.OutputStream-) | Saves document after adding, updating or removing annotations. |
| [save(String filePath)](#save-java.lang.String-) | Saves document after adding, updating or removing annotations. |
| [save(OutputStream outputStream, SaveOptions saveOptions)](#save-java.io.OutputStream-com.groupdocs.annotation.options.export.SaveOptions-) | Saves outputStream after adding, updating or removing annotations. |
| [save(String filePath, SaveOptions saveOptions)](#save-java.lang.String-com.groupdocs.annotation.options.export.SaveOptions-) | Saves document after adding, updating or removing annotations. |
| [dispose()](#dispose--) | Dispose |
| [add(AnnotationBase annotation)](#add-com.groupdocs.annotation.models.annotationmodels.AnnotationBase-) | Adds annotation to document |
| [add(List<AnnotationBase> annotations)](#add-java.util.List-com.groupdocs.annotation.models.annotationmodels.AnnotationBase--) | Adds collection of annotations to a document. |
| [update(AnnotationBase newAnnotation)](#update-com.groupdocs.annotation.models.annotationmodels.AnnotationBase-) | Updates document annotation. |
| [update(List<AnnotationBase> annotations)](#update-java.util.List-com.groupdocs.annotation.models.annotationmodels.AnnotationBase--) | Updates collection of document annotations. |
| [remove(int annotationId)](#remove-int-) | Removes annotation from document by Id. |
| [remove(AnnotationBase annotation)](#remove-com.groupdocs.annotation.models.annotationmodels.AnnotationBase-) | Removes annotation from document. |
| [remove(AnnotationBase[] annotationsToDelete)](#remove-com.groupdocs.annotation.models.annotationmodels.AnnotationBase...-) | Removes collection of annotations from document by provided annotation ids. |
| [remove(List<Integer> annotationsIdsToDelete)](#remove-java.util.List-java.lang.Integer--) | Removes collection of annotations from document by provided annotation ids. |
| [removeInternal(List<AnnotationBase> annotationsToDelete)](#removeInternal-java.util.List-com.groupdocs.annotation.models.annotationmodels.AnnotationBase--) | Removes collection of annotations from document. |
| [get()](#get--) | Gets collections of document annotations. |
| [getVersionsList()](#getVersionsList--) | Get versions. |
| [getVersion(Object version)](#getVersion-java.lang.Object-) | Get annotations from versions. |
| [get(int type)](#get-int-) | Gets collection of document annotations by annotation type. |
| [importAnnotationsFromDocument(String outputPath)](#importAnnotationsFromDocument-java.lang.String-) | Import annotations from document to XML file. |
| [exportAnnotationsFromDocument(String filePath)](#exportAnnotationsFromDocument-java.lang.String-) | Export annotations from XML document. |
| [close()](#close--) |  |
### Annotator(String filePath) {#Annotator-java.lang.String-}
```
public Annotator(String filePath)
```


Initialise annotator class which accept document path

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| filePath | java.lang.String | File path

--------------------

 **Learn more** 

 *  
 *   |

### Annotator(String filePath, LoadOptions loadOptions) {#Annotator-java.lang.String-com.groupdocs.annotation.options.LoadOptions-}
```
public Annotator(String filePath, LoadOptions loadOptions)
```


Initialise annotator class which accept document path

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| filePath | java.lang.String | File path |
| loadOptions | [LoadOptions](../../com.groupdocs.annotation.options/loadoptions) | Load options

--------------------

 **Learn more** 

 *  
 *  
 *  
 *   |

### Annotator(String filePath, AnnotatorSettings settings) {#Annotator-java.lang.String-com.groupdocs.annotation.AnnotatorSettings-}
```
public Annotator(String filePath, AnnotatorSettings settings)
```


Initialise annotator class which accept document path

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| filePath | java.lang.String | File path |
| settings | [AnnotatorSettings](../../com.groupdocs.annotation/annotatorsettings) | Annotator settings

--------------------

 **Learn more** 

 *  
 *   |

### Annotator(String filePath, LoadOptions loadOptions, AnnotatorSettings settings) {#Annotator-java.lang.String-com.groupdocs.annotation.options.LoadOptions-com.groupdocs.annotation.AnnotatorSettings-}
```
public Annotator(String filePath, LoadOptions loadOptions, AnnotatorSettings settings)
```


Initialise annotator class which accept document path

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| filePath | java.lang.String | File path |
| loadOptions | [LoadOptions](../../com.groupdocs.annotation.options/loadoptions) | Load options |
| settings | [AnnotatorSettings](../../com.groupdocs.annotation/annotatorsettings) | Annotator settings

--------------------

 **Learn more** 

 *  
 *  
 *  
 *   |

### Annotator(InputStream inputStream) {#Annotator-java.io.InputStream-}
```
public Annotator(InputStream inputStream)
```


Initialise annotator class which accept document stream

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| inputStream | java.io.InputStream | Document stream

--------------------

 **Learn more** 

 *  
 *   |

### Annotator(InputStream inputStream, LoadOptions loadOptions) {#Annotator-java.io.InputStream-com.groupdocs.annotation.options.LoadOptions-}
```
public Annotator(InputStream inputStream, LoadOptions loadOptions)
```


Initialise annotator class which accept document stream

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| inputStream | java.io.InputStream | Document stream |
| loadOptions | [LoadOptions](../../com.groupdocs.annotation.options/loadoptions) | Load options

--------------------

 **Learn more** 

 *  
 *  
 *  
 *   |

### Annotator(InputStream inputStream, AnnotatorSettings settings) {#Annotator-java.io.InputStream-com.groupdocs.annotation.AnnotatorSettings-}
```
public Annotator(InputStream inputStream, AnnotatorSettings settings)
```


Initialise annotator class which accept document stream

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| inputStream | java.io.InputStream | Document stream |
| settings | [AnnotatorSettings](../../com.groupdocs.annotation/annotatorsettings) | Annotator settings

--------------------

 **Learn more** 

 *  
 *   |

### Annotator(InputStream inputStream, LoadOptions loadOptions, AnnotatorSettings settings) {#Annotator-java.io.InputStream-com.groupdocs.annotation.options.LoadOptions-com.groupdocs.annotation.AnnotatorSettings-}
```
public Annotator(InputStream inputStream, LoadOptions loadOptions, AnnotatorSettings settings)
```


Initialise annotator class which accept inputStream stream

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| inputStream | java.io.InputStream | Document stream |
| loadOptions | [LoadOptions](../../com.groupdocs.annotation.options/loadoptions) | Load options |
| settings | [AnnotatorSettings](../../com.groupdocs.annotation/annotatorsettings) | Annotator settings

--------------------

 **Learn more** 

 *  
 *  
 *  
 *   |

### getDocument() {#getDocument--}
```
public final Document getDocument()
```


Document

**Returns:**
[Document](../../com.groupdocs.annotation/document) - 
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

### save() {#save--}
```
public final void save()
```


Saves document after adding, updating or removing annotations.

--------------------

 **Learn more about saving annotated documents** 

 *  
 *  
 *  

### save(SaveOptions saveOptions) {#save-com.groupdocs.annotation.options.export.SaveOptions-}
```
public final void save(SaveOptions saveOptions)
```


Saves document after adding, updating or removing annotations.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| saveOptions | [SaveOptions](../../com.groupdocs.annotation.options.export/saveoptions) | The save options.

--------------------

 **Learn more about saving annotated documents** 

 *  
 *  
 *   |

### save(OutputStream document) {#save-java.io.OutputStream-}
```
public final void save(OutputStream document)
```


Saves document after adding, updating or removing annotations.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| document | java.io.OutputStream | The output stream.

--------------------

 **Learn more about saving annotated documents** 

 *  
 *  
 *   |

### save(String filePath) {#save-java.lang.String-}
```
public final void save(String filePath)
```


Saves document after adding, updating or removing annotations.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| filePath | java.lang.String | The output file path.

--------------------

 **Learn more about saving annotated documents** 

 *  
 *  
 *   |

### save(OutputStream outputStream, SaveOptions saveOptions) {#save-java.io.OutputStream-com.groupdocs.annotation.options.export.SaveOptions-}
```
public final void save(OutputStream outputStream, SaveOptions saveOptions)
```


Saves outputStream after adding, updating or removing annotations.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| outputStream | java.io.OutputStream | The output stream. |
| saveOptions | [SaveOptions](../../com.groupdocs.annotation.options.export/saveoptions) | The save options.

--------------------

 **Learn more about saving annotated documents** 

 *  
 *  
 *   |

### save(String filePath, SaveOptions saveOptions) {#save-java.lang.String-com.groupdocs.annotation.options.export.SaveOptions-}
```
public final void save(String filePath, SaveOptions saveOptions)
```


Saves document after adding, updating or removing annotations.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| filePath | java.lang.String | The output file path. |
| saveOptions | [SaveOptions](../../com.groupdocs.annotation.options.export/saveoptions) | The save options.

--------------------

 **Learn more about saving annotated documents** 

 *  
 *  
 *   |

### dispose() {#dispose--}
```
public final void dispose()
```


Dispose

### add(AnnotationBase annotation) {#add-com.groupdocs.annotation.models.annotationmodels.AnnotationBase-}
```
public final void add(AnnotationBase annotation)
```


Adds annotation to document

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| annotation | [AnnotationBase](../../com.groupdocs.annotation.models.annotationmodels/annotationbase) | The annotation to add.

--------------------

 **Learn more** 

 *   |

### add(List<AnnotationBase> annotations) {#add-java.util.List-com.groupdocs.annotation.models.annotationmodels.AnnotationBase--}
```
public final void add(List<AnnotationBase> annotations)
```


Adds collection of annotations to a document.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| annotations | java.util.List<com.groupdocs.annotation.models.annotationmodels.AnnotationBase> | The annotations list to add.

--------------------

 **Learn more** 

 *   |

### update(AnnotationBase newAnnotation) {#update-com.groupdocs.annotation.models.annotationmodels.AnnotationBase-}
```
public final void update(AnnotationBase newAnnotation)
```


Updates document annotation.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| newAnnotation | [AnnotationBase](../../com.groupdocs.annotation.models.annotationmodels/annotationbase) | The annotation to update (Id should be provided).

--------------------

 **Learn more** 

 *   |

### update(List<AnnotationBase> annotations) {#update-java.util.List-com.groupdocs.annotation.models.annotationmodels.AnnotationBase--}
```
public final void update(List<AnnotationBase> annotations)
```


Updates collection of document annotations.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| annotations | java.util.List<com.groupdocs.annotation.models.annotationmodels.AnnotationBase> | The annotations list that will be set.

--------------------

 **Learn more** 

 *   |

### remove(int annotationId) {#remove-int-}
```
public final void remove(int annotationId)
```


Removes annotation from document by Id.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| annotationId | int | The annotation's id that must be removed.

--------------------

 **Learn more** 

 *   |

### remove(AnnotationBase annotation) {#remove-com.groupdocs.annotation.models.annotationmodels.AnnotationBase-}
```
public final void remove(AnnotationBase annotation)
```


Removes annotation from document.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| annotation | [AnnotationBase](../../com.groupdocs.annotation.models.annotationmodels/annotationbase) | Annotation that must be removed.

--------------------

 **Learn more** 

 *   |

### remove(AnnotationBase[] annotationsToDelete) {#remove-com.groupdocs.annotation.models.annotationmodels.AnnotationBase...-}
```
public final void remove(AnnotationBase[] annotationsToDelete)
```


Removes collection of annotations from document by provided annotation ids.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| annotationsToDelete | [AnnotationBase\[\]](../../com.groupdocs.annotation.models.annotationmodels/annotationbase) | The annotation's id that must be removed.

--------------------

 **Learn more** 

 *   |

### remove(List<Integer> annotationsIdsToDelete) {#remove-java.util.List-java.lang.Integer--}
```
public final void remove(List<Integer> annotationsIdsToDelete)
```


Removes collection of annotations from document by provided annotation ids.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| annotationsIdsToDelete | java.util.List<java.lang.Integer> | The annotation's id that must be removed.

--------------------

 **Learn more** 

 *   |

### removeInternal(List<AnnotationBase> annotationsToDelete) {#removeInternal-java.util.List-com.groupdocs.annotation.models.annotationmodels.AnnotationBase--}
```
public final void removeInternal(List<AnnotationBase> annotationsToDelete)
```


Removes collection of annotations from document.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| annotationsToDelete | java.util.List<com.groupdocs.annotation.models.annotationmodels.AnnotationBase> | The annotations that must be removed.

--------------------

 **Learn more** 

 *   |

### get() {#get--}
```
public final List<AnnotationBase> get()
```


Gets collections of document annotations.

**Returns:**
java.util.List<com.groupdocs.annotation.models.annotationmodels.AnnotationBase> - The list of annotations.

--------------------

 **Learn more** 

 *  
### getVersionsList() {#getVersionsList--}
```
public final List<Object> getVersionsList()
```


Get versions.

**Returns:**
java.util.List<java.lang.Object> - The list of versions.
### getVersion(Object version) {#getVersion-java.lang.Object-}
```
public final List<AnnotationBase> getVersion(Object version)
```


Get annotations from versions.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| version | java.lang.Object | The version's Key of versions which you want to return |

**Returns:**
java.util.List<com.groupdocs.annotation.models.annotationmodels.AnnotationBase> - The list of annotations from specific versions. If null will return last.
### get(int type) {#get-int-}
```
public final List<AnnotationBase> get(int type)
```


Gets collection of document annotations by annotation type.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| type | int | The annotations type that must be returned.

--------------------

 **Learn more** 

 *   |

**Returns:**
java.util.List<com.groupdocs.annotation.models.annotationmodels.AnnotationBase> - The list of annotations by type.
### importAnnotationsFromDocument(String outputPath) {#importAnnotationsFromDocument-java.lang.String-}
```
public final void importAnnotationsFromDocument(String outputPath)
```


Import annotations from document to XML file.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| outputPath | java.lang.String | The output file path.

--------------------

 **Learn more** 

 *   |

### exportAnnotationsFromDocument(String filePath) {#exportAnnotationsFromDocument-java.lang.String-}
```
public final void exportAnnotationsFromDocument(String filePath)
```


Export annotations from XML document.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| filePath | java.lang.String | The input file path.

--------------------

 **Learn more** 

 *   |

### close() {#close--}
```
public void close()
```




