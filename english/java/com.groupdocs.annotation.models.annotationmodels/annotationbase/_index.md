---
title: AnnotationBase
second_title: GroupDocs.Annotation for Java API Reference
description: Base class for all annotation types
type: docs
weight: 10
url: /java/com.groupdocs.annotation.models.annotationmodels/annotationbase/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable, java.lang.Cloneable, com.aspose.ms.System.IEquatable
```
public abstract class AnnotationBase implements System.ICloneable, Cloneable, System.IEquatable<AnnotationBase>
```

Base class for all annotation types
## Constructors

| Constructor | Description |
| --- | --- |
| [AnnotationBase()](#AnnotationBase--) |  |
## Fields

| Field | Description |
| --- | --- |
| [Counter](#Counter) |  |
## Methods

| Method | Description |
| --- | --- |
| [getId()](#getId--) | Gets or sets annotation unique identifier |
| [setId(int value)](#setId-int-) | Gets or sets annotation unique identifier |
| [getCreatedOn()](#getCreatedOn--) | Gets or sets annotation creation date |
| [setCreatedOn(Date value)](#setCreatedOn-java.util.Date-) | Gets or sets annotation creation date |
| [getMessage()](#getMessage--) | Gets or sets annotation message |
| [setMessage(String value)](#setMessage-java.lang.String-) | Gets or sets annotation message |
| [getPageNumber()](#getPageNumber--) | Gets or sets page number to be annotated |
| [setPageNumber(Integer value)](#setPageNumber-java.lang.Integer-) | Gets or sets page number to be annotated |
| [getReplies()](#getReplies--) | Represents annotation replies collection |
| [setReplies(List<Reply> value)](#setReplies-java.util.List-com.groupdocs.annotation.models.Reply--) | Represents annotation replies collection |
| [getStateBeforeAnnotation()](#getStateBeforeAnnotation--) | Text state before annotation |
| [setStateBeforeAnnotation(Object value)](#setStateBeforeAnnotation-java.lang.Object-) | Text state before annotation |
| [getType()](#getType--) | Gets or sets annotation type |
| [setType(int value)](#setType-int-) | Gets or sets annotation type |
| [getUser()](#getUser--) | Gets or sets annotation creator |
| [setUser(User value)](#setUser-com.groupdocs.annotation.models.User-) | Gets or sets annotation creator |
| [equals(AnnotationBase other)](#equals-com.groupdocs.annotation.models.annotationmodels.AnnotationBase-) | Compares Base Annotations using IEquatable Equals method |
| [equals(Object obj)](#equals-java.lang.Object-) | Compares Base Annotations using standard object Equals method |
| [hashCode()](#hashCode--) | Returns HashCode of AnnotationBase Message, PageNumber and Type Properties |
| [deepClone()](#deepClone--) | Returns new Instance with same values |
| [toString()](#toString--) |  |
| [toString(ToStringStyle toStringStyle)](#toString-org.apache.commons.lang3.builder.ToStringStyle-) |  |
### AnnotationBase() {#AnnotationBase--}
```
public AnnotationBase()
```


### Counter {#Counter}
```
public static int Counter
```


### getId() {#getId--}
```
public final int getId()
```


Gets or sets annotation unique identifier

**Returns:**
int - 
### setId(int value) {#setId-int-}
```
public final void setId(int value)
```


Gets or sets annotation unique identifier

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getCreatedOn() {#getCreatedOn--}
```
public final Date getCreatedOn()
```


Gets or sets annotation creation date

**Returns:**
java.util.Date - 
### setCreatedOn(Date value) {#setCreatedOn-java.util.Date-}
```
public final void setCreatedOn(Date value)
```


Gets or sets annotation creation date

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.util.Date |  |

### getMessage() {#getMessage--}
```
public final String getMessage()
```


Gets or sets annotation message

**Returns:**
java.lang.String - 
### setMessage(String value) {#setMessage-java.lang.String-}
```
public final void setMessage(String value)
```


Gets or sets annotation message

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getPageNumber() {#getPageNumber--}
```
public final Integer getPageNumber()
```


Gets or sets page number to be annotated

**Returns:**
java.lang.Integer - 
### setPageNumber(Integer value) {#setPageNumber-java.lang.Integer-}
```
public final void setPageNumber(Integer value)
```


Gets or sets page number to be annotated

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.Integer |  |

### getReplies() {#getReplies--}
```
public final List<Reply> getReplies()
```


Represents annotation replies collection

**Returns:**
java.util.List<com.groupdocs.annotation.models.Reply> - 
### setReplies(List<Reply> value) {#setReplies-java.util.List-com.groupdocs.annotation.models.Reply--}
```
public final void setReplies(List<Reply> value)
```


Represents annotation replies collection

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.util.List<com.groupdocs.annotation.models.Reply> |  |

### getStateBeforeAnnotation() {#getStateBeforeAnnotation--}
```
public final Object getStateBeforeAnnotation()
```


Text state before annotation

**Returns:**
java.lang.Object - 
### setStateBeforeAnnotation(Object value) {#setStateBeforeAnnotation-java.lang.Object-}
```
public final void setStateBeforeAnnotation(Object value)
```


Text state before annotation

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.Object |  |

### getType() {#getType--}
```
public final int getType()
```


Gets or sets annotation type

**Returns:**
int - 
### setType(int value) {#setType-int-}
```
public final void setType(int value)
```


Gets or sets annotation type

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getUser() {#getUser--}
```
public final User getUser()
```


Gets or sets annotation creator

**Returns:**
[User](../../com.groupdocs.annotation.models/user) - 
### setUser(User value) {#setUser-com.groupdocs.annotation.models.User-}
```
public final void setUser(User value)
```


Gets or sets annotation creator

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [User](../../com.groupdocs.annotation.models/user) |  |

### equals(AnnotationBase other) {#equals-com.groupdocs.annotation.models.annotationmodels.AnnotationBase-}
```
public final boolean equals(AnnotationBase other)
```


Compares Base Annotations using IEquatable Equals method

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| other | [AnnotationBase](../../com.groupdocs.annotation.models.annotationmodels/annotationbase) | The AnnotationBase object to compare with the current object |

**Returns:**
boolean - 
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Compares Base Annotations using standard object Equals method

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


Returns HashCode of AnnotationBase Message, PageNumber and Type Properties

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
