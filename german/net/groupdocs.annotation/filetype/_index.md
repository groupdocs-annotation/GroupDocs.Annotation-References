---
title: FileType
second_title: GroupDocs.Annotation für .NET-API-Referenz
description: Informationen zur Datei wie Typ Erweiterung etc.
type: docs
weight: 120
url: /de/net/groupdocs.annotation/filetype/
---
## FileType class

Informationen zur Datei, wie Typ, Erweiterung etc.

```csharp
public sealed class FileType : IEquatable<FileType>
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| static [Bmp](../../groupdocs.annotation/filetype/bmp) { get; } | Bitmap-Bilddatei. |
| static [Doc](../../groupdocs.annotation/filetype/doc) { get; } | Microsoft Word-Format. |
| static [Docm](../../groupdocs.annotation/filetype/docm) { get; } | Microsoft Word 2007-Makrodatei. |
| static [Docx](../../groupdocs.annotation/filetype/docx) { get; } | Microsoft Word Open XML-Format. |
| static [Dot](../../groupdocs.annotation/filetype/dot) { get; } | Microsoft Word-Dokumentvorlage. |
| static [Dotm](../../groupdocs.annotation/filetype/dotm) { get; } | Microsoft Word-Dokumentvorlage mit Makros. |
| static [Dotx](../../groupdocs.annotation/filetype/dotx) { get; } | Microsoft Word-Vorlage. |
| static [Dwg](../../groupdocs.annotation/filetype/dwg) { get; } | AutoCAD-Zeichnungsdatenbankdatei. |
| static [Dxf](../../groupdocs.annotation/filetype/dxf) { get; } | Zeichnungsaustauschformatdatei. |
| static [Eml](../../groupdocs.annotation/filetype/eml) { get; } | Datei im MIME-Standard. |
| static [Emlx](../../groupdocs.annotation/filetype/emlx) { get; } | Dateiformat des Mail.app-Programms von Apple. |
| static [Htm](../../groupdocs.annotation/filetype/htm) { get; } | Hypertext Markup Language-Datei. |
| static [Html](../../groupdocs.annotation/filetype/html) { get; } | Hypertext Markup Language-Datei. |
| static [Jpeg](../../groupdocs.annotation/filetype/jpeg) { get; } | Gemeinsame fotografische Expertengruppe. |
| static [Jpg](../../groupdocs.annotation/filetype/jpg) { get; } | Gemeinsame fotografische Expertengruppe. |
| static [Odp](../../groupdocs.annotation/filetype/odp) { get; } | Dokumentpräsentation öffnen. |
| static [Ods](../../groupdocs.annotation/filetype/ods) { get; } | OpenDocument Spreadsheet Dokumentformat |
| static [Odt](../../groupdocs.annotation/filetype/odt) { get; } | Dokumenttext öffnen. |
| static [Pdf](../../groupdocs.annotation/filetype/pdf) { get; } | Adobe Portable Document-Format. |
| static [Png](../../groupdocs.annotation/filetype/png) { get; } | Grafikdatei für tragbare Netzwerke. |
| static [Pps](../../groupdocs.annotation/filetype/pps) { get; } | Microsoft PowerPoint-Bildschirmpräsentation (Legacy). |
| static [Ppsx](../../groupdocs.annotation/filetype/ppsx) { get; } | Microsoft PowerPoint-Diashow. |
| static [Ppt](../../groupdocs.annotation/filetype/ppt) { get; } | Microsoft PowerPoint-Präsentation. |
| static [Pptx](../../groupdocs.annotation/filetype/pptx) { get; } | Microsoft PowerPoint Open XML-Präsentation. |
| static [Rtf](../../groupdocs.annotation/filetype/rtf) { get; } | Datei im Rich-Text-Format. |
| static [Tif](../../groupdocs.annotation/filetype/tif) { get; } | Markierte Bilddatei. |
| static [Tiff](../../groupdocs.annotation/filetype/tiff) { get; } | getaggtes Bilddateiformat |
| static [Unknown](../../groupdocs.annotation/filetype/unknown) { get; } | Unbekannt. |
| static [Vsd](../../groupdocs.annotation/filetype/vsd) { get; } | Microsoft Visio VSD-Binärformat. |
| static [Vsdm](../../groupdocs.annotation/filetype/vsdm) { get; } | Zeichnung mit Microsoft Visio-Makros. |
| static [Vsdx](../../groupdocs.annotation/filetype/vsdx) { get; } | Microsoft Visio 2013 VSDX-Dateiformat. |
| static [Vss](../../groupdocs.annotation/filetype/vss) { get; } | Microsoft Visio-Schablonendatei. |
| static [Vssx](../../groupdocs.annotation/filetype/vssx) { get; } | Microsoft Visio-Schablonendatei. |
| static [Vst](../../groupdocs.annotation/filetype/vst) { get; } | Microsoft Visio VST-Binärvorlagenformat. |
| static [Vstm](../../groupdocs.annotation/filetype/vstm) { get; } | Zeichnungsvorlage mit Microsoft Visio-Makros. |
| static [Vsx](../../groupdocs.annotation/filetype/vsx) { get; } | Microsoft Visio-XML-Schablonendatei. |
| static [Xls](../../groupdocs.annotation/filetype/xls) { get; } | Microsoft Excel-Tabellenformat. |
| static [Xlsb](../../groupdocs.annotation/filetype/xlsb) { get; } | Excel-Binärdateiformat |
| static [Xlsm](../../groupdocs.annotation/filetype/xlsm) { get; } | Format für Microsoft Excel-Tabellenmakros |
| static [Xlsx](../../groupdocs.annotation/filetype/xlsx) { get; } | Microsoft Excel Open XML-Tabelle. |
| [Extension](../../groupdocs.annotation/filetype/extension) { get; } | Dateierweiterung |
| [FileFormat](../../groupdocs.annotation/filetype/fileformat) { get; } | Dateiformat |

## Methoden

| Name | Beschreibung |
| --- | --- |
| static [FromFileNameOrExtension](../../groupdocs.annotation/filetype/fromfilenameorextension)(string) | Dateityp basierend auf Dateiname oder -erweiterung zurückgeben. |
| [Equals](../../groupdocs.annotation/filetype/equals#equals)(FileType) | Dateityp-Äquivalenzprüfung. |
| override [Equals](../../groupdocs.annotation/filetype/equals#equals_1)(object) | Äquivalenzprüfung mit Objekt. |
| override [GetHashCode](../../groupdocs.annotation/filetype/gethashcode)() | Hashcode abrufen. |
| override [ToString](../../groupdocs.annotation/filetype/tostring)() | Gibt eine Zeichenfolge zurück, die den Dateityp darstellt. |
| static [GetSupportedFileTypes](../../groupdocs.annotation/filetype/getsupportedfiletypes)() | Liste der unterstützten Dateitypen abrufen. |
| [operator ==](../../groupdocs.annotation/filetype/op_equality) | Operatorüberladung. |
| [operator !=](../../groupdocs.annotation/filetype/op_inequality) | Operatorüberladung. |

### Siehe auch

* namensraum [GroupDocs.Annotation](../../groupdocs.annotation)
* Montage [GroupDocs.Annotation](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Annotation.dll -->
