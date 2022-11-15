---
title: WatermarkAnnotation
second_title: GroupDocs.Annotation for .NET API Reference
description: يمثل خصائص التعليقات التوضيحية للعلامة المائية
type: docs
weight: 740
url: /ar/net/groupdocs.annotation.models.annotationmodels/watermarkannotation/
---
## WatermarkAnnotation class

يمثل خصائص التعليقات التوضيحية للعلامة المائية

```csharp
public class WatermarkAnnotation : AnnotationBase, IEquatable<WatermarkAnnotation>, 
    IWatermarkAnnotation
```

## المنشئون

| اسم | وصف |
| --- | --- |
| [WatermarkAnnotation](watermarkannotation)() | تهيئة مثيل جديد لـ[`WatermarkAnnotation`](../watermarkannotation) فئة . |

## الخصائص

| اسم | وصف |
| --- | --- |
| [Angle](../../groupdocs.annotation.models.annotationmodels/watermarkannotation/angle) { get; set; } | الحصول على أو تعيين زاوية تدوير العلامة المائية |
| [AutoScale](../../groupdocs.annotation.models.annotationmodels/watermarkannotation/autoscale) { get; set; } | يعين مقياس تلقائي للعلامة المائية |
| [Box](../../groupdocs.annotation.models.annotationmodels/watermarkannotation/box) { get; set; } | الحصول على أو تعيين موضع التعليق التوضيحي |
| [CreatedOn](../../groupdocs.annotation.models.annotationmodels/annotationbase/createdon) { get; set; } | الحصول على تاريخ إنشاء التعليق التوضيحي أو تعيينه |
| [FontColor](../../groupdocs.annotation.models.annotationmodels/watermarkannotation/fontcolor) { get; set; } | الحصول على أو تعيين خط نص العلامة المائية color |
| [FontFamily](../../groupdocs.annotation.models.annotationmodels/watermarkannotation/fontfamily) { get; set; } | الحصول على أو تعيين عائلة خط نص العلامة المائية |
| [FontSize](../../groupdocs.annotation.models.annotationmodels/watermarkannotation/fontsize) { get; set; } | الحصول على أو تعيين حجم خط نص العلامة المائية |
| [HorizontalAlignment](../../groupdocs.annotation.models.annotationmodels/watermarkannotation/horizontalalignment) { get; set; } | الحصول على أو تعيين المحاذاة الأفقية للعلامة المائية في document |
| [Id](../../groupdocs.annotation.models.annotationmodels/annotationbase/id) { get; set; } | الحصول على أو تعيين المعرف الفريد للتعليق التوضيحي |
| [Message](../../groupdocs.annotation.models.annotationmodels/annotationbase/message) { get; set; } | الحصول على رسالة التعليق التوضيحي أو تعيينها |
| [Opacity](../../groupdocs.annotation.models.annotationmodels/watermarkannotation/opacity) { get; set; } | الحصول على أو تعيين عتامة العلامة المائية |
| [PageNumber](../../groupdocs.annotation.models.annotationmodels/annotationbase/pagenumber) { get; set; } | الحصول على رقم الصفحة أو تعيينه ليتم التعليق عليه |
| [Replies](../../groupdocs.annotation.models.annotationmodels/annotationbase/replies) { get; set; } | يمثل مجموعة ردود التعليقات التوضيحية |
| [Text](../../groupdocs.annotation.models.annotationmodels/watermarkannotation/text) { get; set; } | الحصول على نص العلامة المائية أو تعيينه |
| [Type](../../groupdocs.annotation.models.annotationmodels/annotationbase/type) { get; set; } | الحصول على نوع التعليق التوضيحي أو تعيينه |
| [User](../../groupdocs.annotation.models.annotationmodels/annotationbase/user) { get; set; } | الحصول على أو تعيين منشئ التعليقات التوضيحية |
| [VerticalAlignment](../../groupdocs.annotation.models.annotationmodels/watermarkannotation/verticalalignment) { get; set; } | الحصول على أو تعيين المحاذاة الرأسية للعلامة المائية على document |

## طُرق

| اسم | وصف |
| --- | --- |
| override [Clone](../../groupdocs.annotation.models.annotationmodels/watermarkannotation/clone)() | إرجاع مثيل جديد بنفس القيم |
| [Equals](../../groupdocs.annotation.models.annotationmodels/annotationbase/equals)(AnnotationBase) | مقارنة التعليقات التوضيحية الأساسية باستخدام طريقة IEquatable Equals |
| override [Equals](../../groupdocs.annotation.models.annotationmodels/watermarkannotation/equals#equals_2)(object) | يقارن التعليقات التوضيحية للعلامة المائية باستخدام كائن قياسي يساوي طريقة |
| [Equals](../../groupdocs.annotation.models.annotationmodels/watermarkannotation/equals#equals_1)(WatermarkAnnotation) | يقارن التعليقات التوضيحية للعلامة المائية باستخدام طريقة IEquatable Equals |
| override [GetHashCode](../../groupdocs.annotation.models.annotationmodels/watermarkannotation/gethashcode)() | إرجاع HashCode للتعليق التوضيحي للعلامة المائية |

### ملاحظات

**يتعلم أكثر**

* المزيد حول أنواع التعليقات التوضيحية والتعليقات التوضيحية على مستندات PDF و Microsoft Word وجداول بيانات Excel وعروض PowerPoint التقديمية: [كيفية إضافة تعليق توضيحي على المستندات باستخدام GroupDocs.Annotation for .NET](https://docs.groupdocs.com/display/annotationnet/Add+annotation+to+the+document)
* المزيد حول إضافة التعليقات التوضيحية للعلامة المائية إلى المستندات من مختلف الأنواع: [كيفية إضافة التعليقات التوضيحية للعلامة المائية في C #](https://docs.groupdocs.com/display/annotationnet/Add+watermark+annotation)

### أنظر أيضا

* class [AnnotationBase](../annotationbase)
* interface [IWatermarkAnnotation](../../groupdocs.annotation.models.annotationmodels.interfaces.annotations/iwatermarkannotation)
* مساحة الاسم [GroupDocs.Annotation.Models.AnnotationModels](../../groupdocs.annotation.models.annotationmodels)
* المجسم [GroupDocs.Annotation](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Annotation.dll -->
