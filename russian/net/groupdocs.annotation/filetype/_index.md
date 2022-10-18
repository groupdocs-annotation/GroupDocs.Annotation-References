---
title: FileType
second_title: Справочник по API GroupDocs.Annotation для .NET
description: Информация о файле такая как тип расширение и т. д.
type: docs
weight: 120
url: /ru/net/groupdocs.annotation/filetype/
---
## FileType class

Информация о файле, такая как тип, расширение и т. д.

```csharp
public sealed class FileType : IEquatable<FileType>
```

## Характеристики

| Имя | Описание |
| --- | --- |
| static [Bmp](../../groupdocs.annotation/filetype/bmp) { get; } | Файл растрового изображения. |
| static [Doc](../../groupdocs.annotation/filetype/doc) { get; } | Формат Microsoft Word. |
| static [Docm](../../groupdocs.annotation/filetype/docm) { get; } | Файл макроса Microsoft Word 2007. |
| static [Docx](../../groupdocs.annotation/filetype/docx) { get; } | Формат Microsoft Word Open XML. |
| static [Dot](../../groupdocs.annotation/filetype/dot) { get; } | Шаблон документа Microsoft Word. |
| static [Dotm](../../groupdocs.annotation/filetype/dotm) { get; } | Шаблон документа Microsoft Word с поддержкой макросов. |
| static [Dotx](../../groupdocs.annotation/filetype/dotx) { get; } | Шаблон Microsoft Word. |
| static [Dwg](../../groupdocs.annotation/filetype/dwg) { get; } | Файл базы данных чертежей AutoCAD. |
| static [Dxf](../../groupdocs.annotation/filetype/dxf) { get; } | Файл формата обмена чертежами. |
| static [Eml](../../groupdocs.annotation/filetype/eml) { get; } | Файл в стандарте MIME. |
| static [Emlx](../../groupdocs.annotation/filetype/emlx) { get; } | Формат файла программы Apple Mail.app. |
| static [Htm](../../groupdocs.annotation/filetype/htm) { get; } | Файл языка разметки гипертекста. |
| static [Html](../../groupdocs.annotation/filetype/html) { get; } | Файл языка разметки гипертекста. |
| static [Jpeg](../../groupdocs.annotation/filetype/jpeg) { get; } | Объединенная группа экспертов по фотографии. |
| static [Jpg](../../groupdocs.annotation/filetype/jpg) { get; } | Объединенная группа экспертов по фотографии. |
| static [Odp](../../groupdocs.annotation/filetype/odp) { get; } | Открыть презентацию документа. |
| static [Ods](../../groupdocs.annotation/filetype/ods) { get; } | Формат документа электронной таблицы OpenDocument |
| static [Odt](../../groupdocs.annotation/filetype/odt) { get; } | Текст открытого документа. |
| static [Pdf](../../groupdocs.annotation/filetype/pdf) { get; } | Формат Adobe Portable Document. |
| static [Png](../../groupdocs.annotation/filetype/png) { get; } | Файл переносимой сетевой графики. |
| static [Pps](../../groupdocs.annotation/filetype/pps) { get; } | Слайд-шоу Microsoft PowerPoint (предыдущая версия). |
| static [Ppsx](../../groupdocs.annotation/filetype/ppsx) { get; } | Слайд-шоу Microsoft PowerPoint. |
| static [Ppt](../../groupdocs.annotation/filetype/ppt) { get; } | Презентация Microsoft PowerPoint. |
| static [Pptx](../../groupdocs.annotation/filetype/pptx) { get; } | Презентация Microsoft PowerPoint Open XML. |
| static [Rtf](../../groupdocs.annotation/filetype/rtf) { get; } | Файл форматированного текста. |
| static [Tif](../../groupdocs.annotation/filetype/tif) { get; } | Файл изображения с тегами. |
| static [Tiff](../../groupdocs.annotation/filetype/tiff) { get; } | Формат файла изображения с тегами |
| static [Unknown](../../groupdocs.annotation/filetype/unknown) { get; } | Неизвестно. |
| static [Vsd](../../groupdocs.annotation/filetype/vsd) { get; } | Двоичный формат Microsoft Visio VSD. |
| static [Vsdm](../../groupdocs.annotation/filetype/vsdm) { get; } | Чертеж Microsoft Visio с поддержкой макросов. |
| static [Vsdx](../../groupdocs.annotation/filetype/vsdx) { get; } | Формат файла Microsoft Visio 2013 VSDX. |
| static [Vss](../../groupdocs.annotation/filetype/vss) { get; } | Файл трафарета Microsoft Visio. |
| static [Vssx](../../groupdocs.annotation/filetype/vssx) { get; } | Файл трафарета Microsoft Visio. |
| static [Vst](../../groupdocs.annotation/filetype/vst) { get; } | Двоичный формат шаблона Microsoft Visio VST. |
| static [Vstm](../../groupdocs.annotation/filetype/vstm) { get; } | Шаблон чертежа Microsoft Visio с поддержкой макросов. |
| static [Vsx](../../groupdocs.annotation/filetype/vsx) { get; } | XML-файл трафарета Microsoft Visio. |
| static [Xls](../../groupdocs.annotation/filetype/xls) { get; } | Формат электронной таблицы Microsoft Excel. |
| static [Xlsb](../../groupdocs.annotation/filetype/xlsb) { get; } | Формат двоичного файла Excel |
| static [Xlsm](../../groupdocs.annotation/filetype/xlsm) { get; } | Формат макросов электронной таблицы Microsoft Excel |
| static [Xlsx](../../groupdocs.annotation/filetype/xlsx) { get; } | Электронная таблица Microsoft Excel Open XML. |
| [Extension](../../groupdocs.annotation/filetype/extension) { get; } | Расширение файла |
| [FileFormat](../../groupdocs.annotation/filetype/fileformat) { get; } | Формат файла |

## Методы

| Имя | Описание |
| --- | --- |
| static [FromFileNameOrExtension](../../groupdocs.annotation/filetype/fromfilenameorextension)(string) | Возвращает тип файла на основе имени файла или расширения. |
| [Equals](../../groupdocs.annotation/filetype/equals#equals)(FileType) | Проверка эквивалентности типов файлов. |
| override [Equals](../../groupdocs.annotation/filetype/equals#equals_1)(object) | Проверка эквивалентности с объектом. |
| override [GetHashCode](../../groupdocs.annotation/filetype/gethashcode)() | Получить хэш-код. |
| override [ToString](../../groupdocs.annotation/filetype/tostring)() | Возвращает строку, представляющую тип файла. |
| static [GetSupportedFileTypes](../../groupdocs.annotation/filetype/getsupportedfiletypes)() | Получить список поддерживаемых типов файлов. |
| [operator ==](../../groupdocs.annotation/filetype/op_equality) | Перегрузка оператора. |
| [operator !=](../../groupdocs.annotation/filetype/op_inequality) | Перегрузка оператора. |

### Смотрите также

* пространство имен [GroupDocs.Annotation](../../groupdocs.annotation)
* сборка [GroupDocs.Annotation](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Annotation.dll -->
