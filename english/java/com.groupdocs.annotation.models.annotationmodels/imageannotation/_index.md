---
title: ImageAnnotation
second_title: GroupDocs.Annotation for Java API Reference
description: Represents image annotation properties
type: docs
weight: 16
url: /java/com.groupdocs.annotation.models.annotationmodels/imageannotation/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.annotation.models.annotationmodels.AnnotationBase](../../com.groupdocs.annotation.models.annotationmodels/annotationbase)

**All Implemented Interfaces:**
[com.groupdocs.annotation.models.annotationmodels.interfaces.annotations.IImageAnnotation](../../com.groupdocs.annotation.models.annotationmodels.interfaces.annotations/iimageannotation)
```
public class ImageAnnotation extends AnnotationBase implements IImageAnnotation
```

Represents image annotation properties

--------------------

 **Learn more** 

 *  
 *  
## Constructors

| Constructor | Description |
| --- | --- |
| [ImageAnnotation()](#ImageAnnotation--) | Initializes new instance of [ImageAnnotation](../../com.groupdocs.annotation.models.annotationmodels/imageannotation) class. |
## Methods

| Method | Description |
| --- | --- |
| [getBox()](#getBox--) | Gets or sets annotation position |
| [setBox(Rectangle value)](#setBox-com.groupdocs.annotation.models.Rectangle-) | Gets or sets annotation position |
| [getImagePath()](#getImagePath--) | Gets or sets image path |
| [setImagePath(String value)](#setImagePath-java.lang.String-) | Gets or sets image path |
| [getImageData()](#getImageData--) | Gets or sets image data |
| [setImageData(String value)](#setImageData-java.lang.String-) | Gets or sets image data |
| [getImageExtension()](#getImageExtension--) | Gets or sets image data |
| [setImageExtension(String value)](#setImageExtension-java.lang.String-) |  |
| [getOpacity()](#getOpacity--) | Gets or sets annotation opacity |
| [setOpacity(Double value)](#setOpacity-java.lang.Double-) | Gets or sets annotation opacity |
| [getAngle()](#getAngle--) | Gets or sets annotation rotation angle |
| [setAngle(Double value)](#setAngle-java.lang.Double-) | Gets or sets annotation rotation angle |
| [getZIndex()](#getZIndex--) | Gets or sets z-index. |
| [setZIndex(Integer value)](#setZIndex-java.lang.Integer-) | Gets or sets annotation pen color |
| [getImage()](#getImage--) | Gets image object |
| [equals(ImageAnnotation other)](#equals-com.groupdocs.annotation.models.annotationmodels.ImageAnnotation-) | Compares Image Annotations using IEquatable Equals method |
| [equals(Object o)](#equals-java.lang.Object-) | Compares Image Annotations using standard object Equals method |
| [hashCode()](#hashCode--) | Returns HashCode of Image Annotation |
| [deepClone()](#deepClone--) | Returns new Instance with same values |
| [toString()](#toString--) |  |
| [toString(ToStringStyle toStringStyle)](#toString-org.apache.commons.lang3.builder.ToStringStyle-) |  |
### ImageAnnotation() {#ImageAnnotation--}
```
public ImageAnnotation()
```


Initializes new instance of [ImageAnnotation](../../com.groupdocs.annotation.models.annotationmodels/imageannotation) class.

### getBox() {#getBox--}
```
public final Rectangle getBox()
```


Gets or sets annotation position

**Returns:**
[Rectangle](../../com.groupdocs.annotation.models/rectangle)
### setBox(Rectangle value) {#setBox-com.groupdocs.annotation.models.Rectangle-}
```
public final void setBox(Rectangle value)
```


Gets or sets annotation position

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Rectangle](../../com.groupdocs.annotation.models/rectangle) |  |

### getImagePath() {#getImagePath--}
```
public final String getImagePath()
```


Gets or sets image path

**Returns:**
java.lang.String - 
### setImagePath(String value) {#setImagePath-java.lang.String-}
```
public final void setImagePath(String value)
```


Gets or sets image path

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getImageData() {#getImageData--}
```
public final String getImageData()
```


Gets or sets image data

**Returns:**
java.lang.String - 
### setImageData(String value) {#setImageData-java.lang.String-}
```
public final void setImageData(String value)
```


Gets or sets image data

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getImageExtension() {#getImageExtension--}
```
public final String getImageExtension()
```


Gets or sets image data

**Returns:**
java.lang.String - 
### setImageExtension(String value) {#setImageExtension-java.lang.String-}
```
public final void setImageExtension(String value)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getOpacity() {#getOpacity--}
```
public final Double getOpacity()
```


Gets or sets annotation opacity

**Returns:**
java.lang.Double - 
### setOpacity(Double value) {#setOpacity-java.lang.Double-}
```
public final void setOpacity(Double value)
```


Gets or sets annotation opacity

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.Double |  |

### getAngle() {#getAngle--}
```
public final Double getAngle()
```


Gets or sets annotation rotation angle

**Returns:**
java.lang.Double
### setAngle(Double value) {#setAngle-java.lang.Double-}
```
public final void setAngle(Double value)
```


Gets or sets annotation rotation angle

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.Double |  |

### getZIndex() {#getZIndex--}
```
public final Integer getZIndex()
```


Gets or sets z-index. Default value is 0

The  **z-index**  property specifies the stack order of an element.

**Returns:**
java.lang.Integer - 
### setZIndex(Integer value) {#setZIndex-java.lang.Integer-}
```
public final void setZIndex(Integer value)
```


Gets or sets annotation pen color

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.Integer |  |

### getImage() {#getImage--}
```
public final System.Drawing.Image getImage()
```


Gets image object

**Returns:**
com.aspose.ms.System.Drawing.Image - 
### equals(ImageAnnotation other) {#equals-com.groupdocs.annotation.models.annotationmodels.ImageAnnotation-}
```
public final boolean equals(ImageAnnotation other)
```


Compares Image Annotations using IEquatable Equals method

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| other | [ImageAnnotation](../../com.groupdocs.annotation.models.annotationmodels/imageannotation) | The ImageAnnotation object to compare with the current object |

**Returns:**
boolean - 
### equals(Object o) {#equals-java.lang.Object-}
```
public boolean equals(Object o)
```


Compares Image Annotations using standard object Equals method

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| o | java.lang.Object | The object to compare with the current object |

**Returns:**
boolean
### hashCode() {#hashCode--}
```
public int hashCode()
```


Returns HashCode of Image Annotation

**Returns:**
int
### deepClone() {#deepClone--}
```
public Object deepClone()
```


Returns new Instance with same values

**Returns:**
java.lang.Object - 
### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### toString(ToStringStyle toStringStyle) {#toString-org.apache.commons.lang3.builder.ToStringStyle-}
```
public String toString(ToStringStyle toStringStyle)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| toStringStyle | org.apache.commons.lang3.builder.ToStringStyle |  |

**Returns:**
java.lang.String
