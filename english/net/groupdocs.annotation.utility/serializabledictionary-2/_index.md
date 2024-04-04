---
title: Class SerializableDictionaryTKeyTValue
second_title: GroupDocs.Annotation for .NET API Reference
description: GroupDocs.Annotation.Utility.SerializableDictionary2TKeyTValue class. Represents a serializable custom dictionary collection of keys and values
type: docs
weight: 1300
url: /net/groupdocs.annotation.utility/serializabledictionary-2/
---
## SerializableDictionary&lt;TKey,TValue&gt; class

Represents a serializable custom dictionary collection of keys and values.

```csharp
public class SerializableDictionary<TKey, TValue> : Dictionary<TKey, TValue>, IXmlSerializable
```

| Parameter | Description |
| --- | --- |
| TKey | The type of the keys in the dictionary. |
| TValue | The type of the values in the dictionary. |

## Constructors

| Name | Description |
| --- | --- |
| [SerializableDictionary](serializabledictionary/)() | Initializes a new instance of the SerializableDictionary class that is empty, has the default initial capacity, and uses the default equality comparer for the key type. |

## Methods

| Name | Description |
| --- | --- |
| [GetObjectData](../../groupdocs.annotation.utility/serializabledictionary-2/getobjectdata/#getobjectdata)(SerializationInfo, StreamingContext) | Serialize dictionary as a list of key-value pairs |
| [GetSchema](../../groupdocs.annotation.utility/serializabledictionary-2/getschema/)() | Returns XML Scema of the collection |
| [ReadXml](../../groupdocs.annotation.utility/serializabledictionary-2/readxml/)(XmlReader) | Reads collection data from the given reader XmlReader |
| [WriteXml](../../groupdocs.annotation.utility/serializabledictionary-2/writexml/)(XmlWriter) | Writes collection data to given writer XmlWriter |

### See Also

* namespace [GroupDocs.Annotation.Utility](../../groupdocs.annotation.utility/)
* assembly [GroupDocs.Annotation](../../)


