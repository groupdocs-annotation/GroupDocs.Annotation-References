---
title: FileType
second_title: .NET API Başvurusu için GroupDocs.Annotation
description: Tür uzantı vb. gibi dosya hakkında bilgiler.
type: docs
weight: 120
url: /tr/net/groupdocs.annotation/filetype/
---
## FileType class

Tür, uzantı vb. gibi dosya hakkında bilgiler.

```csharp
public sealed class FileType : IEquatable<FileType>
```

## Özellikleri

| İsim | Tanım |
| --- | --- |
| static [Bmp](../../groupdocs.annotation/filetype/bmp) { get; } | Bitmap Görüntü Dosyası. |
| static [Doc](../../groupdocs.annotation/filetype/doc) { get; } | Microsoft Word biçimi. |
| static [Docm](../../groupdocs.annotation/filetype/docm) { get; } | Microsoft Word 2007 Makro dosyası. |
| static [Docx](../../groupdocs.annotation/filetype/docx) { get; } | Microsoft Word Açık XML biçimi. |
| static [Dot](../../groupdocs.annotation/filetype/dot) { get; } | Microsoft Word Belge Şablonu. |
| static [Dotm](../../groupdocs.annotation/filetype/dotm) { get; } | Microsoft Word Makro Etkin Belge Şablonu. |
| static [Dotx](../../groupdocs.annotation/filetype/dotx) { get; } | Microsoft Word Şablonu. |
| static [Dwg](../../groupdocs.annotation/filetype/dwg) { get; } | AutoCAD Çizim Veritabanı Dosyası. |
| static [Dxf](../../groupdocs.annotation/filetype/dxf) { get; } | Çizim Değişim Biçimi Dosyası. |
| static [Eml](../../groupdocs.annotation/filetype/eml) { get; } | MIME standardındaki dosya. |
| static [Emlx](../../groupdocs.annotation/filetype/emlx) { get; } | Apple'ın Mail.app programı dosya biçimi. |
| static [Htm](../../groupdocs.annotation/filetype/htm) { get; } | Köprü Metni Biçimlendirme Dili Dosyası. |
| static [Html](../../groupdocs.annotation/filetype/html) { get; } | Köprü Metni Biçimlendirme Dili Dosyası. |
| static [Jpeg](../../groupdocs.annotation/filetype/jpeg) { get; } | Ortak Fotoğraf Uzmanları Grubu. |
| static [Jpg](../../groupdocs.annotation/filetype/jpg) { get; } | Ortak Fotoğraf Uzmanları Grubu. |
| static [Odp](../../groupdocs.annotation/filetype/odp) { get; } | Belge Sunumunu Açın. |
| static [Ods](../../groupdocs.annotation/filetype/ods) { get; } | OpenDocument Elektronik Tablo Belgesi format |
| static [Odt](../../groupdocs.annotation/filetype/odt) { get; } | Belge Metnini Aç. |
| static [Pdf](../../groupdocs.annotation/filetype/pdf) { get; } | Adobe Taşınabilir Belge biçimi. |
| static [Png](../../groupdocs.annotation/filetype/png) { get; } | Taşınabilir Ağ Grafik Dosyası. |
| static [Pps](../../groupdocs.annotation/filetype/pps) { get; } | Microsoft PowerPoint Slayt Gösterisi (Eski). |
| static [Ppsx](../../groupdocs.annotation/filetype/ppsx) { get; } | Microsoft PowerPoint Slayt Gösterisi. |
| static [Ppt](../../groupdocs.annotation/filetype/ppt) { get; } | Microsoft PowerPoint Sunumu. |
| static [Pptx](../../groupdocs.annotation/filetype/pptx) { get; } | Microsoft PowerPoint Açık XML Sunumu. |
| static [Rtf](../../groupdocs.annotation/filetype/rtf) { get; } | Zengin Metin Biçimi Dosyası. |
| static [Tif](../../groupdocs.annotation/filetype/tif) { get; } | Etiketli Resim Dosyası. |
| static [Tiff](../../groupdocs.annotation/filetype/tiff) { get; } | Etiketli Görüntü Dosyası Formatı |
| static [Unknown](../../groupdocs.annotation/filetype/unknown) { get; } | Bilinmiyor. |
| static [Vsd](../../groupdocs.annotation/filetype/vsd) { get; } | Microsoft Visio VSD ikili biçimi. |
| static [Vsdm](../../groupdocs.annotation/filetype/vsdm) { get; } | Microsoft Visio Makro Etkinleştirilmiş Çizim. |
| static [Vsdx](../../groupdocs.annotation/filetype/vsdx) { get; } | Microsoft Visio 2013 VSDX dosya biçimi. |
| static [Vss](../../groupdocs.annotation/filetype/vss) { get; } | Microsoft Visio Şablon Dosyası. |
| static [Vssx](../../groupdocs.annotation/filetype/vssx) { get; } | Microsoft Visio Şablon Dosyası. |
| static [Vst](../../groupdocs.annotation/filetype/vst) { get; } | Microsoft Visio VST ikili şablon biçimi. |
| static [Vstm](../../groupdocs.annotation/filetype/vstm) { get; } | Microsoft Visio Makro Etkinleştirilmiş Çizim Şablonu. |
| static [Vsx](../../groupdocs.annotation/filetype/vsx) { get; } | Microsoft Visio Stencil XML Dosyası. |
| static [Xls](../../groupdocs.annotation/filetype/xls) { get; } | Microsoft Excel Elektronik Tablo biçimi. |
| static [Xlsb](../../groupdocs.annotation/filetype/xlsb) { get; } | Excel İkili Dosya Biçimi |
| static [Xlsm](../../groupdocs.annotation/filetype/xlsm) { get; } | Microsoft Excel Elektronik Tablo Makroları format |
| static [Xlsx](../../groupdocs.annotation/filetype/xlsx) { get; } | Microsoft Excel Açık XML Hesap Tablosu. |
| [Extension](../../groupdocs.annotation/filetype/extension) { get; } | Dosya uzantısı |
| [FileFormat](../../groupdocs.annotation/filetype/fileformat) { get; } | Dosya biçimi |

## yöntemler

| İsim | Tanım |
| --- | --- |
| static [FromFileNameOrExtension](../../groupdocs.annotation/filetype/fromfilenameorextension)(string) | Dosya adı veya uzantısına göre Dosya Türü döndürür. |
| [Equals](../../groupdocs.annotation/filetype/equals#equals)(FileType) | Dosya türü denklik kontrolü. |
| override [Equals](../../groupdocs.annotation/filetype/equals#equals_1)(object) | Nesne ile denklik kontrolü. |
| override [GetHashCode](../../groupdocs.annotation/filetype/gethashcode)() | Karma kodunu alın. |
| override [ToString](../../groupdocs.annotation/filetype/tostring)() | Dosya türünü temsil eden bir dize döndürür. |
| static [GetSupportedFileTypes](../../groupdocs.annotation/filetype/getsupportedfiletypes)() | Desteklenen dosya türleri numaralandırmasını alın. |
| [operator ==](../../groupdocs.annotation/filetype/op_equality) | Operatör aşırı yüklenmesi. |
| [operator !=](../../groupdocs.annotation/filetype/op_inequality) | Operatör aşırı yüklenmesi. |

### Ayrıca bakınız

* ad alanı [GroupDocs.Annotation](../../groupdocs.annotation)
* toplantı [GroupDocs.Annotation](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Annotation.dll -->
