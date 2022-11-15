---
title: ImageAnnotation
second_title: .NET API Başvurusu için GroupDocs.Annotation
description: Görüntü açıklama özelliklerini temsil eder
type: docs
weight: 250
url: /tr/net/groupdocs.annotation.models.annotationmodels/imageannotation/
---
## ImageAnnotation class

Görüntü açıklama özelliklerini temsil eder

```csharp
public class ImageAnnotation : AnnotationBase, IAngle, IBox, IEquatable<ImageAnnotation>, IOpacity
```

## yapıcılar

| İsim | Tanım |
| --- | --- |
| [ImageAnnotation](imageannotation)() | Yeni örneğini başlatır[`ImageAnnotation`](../imageannotation) sınıf. |

## Özellikleri

| İsim | Tanım |
| --- | --- |
| [Angle](../../groupdocs.annotation.models.annotationmodels/imageannotation/angle) { get; set; } | Ek açıklama dönüş açısını alır veya ayarlar |
| [Box](../../groupdocs.annotation.models.annotationmodels/imageannotation/box) { get; set; } | Konum açıklamasını alır veya ayarlar |
| [CreatedOn](../../groupdocs.annotation.models.annotationmodels/annotationbase/createdon) { get; set; } | Ek açıklama oluşturma tarihini alır veya ayarlar |
| [Id](../../groupdocs.annotation.models.annotationmodels/annotationbase/id) { get; set; } | Ek açıklama benzersiz tanımlayıcısını alır veya ayarlar |
| [ImageExtension](../../groupdocs.annotation.models.annotationmodels/imageannotation/imageextension) { get; set; } | Görüntü verilerini alır veya ayarlar |
| [ImagePath](../../groupdocs.annotation.models.annotationmodels/imageannotation/imagepath) { get; set; } | Görüntü yolunu alır veya ayarlar |
| [Message](../../groupdocs.annotation.models.annotationmodels/annotationbase/message) { get; set; } | Açıklama mesajını alır veya ayarlar |
| [Opacity](../../groupdocs.annotation.models.annotationmodels/imageannotation/opacity) { get; set; } | Görüntü opaklığını alır veya ayarlar |
| [PageNumber](../../groupdocs.annotation.models.annotationmodels/annotationbase/pagenumber) { get; set; } | Ek açıklamalı sayfa numarasını alır veya ayarlar |
| [Replies](../../groupdocs.annotation.models.annotationmodels/annotationbase/replies) { get; set; } | Ek açıklama yanıtlarını temsil eder koleksiyon |
| [Type](../../groupdocs.annotation.models.annotationmodels/annotationbase/type) { get; set; } | Açıklama tipini alır veya ayarlar |
| [User](../../groupdocs.annotation.models.annotationmodels/annotationbase/user) { get; set; } | Ek açıklamayı alır veya ayarlar creator |
| [ZIndex](../../groupdocs.annotation.models.annotationmodels/imageannotation/zindex) { get; set; } | Z-endeksi alır veya ayarlar. Varsayılan değer 0 |

## yöntemler

| İsim | Tanım |
| --- | --- |
| override [Clone](../../groupdocs.annotation.models.annotationmodels/imageannotation/clone)() | Aynı değerlere sahip yeni Örnek döndürür |
| [Equals](../../groupdocs.annotation.models.annotationmodels/annotationbase/equals)(AnnotationBase) | IEquatable Equals yöntemini kullanarak Temel Açıklamaları karşılaştırır |
| [Equals](../../groupdocs.annotation.models.annotationmodels/imageannotation/equals#equals_1)(ImageAnnotation) | IEquatable Equals yöntemini kullanarak Görüntü Ek Açıklamalarını karşılaştırır |
| override [Equals](../../groupdocs.annotation.models.annotationmodels/imageannotation/equals#equals_2)(object) | Standart nesne Equals method kullanarak Görüntü Ek Açıklamalarını karşılaştırır |
| override [GetHashCode](../../groupdocs.annotation.models.annotationmodels/imageannotation/gethashcode)() | Görüntü Açıklamanın HashCode'unu döndürür |
| [GetImage](../../groupdocs.annotation.models.annotationmodels/imageannotation/getimage)() | Görüntü nesnesini alır |

### Notlar

**Daha fazla bilgi edin**

* Açıklama türleri ve PDF ve Microsoft Word belgelerine, Excel elektronik tablolarına ve PowerPoint Sunumlarına açıklama ekleme hakkında daha fazla bilgi: [.NET için GroupDocs.Annotation kullanarak belgelere açıklama ekleme](https://docs.groupdocs.com/display/annotationnet/Add+annotation+to+the+document)
* Çeşitli türdeki belgelere resim açıklamaları ekleme hakkında daha fazla bilgi: [C#'ta görüntü ek açıklamaları nasıl eklenir?](https://docs.groupdocs.com/display/annotationnet/Add+image+annotation)

### Ayrıca bakınız

* class [AnnotationBase](../annotationbase)
* interface [IAngle](../../groupdocs.annotation.models.annotationmodels.interfaces.properties/iangle)
* interface [IBox](../../groupdocs.annotation.models.annotationmodels.interfaces.properties/ibox)
* interface [IOpacity](../../groupdocs.annotation.models.annotationmodels.interfaces.properties/iopacity)
* ad alanı [GroupDocs.Annotation.Models.AnnotationModels](../../groupdocs.annotation.models.annotationmodels)
* toplantı [GroupDocs.Annotation](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Annotation.dll -->