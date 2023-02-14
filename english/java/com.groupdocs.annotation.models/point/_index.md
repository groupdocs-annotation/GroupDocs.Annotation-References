---
title: Point
second_title: GroupDocs.Annotation for Java API Reference
description: Represents point.
type: docs
weight: 12
url: /java/com.groupdocs.annotation.models/point/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.lang.Struct
```
public class Point extends Struct<Point>
```

Represents point.
## Constructors

| Constructor | Description |
| --- | --- |
| [Point()](#Point--) |  |
| [Point(float x, float y)](#Point-float-float-) | Initializes a new instance of the [Point](../../com.groupdocs.annotation.models/point) struct. |
## Methods

| Method | Description |
| --- | --- |
| [isPointCollectionsEqual(List<Point> points1, List<Point> points2)](#isPointCollectionsEqual-java.util.List-com.groupdocs.annotation.models.Point--java.util.List-com.groupdocs.annotation.models.Point--) |  |
| [op_Equality(Point left, Point right)](#op-Equality-com.groupdocs.annotation.models.Point-com.groupdocs.annotation.models.Point-) | Compares two Point objects. |
| [op_Inequality(Point left, Point right)](#op-Inequality-com.groupdocs.annotation.models.Point-com.groupdocs.annotation.models.Point-) | Compares two Point objects. |
| [equals(Point obj1, Point obj2)](#equals-com.groupdocs.annotation.models.Point-com.groupdocs.annotation.models.Point-) |  |
| [getX()](#getX--) | Gets or sets the x. |
| [setX(float value)](#setX-float-) | Gets or sets the x. |
| [getY()](#getY--) | Gets or sets the y. |
| [setY(float value)](#setY-float-) | Gets or sets the y. |
| [equals(Object obj)](#equals-java.lang.Object-) | Determines whether the specified point is equal to the current point. |
| [hashCode()](#hashCode--) | Serves as the default hash function. |
| [CloneTo(Point that)](#CloneTo-com.groupdocs.annotation.models.Point-) |  |
| [Clone()](#Clone--) |  |
| [clone()](#clone--) |  |
| [toString()](#toString--) |  |
### Point() {#Point--}
```
public Point()
```


### Point(float x, float y) {#Point-float-float-}
```
public Point(float x, float y)
```


Initializes a new instance of the [Point](../../com.groupdocs.annotation.models/point) struct.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| x | float | The x. |
| y | float | The y. |

### isPointCollectionsEqual(List<Point> points1, List<Point> points2) {#isPointCollectionsEqual-java.util.List-com.groupdocs.annotation.models.Point--java.util.List-com.groupdocs.annotation.models.Point--}
```
public static boolean isPointCollectionsEqual(List<Point> points1, List<Point> points2)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| points1 | java.util.List<com.groupdocs.annotation.models.Point> |  |
| points2 | java.util.List<com.groupdocs.annotation.models.Point> |  |

**Returns:**
boolean
### op_Equality(Point left, Point right) {#op-Equality-com.groupdocs.annotation.models.Point-com.groupdocs.annotation.models.Point-}
```
public static boolean op_Equality(Point left, Point right)
```


Compares two Point objects. The result specifies whether the values of the Point.X and Point.Y properties of the two Point objects are equal.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| left | [Point](../../com.groupdocs.annotation.models/point) | A Point to compare. |
| right | [Point](../../com.groupdocs.annotation.models/point) | A Point to compare. |

**Returns:**
boolean - true if the Point.X and Point.Y values of left and right are equal; otherwise, false.
### op_Inequality(Point left, Point right) {#op-Inequality-com.groupdocs.annotation.models.Point-com.groupdocs.annotation.models.Point-}
```
public static boolean op_Inequality(Point left, Point right)
```


Compares two Point objects. The result specifies whether the values of the Point.X and Point.Y properties of the two Point objects are not equal.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| left | [Point](../../com.groupdocs.annotation.models/point) | A Point to compare. |
| right | [Point](../../com.groupdocs.annotation.models/point) | A Point to compare. |

**Returns:**
boolean - true if the Point.X and Point.Y values of left and right are not equal; otherwise, false.
### equals(Point obj1, Point obj2) {#equals-com.groupdocs.annotation.models.Point-com.groupdocs.annotation.models.Point-}
```
public static boolean equals(Point obj1, Point obj2)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| obj1 | [Point](../../com.groupdocs.annotation.models/point) |  |
| obj2 | [Point](../../com.groupdocs.annotation.models/point) |  |

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

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Determines whether the specified point is equal to the current point.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| obj | java.lang.Object | The point to compare with the current point. |

**Returns:**
boolean -   if the specified point is equal to the current point; otherwise,  .
### hashCode() {#hashCode--}
```
public int hashCode()
```


Serves as the default hash function.

**Returns:**
int - A hash code for the current point.
### CloneTo(Point that) {#CloneTo-com.groupdocs.annotation.models.Point-}
```
public void CloneTo(Point that)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| that | [Point](../../com.groupdocs.annotation.models/point) |  |

### Clone() {#Clone--}
```
public Point Clone()
```




**Returns:**
[Point](../../com.groupdocs.annotation.models/point)
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
