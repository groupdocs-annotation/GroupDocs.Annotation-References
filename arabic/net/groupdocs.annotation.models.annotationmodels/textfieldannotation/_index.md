---
title: TextFieldAnnotation
second_title: GroupDocs.Annotation for .NET API Reference
description: يمثل خصائص التعليق التوضيحي لحقل النص
type: docs
weight: 710
url: /ar/net/groupdocs.annotation.models.annotationmodels/textfieldannotation/
---
## TextFieldAnnotation class

يمثل خصائص التعليق التوضيحي لحقل النص

```csharp
public class TextFieldAnnotation : AnnotationBase, IEquatable<TextFieldAnnotation>, 
    ITextFieldAnnotation
```

## المنشئون

| اسم | وصف |
| --- | --- |
| [TextFieldAnnotation](textfieldannotation)() | تهيئة مثيل جديد لـ[`TextFieldAnnotation`](../textfieldannotation) فئة . |

## الخصائص

| اسم | وصف |
| --- | --- |
| [BackgroundColor](../../groupdocs.annotation.models.annotationmodels/textfieldannotation/backgroundcolor) { get; set; } | الحصول على أو تعيين لون خلفية التعليق التوضيحي |
| [Box](../../groupdocs.annotation.models.annotationmodels/textfieldannotation/box) { get; set; } | الحصول على أو تعيين موضع التعليق التوضيحي |
| [CreatedOn](../../groupdocs.annotation.models.annotationmodels/annotationbase/createdon) { get; set; } | الحصول على تاريخ إنشاء التعليق التوضيحي أو تعيينه |
| [FontColor](../../groupdocs.annotation.models.annotationmodels/textfieldannotation/fontcolor) { get; set; } | الحصول على أو تعيين خط نص التعليق التوضيحي color |
| [FontFamily](../../groupdocs.annotation.models.annotationmodels/textfieldannotation/fontfamily) { get; set; } | الحصول على أو تعيين عائلة خط نص التعليق التوضيحي |
| [FontSize](../../groupdocs.annotation.models.annotationmodels/textfieldannotation/fontsize) { get; set; } | الحصول على حجم خط نص التعليق التوضيحي أو تعيينه |
| [Id](../../groupdocs.annotation.models.annotationmodels/annotationbase/id) { get; set; } | الحصول على أو تعيين المعرف الفريد للتعليق التوضيحي |
| [Message](../../groupdocs.annotation.models.annotationmodels/annotationbase/message) { get; set; } | الحصول على رسالة التعليق التوضيحي أو تعيينها |
| [Opacity](../../groupdocs.annotation.models.annotationmodels/textfieldannotation/opacity) { get; set; } | الحصول على تعتيم التعليق التوضيحي أو تعيينه |
| [PageNumber](../../groupdocs.annotation.models.annotationmodels/annotationbase/pagenumber) { get; set; } | الحصول على رقم الصفحة أو تعيينه ليتم التعليق عليه |
| [PenColor](../../groupdocs.annotation.models.annotationmodels/textfieldannotation/pencolor) { get; set; } | الحصول على أو تعيين لون قلم التعليقات التوضيحية |
| [PenStyle](../../groupdocs.annotation.models.annotationmodels/textfieldannotation/penstyle) { get; set; } | الحصول على أو تعيين أسلوب قلم التعليقات التوضيحي |
| [PenWidth](../../groupdocs.annotation.models.annotationmodels/textfieldannotation/penwidth) { get; set; } | الحصول على عرض قلم التعليق التوضيحي أو تعيينه |
| [Replies](../../groupdocs.annotation.models.annotationmodels/annotationbase/replies) { get; set; } | يمثل مجموعة ردود التعليقات التوضيحية |
| [Text](../../groupdocs.annotation.models.annotationmodels/textfieldannotation/text) { get; set; } | يحصل أو يحدد text |
| [TextHorizontalAlignment](../../groupdocs.annotation.models.annotationmodels/textfieldannotation/texthorizontalalignment) { get; set; } | الحصول على محاذاة أفقية للنص أو تعيينها |
| [Type](../../groupdocs.annotation.models.annotationmodels/annotationbase/type) { get; set; } | الحصول على نوع التعليق التوضيحي أو تعيينه |
| [User](../../groupdocs.annotation.models.annotationmodels/annotationbase/user) { get; set; } | الحصول على أو تعيين منشئ التعليقات التوضيحية |

## طُرق

| اسم | وصف |
| --- | --- |
| override [Clone](../../groupdocs.annotation.models.annotationmodels/textfieldannotation/clone)() | إرجاع مثيل جديد بنفس القيم |
| [Equals](../../groupdocs.annotation.models.annotationmodels/annotationbase/equals)(AnnotationBase) | مقارنة التعليقات التوضيحية الأساسية باستخدام طريقة IEquatable Equals |
| override [Equals](../../groupdocs.annotation.models.annotationmodels/textfieldannotation/equals#equals_2)(object) | مقارنة التعليقات التوضيحية لحقل النص باستخدام كائن قياسي يساوي طريقة |
| [Equals](../../groupdocs.annotation.models.annotationmodels/textfieldannotation/equals#equals_1)(TextFieldAnnotation) | يقارن التعليقات التوضيحية لحقل النص باستخدام طريقة IEquatable Equals |
| override [GetHashCode](../../groupdocs.annotation.models.annotationmodels/textfieldannotation/gethashcode)() | إرجاع HashCode للتعليق التوضيحي لحقل النص |

### ملاحظات

**يتعلم أكثر**

* المزيد حول أنواع التعليقات التوضيحية والتعليقات التوضيحية على مستندات PDF و Microsoft Word وجداول بيانات Excel وعروض PowerPoint التقديمية: [كيفية إضافة تعليق توضيحي على المستندات باستخدام GroupDocs.Annotation for .NET](https://docs.groupdocs.com/display/annotationnet/Add+annotation+to+the+document)
* المزيد حول إضافة التعليقات التوضيحية لحقل النص إلى المستندات من مختلف الأنواع: [كيفية إضافة شروح حقل النص في C #](https://docs.groupdocs.com/display/annotationnet/Add+text+field+annotation)

### أنظر أيضا

* class [AnnotationBase](../annotationbase)
* interface [ITextFieldAnnotation](../../groupdocs.annotation.models.annotationmodels.interfaces.annotations/itextfieldannotation)
* مساحة الاسم [GroupDocs.Annotation.Models.AnnotationModels](../../groupdocs.annotation.models.annotationmodels)
* المجسم [GroupDocs.Annotation](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Annotation.dll -->
