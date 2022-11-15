---
title: FileType
second_title: GroupDocs.Annotation for .NET API Reference
description: معلومات حول الملف  مثل النوع والامتداد وما إلى ذلك.
type: docs
weight: 120
url: /ar/net/groupdocs.annotation/filetype/
---
## FileType class

معلومات حول الملف ، مثل النوع والامتداد وما إلى ذلك.

```csharp
public sealed class FileType : IEquatable<FileType>
```

## الخصائص

| اسم | وصف |
| --- | --- |
| static [Bmp](../../groupdocs.annotation/filetype/bmp) { get; } | ملف صورة نقطية . |
| static [Doc](../../groupdocs.annotation/filetype/doc) { get; } | تنسيق Microsoft Word . |
| static [Docm](../../groupdocs.annotation/filetype/docm) { get; } | ملف ماكرو Microsoft Word 2007. |
| static [Docx](../../groupdocs.annotation/filetype/docx) { get; } | تنسيق Microsoft Word Open XML . |
| static [Dot](../../groupdocs.annotation/filetype/dot) { get; } | قالب مستند Microsoft Word . |
| static [Dotm](../../groupdocs.annotation/filetype/dotm) { get; } | قالب مستند ممكّن بماكرو لـ Microsoft Word . |
| static [Dotx](../../groupdocs.annotation/filetype/dotx) { get; } | قالب Microsoft Word . |
| static [Dwg](../../groupdocs.annotation/filetype/dwg) { get; } | ملف قاعدة بيانات رسم AutoCAD . |
| static [Dxf](../../groupdocs.annotation/filetype/dxf) { get; } | رسم ملف تنسيق التبادل . |
| static [Eml](../../groupdocs.annotation/filetype/eml) { get; } | ملف بمعيار MIME . |
| static [Emlx](../../groupdocs.annotation/filetype/emlx) { get; } | تنسيق ملف برنامج Apple Mail.app . |
| static [Htm](../../groupdocs.annotation/filetype/htm) { get; } | ملف لغة توصيف النص التشعبي . |
| static [Html](../../groupdocs.annotation/filetype/html) { get; } | ملف لغة توصيف النص التشعبي . |
| static [Jpeg](../../groupdocs.annotation/filetype/jpeg) { get; } | مجموعة خبراء التصوير المشتركة . |
| static [Jpg](../../groupdocs.annotation/filetype/jpg) { get; } | مجموعة خبراء التصوير المشتركة . |
| static [Odp](../../groupdocs.annotation/filetype/odp) { get; } | فتح عرض تقديمي للمستند . |
| static [Ods](../../groupdocs.annotation/filetype/ods) { get; } | تنسيق مستند جدول بيانات OpenDocument |
| static [Odt](../../groupdocs.annotation/filetype/odt) { get; } | فتح نص المستند. |
| static [Pdf](../../groupdocs.annotation/filetype/pdf) { get; } | تنسيق Adobe Portable Document. |
| static [Png](../../groupdocs.annotation/filetype/png) { get; } | ملف رسومات الشبكة المحمولة. |
| static [Pps](../../groupdocs.annotation/filetype/pps) { get; } | عرض شرائح Microsoft PowerPoint (قديم) . |
| static [Ppsx](../../groupdocs.annotation/filetype/ppsx) { get; } | عرض شرائح Microsoft PowerPoint |
| static [Ppt](../../groupdocs.annotation/filetype/ppt) { get; } | عرض تقديمي لـ Microsoft PowerPoint |
| static [Pptx](../../groupdocs.annotation/filetype/pptx) { get; } | Microsoft PowerPoint Open XML Presentation. |
| static [Rtf](../../groupdocs.annotation/filetype/rtf) { get; } | ملف بتنسيق نص منسق . |
| static [Tif](../../groupdocs.annotation/filetype/tif) { get; } | ملف الصور الموسومة . |
| static [Tiff](../../groupdocs.annotation/filetype/tiff) { get; } | تنسيق ملف الصورة الموسوم |
| static [Unknown](../../groupdocs.annotation/filetype/unknown) { get; } | غير معروف . |
| static [Vsd](../../groupdocs.annotation/filetype/vsd) { get; } | تنسيق Microsoft Visio VSD الثنائي . |
| static [Vsdm](../../groupdocs.annotation/filetype/vsdm) { get; } | رسم ممكّن بماكرو Microsoft Visio . |
| static [Vsdx](../../groupdocs.annotation/filetype/vsdx) { get; } | تنسيق ملف Microsoft Visio 2013 VSDX . |
| static [Vss](../../groupdocs.annotation/filetype/vss) { get; } | ملف استنسل Microsoft Visio . |
| static [Vssx](../../groupdocs.annotation/filetype/vssx) { get; } | ملف استنسل Microsoft Visio . |
| static [Vst](../../groupdocs.annotation/filetype/vst) { get; } | تنسيق قالب Microsoft Visio VST الثنائي . |
| static [Vstm](../../groupdocs.annotation/filetype/vstm) { get; } | قالب رسم تم تمكين ماكرو لـ Microsoft Visio . |
| static [Vsx](../../groupdocs.annotation/filetype/vsx) { get; } | ملف Microsoft Visio Stencil XML . |
| static [Xls](../../groupdocs.annotation/filetype/xls) { get; } | تنسيق جدول بيانات Microsoft Excel . |
| static [Xlsb](../../groupdocs.annotation/filetype/xlsb) { get; } | تنسيق ملف Excel الثنائي |
| static [Xlsm](../../groupdocs.annotation/filetype/xlsm) { get; } | تنسيق وحدات ماكرو لجدول بيانات Microsoft Excel |
| static [Xlsx](../../groupdocs.annotation/filetype/xlsx) { get; } | Microsoft Excel افتح جدول بيانات XML . |
| [Extension](../../groupdocs.annotation/filetype/extension) { get; } | امتداد الملف |
| [FileFormat](../../groupdocs.annotation/filetype/fileformat) { get; } | تنسيق الملف |

## طُرق

| اسم | وصف |
| --- | --- |
| static [FromFileNameOrExtension](../../groupdocs.annotation/filetype/fromfilenameorextension)(string) | إرجاع نوع الملف بناءً على اسم الملف أو الامتداد . |
| [Equals](../../groupdocs.annotation/filetype/equals#equals)(FileType) | فحص تكافؤ نوع الملف. |
| override [Equals](../../groupdocs.annotation/filetype/equals#equals_1)(object) | فحص التكافؤ بالكائن . |
| override [GetHashCode](../../groupdocs.annotation/filetype/gethashcode)() | احصل على كود التجزئة . |
| override [ToString](../../groupdocs.annotation/filetype/tostring)() | إرجاع سلسلة تمثل نوع الملف. |
| static [GetSupportedFileTypes](../../groupdocs.annotation/filetype/getsupportedfiletypes)() | الحصول على تعداد أنواع الملفات المدعومة. |
| [operator ==](../../groupdocs.annotation/filetype/op_equality) | الحمل الزائد على المشغل . |
| [operator !=](../../groupdocs.annotation/filetype/op_inequality) | الحمل الزائد على المشغل . |

### أنظر أيضا

* مساحة الاسم [GroupDocs.Annotation](../../groupdocs.annotation)
* المجسم [GroupDocs.Annotation](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Annotation.dll -->
