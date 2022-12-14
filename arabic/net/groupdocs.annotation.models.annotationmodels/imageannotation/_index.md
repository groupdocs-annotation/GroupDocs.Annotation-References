---
title: ImageAnnotation
second_title: GroupDocs.Annotation for .NET API Reference
description: يمثل خصائص التعليق التوضيحي للصورة
type: docs
weight: 250
url: /ar/net/groupdocs.annotation.models.annotationmodels/imageannotation/
---
## ImageAnnotation class

يمثل خصائص التعليق التوضيحي للصورة

```csharp
public class ImageAnnotation : AnnotationBase, IAngle, IBox, IEquatable<ImageAnnotation>, IOpacity
```

## المنشئون

| اسم | وصف |
| --- | --- |
| [ImageAnnotation](imageannotation)() | تهيئة مثيل جديد لـ[`ImageAnnotation`](../imageannotation) فئة . |

## الخصائص

| اسم | وصف |
| --- | --- |
| [Angle](../../groupdocs.annotation.models.annotationmodels/imageannotation/angle) { get; set; } | الحصول على زاوية تدوير التعليق التوضيحي أو تعيينها |
| [Box](../../groupdocs.annotation.models.annotationmodels/imageannotation/box) { get; set; } | الحصول على أو تعيين موضع التعليق التوضيحي |
| [CreatedOn](../../groupdocs.annotation.models.annotationmodels/annotationbase/createdon) { get; set; } | الحصول على تاريخ إنشاء التعليق التوضيحي أو تعيينه |
| [Id](../../groupdocs.annotation.models.annotationmodels/annotationbase/id) { get; set; } | الحصول على أو تعيين المعرف الفريد للتعليق التوضيحي |
| [ImageExtension](../../groupdocs.annotation.models.annotationmodels/imageannotation/imageextension) { get; set; } | الحصول على أو تعيين بيانات الصورة |
| [ImagePath](../../groupdocs.annotation.models.annotationmodels/imageannotation/imagepath) { get; set; } | الحصول على مسار الصورة أو تعيينه |
| [Message](../../groupdocs.annotation.models.annotationmodels/annotationbase/message) { get; set; } | الحصول على رسالة التعليق التوضيحي أو تعيينها |
| [Opacity](../../groupdocs.annotation.models.annotationmodels/imageannotation/opacity) { get; set; } | الحصول على أو تعيين عتامة الصورة |
| [PageNumber](../../groupdocs.annotation.models.annotationmodels/annotationbase/pagenumber) { get; set; } | الحصول على رقم الصفحة أو تعيينه ليتم التعليق عليه |
| [Replies](../../groupdocs.annotation.models.annotationmodels/annotationbase/replies) { get; set; } | يمثل مجموعة ردود التعليقات التوضيحية |
| [Type](../../groupdocs.annotation.models.annotationmodels/annotationbase/type) { get; set; } | الحصول على نوع التعليق التوضيحي أو تعيينه |
| [User](../../groupdocs.annotation.models.annotationmodels/annotationbase/user) { get; set; } | الحصول على أو تعيين منشئ التعليقات التوضيحية |
| [ZIndex](../../groupdocs.annotation.models.annotationmodels/imageannotation/zindex) { get; set; } | الحصول على الفهرس z أو تعيينه. القيمة الافتراضية هي 0 |

## طُرق

| اسم | وصف |
| --- | --- |
| override [Clone](../../groupdocs.annotation.models.annotationmodels/imageannotation/clone)() | إرجاع مثيل جديد بنفس القيم |
| [Equals](../../groupdocs.annotation.models.annotationmodels/annotationbase/equals)(AnnotationBase) | مقارنة التعليقات التوضيحية الأساسية باستخدام طريقة IEquatable Equals |
| [Equals](../../groupdocs.annotation.models.annotationmodels/imageannotation/equals#equals_1)(ImageAnnotation) | مقارنة التعليقات التوضيحية للصور باستخدام طريقة IEquatable Equals |
| override [Equals](../../groupdocs.annotation.models.annotationmodels/imageannotation/equals#equals_2)(object) | مقارنة التعليقات التوضيحية للصور باستخدام كائن قياسي يساوي طريقة |
| override [GetHashCode](../../groupdocs.annotation.models.annotationmodels/imageannotation/gethashcode)() | إرجاع HashCode للتعليق التوضيحي للصورة |
| [GetImage](../../groupdocs.annotation.models.annotationmodels/imageannotation/getimage)() | الحصول على كائن الصورة |

### ملاحظات

**يتعلم أكثر**

* المزيد حول أنواع التعليقات التوضيحية والتعليقات التوضيحية على مستندات PDF و Microsoft Word وجداول بيانات Excel وعروض PowerPoint التقديمية: [كيفية إضافة تعليق توضيحي على المستندات باستخدام GroupDocs.Annotation for .NET](https://docs.groupdocs.com/display/annotationnet/Add+annotation+to+the+document)
* المزيد حول إضافة التعليقات التوضيحية بالصور إلى المستندات من مختلف الأنواع: [كيفية إضافة التعليقات التوضيحية للصور في C #](https://docs.groupdocs.com/display/annotationnet/Add+image+annotation)

### أنظر أيضا

* class [AnnotationBase](../annotationbase)
* interface [IAngle](../../groupdocs.annotation.models.annotationmodels.interfaces.properties/iangle)
* interface [IBox](../../groupdocs.annotation.models.annotationmodels.interfaces.properties/ibox)
* interface [IOpacity](../../groupdocs.annotation.models.annotationmodels.interfaces.properties/iopacity)
* مساحة الاسم [GroupDocs.Annotation.Models.AnnotationModels](../../groupdocs.annotation.models.annotationmodels)
* المجسم [GroupDocs.Annotation](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Annotation.dll -->
