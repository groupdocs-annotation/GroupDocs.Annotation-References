---
title: Class RepeatingBlockWithOffset
second_title: GroupDocs.Annotation for .NET API Reference
description: GroupDocs.Annotation.Projects.Images.Models.RepeatingBlockWithOffset class. the representation of a repeating block of data with a certain offset in the byte array
type: docs
weight: 1220
url: /net/groupdocs.annotation.projects.images.models/repeatingblockwithoffset/
---
## RepeatingBlockWithOffset class

the representation of a repeating block of data with a certain offset in the byte array.

```csharp
public class RepeatingBlockWithOffset : BlockWithOffset
```

## Constructors

| Name | Description |
| --- | --- |
| [RepeatingBlockWithOffset](repeatingblockwithoffset/#constructor)() | Creates default instance of the RepeatingBlockWithOffset |
| [RepeatingBlockWithOffset](repeatingblockwithoffset/#constructor_1)(byte[], int, int, int) | Creates instance of the RepeatingBlockWithOffset with predefined values |

## Methods

| Name | Description |
| --- | --- |
| override [GetLength](../../groupdocs.annotation.projects.images.models/repeatingblockwithoffset/getlength/)() | Returns size of block |
| override [RestoreBytes](../../groupdocs.annotation.projects.images.models/repeatingblockwithoffset/restorebytes/)(byte[]) | Copies block bytes to given array. |

## Fields

| Name | Description |
| --- | --- |
| [Block](../../groupdocs.annotation.projects.images.models/blockwithoffset/block/) | Byte block |
| [Offset](../../groupdocs.annotation.projects.images.models/blockwithoffset/offset/) | Byte block reduction information |
| [_repeatingCount](../../groupdocs.annotation.projects.images.models/repeatingblockwithoffset/_repeatingcount/) | Number of repetitions of the data block |

### See Also

* class [BlockWithOffset](../blockwithoffset/)
* namespace [GroupDocs.Annotation.Projects.Images.Models](../../groupdocs.annotation.projects.images.models/)
* assembly [GroupDocs.Annotation](../../)


