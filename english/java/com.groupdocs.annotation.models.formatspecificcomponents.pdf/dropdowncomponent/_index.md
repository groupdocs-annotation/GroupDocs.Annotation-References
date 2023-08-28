---
title: DropdownComponent
second_title: GroupDocs.Annotation for Java API Reference
description: Represents dropdown component properties
type: docs
weight: 12
url: /java/com.groupdocs.annotation.models.formatspecificcomponents.pdf/dropdowncomponent/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.annotation.models.annotationmodels.AnnotationBase](../../com.groupdocs.annotation.models.annotationmodels/annotationbase)

**All Implemented Interfaces:**
[com.groupdocs.annotation.models.formatspecificcomponents.pdf.interfaces.IDropdownComponent](../../com.groupdocs.annotation.models.formatspecificcomponents.pdf.interfaces/idropdowncomponent)
```
public class DropdownComponent extends AnnotationBase implements IDropdownComponent
```

Represents dropdown component properties

--------------------

 **Learn more** 

 *  
 *  
## Constructors

| Constructor | Description |
| --- | --- |
| [DropdownComponent()](#DropdownComponent--) | Initializes new instance of [CheckBoxComponent](../../com.groupdocs.annotation.models.formatspecificcomponents.pdf/checkboxcomponent) class. |
## Methods

| Method | Description |
| --- | --- |
| [getOptions()](#getOptions--) | List of options (drop down items) to be shown when component is clicked |
| [setOptions(List<String> value)](#setOptions-java.util.List-java.lang.String--) | List of options (drop down items) to be shown when component is clicked |
| [getSelectedOption()](#getSelectedOption--) | Number of option to be selected by default |
| [setSelectedOption(Integer value)](#setSelectedOption-java.lang.Integer-) | Number of option to be selected by default |
| [getPlaceholder()](#getPlaceholder--) | Text to shown when no options has been selected yet |
| [setPlaceholder(String value)](#setPlaceholder-java.lang.String-) | Text to shown when no options has been selected yet |
| [getBox()](#getBox--) | Gets or sets component position |
| [setBox(Rectangle value)](#setBox-com.groupdocs.annotation.models.Rectangle-) | Gets or sets component position |
| [getPenColor()](#getPenColor--) | Gets or sets component pen color |
| [setPenColor(Integer value)](#setPenColor-java.lang.Integer-) | Gets or sets component pen color |
| [getPenStyle()](#getPenStyle--) | Gets or sets component pen style |
| [setPenStyle(Byte value)](#setPenStyle-java.lang.Byte-) | Gets or sets component pen style |
| [getPenWidth()](#getPenWidth--) | Gets or sets component pen width |
| [setPenWidth(Byte value)](#setPenWidth-java.lang.Byte-) | Gets or sets component pen width |
| [equals(DropdownComponent other)](#equals-com.groupdocs.annotation.models.formatspecificcomponents.pdf.DropdownComponent-) | Compares Dropdown component using IEquatable Equals method |
| [equals(Object obj)](#equals-java.lang.Object-) | Compares Dropdown Components using standard object Equals method |
| [hashCode()](#hashCode--) | Returns HashCode of Dropdown Component |
| [deepClone()](#deepClone--) | Returns new Instance with same values |
| [toString()](#toString--) |  |
| [toString(ToStringStyle toStringStyle)](#toString-org.apache.commons.lang3.builder.ToStringStyle-) |  |
### DropdownComponent() {#DropdownComponent--}
```
public DropdownComponent()
```


Initializes new instance of [CheckBoxComponent](../../com.groupdocs.annotation.models.formatspecificcomponents.pdf/checkboxcomponent) class.

### getOptions() {#getOptions--}
```
public final List<String> getOptions()
```


List of options (drop down items) to be shown when component is clicked

**Returns:**
java.util.List<java.lang.String> - 
### setOptions(List<String> value) {#setOptions-java.util.List-java.lang.String--}
```
public final void setOptions(List<String> value)
```


List of options (drop down items) to be shown when component is clicked

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.util.List<java.lang.String> |  |

### getSelectedOption() {#getSelectedOption--}
```
public final Integer getSelectedOption()
```


Number of option to be selected by default

**Returns:**
java.lang.Integer
### setSelectedOption(Integer value) {#setSelectedOption-java.lang.Integer-}
```
public final void setSelectedOption(Integer value)
```


Number of option to be selected by default

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.Integer |  |

### getPlaceholder() {#getPlaceholder--}
```
public final String getPlaceholder()
```


Text to shown when no options has been selected yet

**Returns:**
java.lang.String
### setPlaceholder(String value) {#setPlaceholder-java.lang.String-}
```
public final void setPlaceholder(String value)
```


Text to shown when no options has been selected yet

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getBox() {#getBox--}
```
public final Rectangle getBox()
```


Gets or sets component position

**Returns:**
[Rectangle](../../com.groupdocs.annotation.models/rectangle)
### setBox(Rectangle value) {#setBox-com.groupdocs.annotation.models.Rectangle-}
```
public final void setBox(Rectangle value)
```


Gets or sets component position

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Rectangle](../../com.groupdocs.annotation.models/rectangle) |  |

### getPenColor() {#getPenColor--}
```
public final Integer getPenColor()
```


Gets or sets component pen color

**Returns:**
java.lang.Integer
### setPenColor(Integer value) {#setPenColor-java.lang.Integer-}
```
public final void setPenColor(Integer value)
```


Gets or sets component pen color

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.Integer |  |

### getPenStyle() {#getPenStyle--}
```
public final Byte getPenStyle()
```


Gets or sets component pen style

**Returns:**
java.lang.Byte
### setPenStyle(Byte value) {#setPenStyle-java.lang.Byte-}
```
public final void setPenStyle(Byte value)
```


Gets or sets component pen style

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.Byte |  |

### getPenWidth() {#getPenWidth--}
```
public final Byte getPenWidth()
```


Gets or sets component pen width

**Returns:**
java.lang.Byte
### setPenWidth(Byte value) {#setPenWidth-java.lang.Byte-}
```
public final void setPenWidth(Byte value)
```


Gets or sets component pen width

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.Byte |  |

### equals(DropdownComponent other) {#equals-com.groupdocs.annotation.models.formatspecificcomponents.pdf.DropdownComponent-}
```
public final boolean equals(DropdownComponent other)
```


Compares Dropdown component using IEquatable Equals method

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| other | [DropdownComponent](../../com.groupdocs.annotation.models.formatspecificcomponents.pdf/dropdowncomponent) | The DropdownComponent object to compare with the current object |

**Returns:**
boolean - 
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Compares Dropdown Components using standard object Equals method

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| obj | java.lang.Object | The object to compare with the current object |

**Returns:**
boolean
### hashCode() {#hashCode--}
```
public int hashCode()
```


Returns HashCode of Dropdown Component

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
