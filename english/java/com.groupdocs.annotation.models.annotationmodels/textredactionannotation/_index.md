---
title: TextRedactionAnnotation
second_title: GroupDocs.Annotation for Java API Reference
description: Represents Text redaction annotation properties
type: docs
weight: 23
url: /java/com.groupdocs.annotation.models.annotationmodels/textredactionannotation/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.annotation.models.annotationmodels.AnnotationBase](../../com.groupdocs.annotation.models.annotationmodels/annotationbase)

**All Implemented Interfaces:**
[com.groupdocs.annotation.models.annotationmodels.interfaces.annotations.ITextRedactionAnnotation](../../com.groupdocs.annotation.models.annotationmodels.interfaces.annotations/itextredactionannotation)
```
public class TextRedactionAnnotation extends AnnotationBase implements ITextRedactionAnnotation
```

Represents Text redaction annotation properties
## Constructors

| Constructor | Description |
| --- | --- |
| [TextRedactionAnnotation()](#TextRedactionAnnotation--) | Initializes new instance of [TextRedactionAnnotation](../../com.groupdocs.annotation.models.annotationmodels/textredactionannotation) class. |
## Methods

| Method | Description |
| --- | --- |
| [getFontColor()](#getFontColor--) | Gets or sets annotation text font color |
| [setFontColor(Integer value)](#setFontColor-java.lang.Integer-) | Gets or sets annotation text font color |
| [getPoints()](#getPoints--) | Gets or sets collection of points that describe rectangles with text |
| [setPoints(List<Point> value)](#setPoints-java.util.List-com.groupdocs.annotation.models.Point--) | Gets or sets collection of points that describe rectangles with text |
| [equals(TextRedactionAnnotation other)](#equals-com.groupdocs.annotation.models.annotationmodels.TextRedactionAnnotation-) | Compares Text Redaction Annotations using IEquatable Equals method |
| [equals(Object o)](#equals-java.lang.Object-) | Compares Text Redaction Annotations using standard object Equals method |
| [hashCode()](#hashCode--) | Returns HashCode of Text Redaction Annotation |
| [deepClone()](#deepClone--) | Returns new Instance with same values |
| [toString()](#toString--) |  |
| [toString(ToStringStyle toStringStyle)](#toString-org.apache.commons.lang3.builder.ToStringStyle-) |  |
### TextRedactionAnnotation() {#TextRedactionAnnotation--}
```
public TextRedactionAnnotation()
```


Initializes new instance of [TextRedactionAnnotation](../../com.groupdocs.annotation.models.annotationmodels/textredactionannotation) class.

### getFontColor() {#getFontColor--}
```
public final Integer getFontColor()
```


Gets or sets annotation text font color

**Returns:**
java.lang.Integer - 
### setFontColor(Integer value) {#setFontColor-java.lang.Integer-}
```
public final void setFontColor(Integer value)
```


Gets or sets annotation text font color

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.Integer |  |

### getPoints() {#getPoints--}
```
public final List<Point> getPoints()
```


Gets or sets collection of points that describe rectangles with text

**Returns:**
java.util.List<com.groupdocs.annotation.models.Point> - 
### setPoints(List<Point> value) {#setPoints-java.util.List-com.groupdocs.annotation.models.Point--}
```
public final void setPoints(List<Point> value)
```


Gets or sets collection of points that describe rectangles with text

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.util.List<com.groupdocs.annotation.models.Point> |  |

### equals(TextRedactionAnnotation other) {#equals-com.groupdocs.annotation.models.annotationmodels.TextRedactionAnnotation-}
```
public final boolean equals(TextRedactionAnnotation other)
```


Compares Text Redaction Annotations using IEquatable Equals method

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| other | [TextRedactionAnnotation](../../com.groupdocs.annotation.models.annotationmodels/textredactionannotation) | The TextRedactionAnnotation object to compare with the current object |

**Returns:**
boolean
### equals(Object o) {#equals-java.lang.Object-}
```
public boolean equals(Object o)
```


Compares Text Redaction Annotations using standard object Equals method

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


Returns HashCode of Text Redaction Annotation

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
