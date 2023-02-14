---
title: Rectangle
second_title: GroupDocs.Annotation for Java API Reference
description: Represents rectangle.
type: docs
weight: 13
url: /java/com.groupdocs.annotation.models/rectangle/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.lang.Struct
```
public class Rectangle extends Struct<Rectangle>
```

Represents rectangle.
## Constructors

| Constructor | Description |
| --- | --- |
| [Rectangle()](#Rectangle--) |  |
| [Rectangle(float x, float y, float width, float height)](#Rectangle-float-float-float-float-) | Initializes a new instance of the [Rectangle](../../com.groupdocs.annotation.models/rectangle) struct. |
## Methods

| Method | Description |
| --- | --- |
| [opEquality(Rectangle left, Rectangle right)](#opEquality-com.groupdocs.annotation.models.Rectangle-com.groupdocs.annotation.models.Rectangle-) | Compares two Rectangle objects. |
| [opInequality(Rectangle left, Rectangle right)](#opInequality-com.groupdocs.annotation.models.Rectangle-com.groupdocs.annotation.models.Rectangle-) | Compares two Rectangle objects. |
| [equals(Rectangle obj1, Rectangle obj2)](#equals-com.groupdocs.annotation.models.Rectangle-com.groupdocs.annotation.models.Rectangle-) |  |
| [getX()](#getX--) | Gets or sets the x. |
| [setX(float value)](#setX-float-) | Gets or sets the x. |
| [getY()](#getY--) | Gets or sets the y. |
| [setY(float value)](#setY-float-) | Gets or sets the y. |
| [getWidth()](#getWidth--) | Gets or sets the width. |
| [setWidth(float value)](#setWidth-float-) | Gets or sets the width. |
| [getHeight()](#getHeight--) | Gets or sets the height. |
| [setHeight(float value)](#setHeight-float-) | Gets or sets the height. |
| [equals(Object obj)](#equals-java.lang.Object-) | Determines whether the specified rectangle is equal to the current rectangle. |
| [hashCode()](#hashCode--) | Serves as the default hash function. |
| [CloneTo(Rectangle that)](#CloneTo-com.groupdocs.annotation.models.Rectangle-) |  |
| [Clone()](#Clone--) |  |
| [clone()](#clone--) |  |
| [toString()](#toString--) |  |
### Rectangle() {#Rectangle--}
```
public Rectangle()
```


### Rectangle(float x, float y, float width, float height) {#Rectangle-float-float-float-float-}
```
public Rectangle(float x, float y, float width, float height)
```


Initializes a new instance of the [Rectangle](../../com.groupdocs.annotation.models/rectangle) struct.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| x | float | The x. |
| y | float | The y. |
| width | float | The width. |
| height | float | The height. |

### opEquality(Rectangle left, Rectangle right) {#opEquality-com.groupdocs.annotation.models.Rectangle-com.groupdocs.annotation.models.Rectangle-}
```
public static boolean opEquality(Rectangle left, Rectangle right)
```


Compares two Rectangle objects. The result specifies whether the values of the Rectangle.X, Rectangle.Y, Rectangle.Width and Rectangle.Height properties of the two Rectangle objects are equal.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| left | [Rectangle](../../com.groupdocs.annotation.models/rectangle) | A Rectangle to compare. |
| right | [Rectangle](../../com.groupdocs.annotation.models/rectangle) | A Rectangle to compare. |

**Returns:**
boolean - true if the Rectangle.X, Rectangle.Y, Rectangle.Width and Rectangle.Height values of left and right are equal; otherwise, false.
### opInequality(Rectangle left, Rectangle right) {#opInequality-com.groupdocs.annotation.models.Rectangle-com.groupdocs.annotation.models.Rectangle-}
```
public static boolean opInequality(Rectangle left, Rectangle right)
```


Compares two Rectangle objects. The result specifies whether the values of the Rectangle.X, Rectangle.Y, Rectangle.Width and Rectangle.Height properties of the two Rectangle objects are not equal.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| left | [Rectangle](../../com.groupdocs.annotation.models/rectangle) | A Rectangle to compare. |
| right | [Rectangle](../../com.groupdocs.annotation.models/rectangle) | A Rectangle to compare. |

**Returns:**
boolean - true if the Rectangle.X, Rectangle.Y, Rectangle.Width and Rectangle.Height values of left and right are not equal; otherwise, false.
### equals(Rectangle obj1, Rectangle obj2) {#equals-com.groupdocs.annotation.models.Rectangle-com.groupdocs.annotation.models.Rectangle-}
```
public static boolean equals(Rectangle obj1, Rectangle obj2)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| obj1 | [Rectangle](../../com.groupdocs.annotation.models/rectangle) |  |
| obj2 | [Rectangle](../../com.groupdocs.annotation.models/rectangle) |  |

**Returns:**
boolean
### getX() {#getX--}
```
public final float getX()
```


Gets or sets the x.

Value: The x.

**Returns:**
float - 
### setX(float value) {#setX-float-}
```
public final void setX(float value)
```


Gets or sets the x.

Value: The x.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getY() {#getY--}
```
public final float getY()
```


Gets or sets the y.

Value: The y.

**Returns:**
float - 
### setY(float value) {#setY-float-}
```
public final void setY(float value)
```


Gets or sets the y.

Value: The y.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getWidth() {#getWidth--}
```
public final float getWidth()
```


Gets or sets the width.

Value: The width.

**Returns:**
float - 
### setWidth(float value) {#setWidth-float-}
```
public final void setWidth(float value)
```


Gets or sets the width.

Value: The width.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getHeight() {#getHeight--}
```
public final float getHeight()
```


Gets or sets the height.

Value: The height.

**Returns:**
float - 
### setHeight(float value) {#setHeight-float-}
```
public final void setHeight(float value)
```


Gets or sets the height.

Value: The height.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Determines whether the specified rectangle is equal to the current rectangle.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| obj | java.lang.Object | The rectangle to compare with the current rectangle. |

**Returns:**
boolean -   if the specified rectangle is equal to the current rectangle; otherwise,  .
### hashCode() {#hashCode--}
```
public int hashCode()
```


Serves as the default hash function.

**Returns:**
int - A hash code for the current rectangle.
### CloneTo(Rectangle that) {#CloneTo-com.groupdocs.annotation.models.Rectangle-}
```
public void CloneTo(Rectangle that)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| that | [Rectangle](../../com.groupdocs.annotation.models/rectangle) |  |

### Clone() {#Clone--}
```
public Rectangle Clone()
```




**Returns:**
[Rectangle](../../com.groupdocs.annotation.models/rectangle)
### clone() {#clone--}
```
public Object clone()
```




**Returns:**
java.lang.Object
### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
