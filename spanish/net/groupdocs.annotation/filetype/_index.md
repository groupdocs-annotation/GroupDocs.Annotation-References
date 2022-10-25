---
title: FileType
second_title: GroupDocs.Annotation para la referencia de la API de .NET
description: Información sobre el archivo como tipo extensión etc.
type: docs
weight: 120
url: /es/net/groupdocs.annotation/filetype/
---
## FileType class

Información sobre el archivo, como tipo, extensión, etc.

```csharp
public sealed class FileType : IEquatable<FileType>
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| static [Bmp](../../groupdocs.annotation/filetype/bmp) { get; } | Archivo de imagen de mapa de bits. |
| static [Doc](../../groupdocs.annotation/filetype/doc) { get; } | formato Microsoft Word. |
| static [Docm](../../groupdocs.annotation/filetype/docm) { get; } | Archivo de macros de Microsoft Word 2007. |
| static [Docx](../../groupdocs.annotation/filetype/docx) { get; } | Formato XML abierto de Microsoft Word. |
| static [Dot](../../groupdocs.annotation/filetype/dot) { get; } | Plantilla de documento de Microsoft Word. |
| static [Dotm](../../groupdocs.annotation/filetype/dotm) { get; } | Plantilla de documento habilitada para macros de Microsoft Word. |
| static [Dotx](../../groupdocs.annotation/filetype/dotx) { get; } | Plantilla de Microsoft Word. |
| static [Dwg](../../groupdocs.annotation/filetype/dwg) { get; } | Archivo de base de datos de dibujos de AutoCAD. |
| static [Dxf](../../groupdocs.annotation/filetype/dxf) { get; } | Archivo de formato de intercambio de dibujos. |
| static [Eml](../../groupdocs.annotation/filetype/eml) { get; } | Archivo en el estándar MIME. |
| static [Emlx](../../groupdocs.annotation/filetype/emlx) { get; } | Formato de archivo del programa Mail.app de Apple. |
| static [Htm](../../groupdocs.annotation/filetype/htm) { get; } | Archivo de lenguaje de marcado de hipertexto. |
| static [Html](../../groupdocs.annotation/filetype/html) { get; } | Archivo de lenguaje de marcado de hipertexto. |
| static [Jpeg](../../groupdocs.annotation/filetype/jpeg) { get; } | Grupo Conjunto de Expertos Fotográficos. |
| static [Jpg](../../groupdocs.annotation/filetype/jpg) { get; } | Grupo Conjunto de Expertos Fotográficos. |
| static [Odp](../../groupdocs.annotation/filetype/odp) { get; } | Abrir presentación de documento. |
| static [Ods](../../groupdocs.annotation/filetype/ods) { get; } | Formato de documento de hoja de cálculo de OpenDocument |
| static [Odt](../../groupdocs.annotation/filetype/odt) { get; } | Texto de documento abierto. |
| static [Pdf](../../groupdocs.annotation/filetype/pdf) { get; } | Formato de documento portátil de Adobe. |
| static [Png](../../groupdocs.annotation/filetype/png) { get; } | Archivo gráfico de red portátil. |
| static [Pps](../../groupdocs.annotation/filetype/pps) { get; } | Presentación de diapositivas de Microsoft PowerPoint (heredado). |
| static [Ppsx](../../groupdocs.annotation/filetype/ppsx) { get; } | Presentación de diapositivas de Microsoft PowerPoint. |
| static [Ppt](../../groupdocs.annotation/filetype/ppt) { get; } | Presentación de Microsoft PowerPoint. |
| static [Pptx](../../groupdocs.annotation/filetype/pptx) { get; } | Presentación XML abierta de Microsoft PowerPoint. |
| static [Rtf](../../groupdocs.annotation/filetype/rtf) { get; } | Archivo de formato de texto enriquecido. |
| static [Tif](../../groupdocs.annotation/filetype/tif) { get; } | Archivo de imagen etiquetado. |
| static [Tiff](../../groupdocs.annotation/filetype/tiff) { get; } | Formato de archivo de imagen etiquetado |
| static [Unknown](../../groupdocs.annotation/filetype/unknown) { get; } | Desconocido. |
| static [Vsd](../../groupdocs.annotation/filetype/vsd) { get; } | Formato binario Microsoft Visio VSD. |
| static [Vsdm](../../groupdocs.annotation/filetype/vsdm) { get; } | Dibujo habilitado para macros de Microsoft Visio. |
| static [Vsdx](../../groupdocs.annotation/filetype/vsdx) { get; } | Formato de archivo VSDX de Microsoft Visio 2013. |
| static [Vss](../../groupdocs.annotation/filetype/vss) { get; } | Archivo de plantilla de Microsoft Visio. |
| static [Vssx](../../groupdocs.annotation/filetype/vssx) { get; } | Archivo de plantilla de Microsoft Visio. |
| static [Vst](../../groupdocs.annotation/filetype/vst) { get; } | Formato de plantilla binaria VST de Microsoft Visio. |
| static [Vstm](../../groupdocs.annotation/filetype/vstm) { get; } | Plantilla de dibujo habilitada para macros de Microsoft Visio. |
| static [Vsx](../../groupdocs.annotation/filetype/vsx) { get; } | Archivo XML de plantilla de Microsoft Visio. |
| static [Xls](../../groupdocs.annotation/filetype/xls) { get; } | Formato de hoja de cálculo de Microsoft Excel. |
| static [Xlsb](../../groupdocs.annotation/filetype/xlsb) { get; } | Formato de archivo binario de Excel |
| static [Xlsm](../../groupdocs.annotation/filetype/xlsm) { get; } | Formato de macros de hoja de cálculo de Microsoft Excel |
| static [Xlsx](../../groupdocs.annotation/filetype/xlsx) { get; } | Hoja de cálculo XML abierta de Microsoft Excel. |
| [Extension](../../groupdocs.annotation/filetype/extension) { get; } | Extensión de archivo |
| [FileFormat](../../groupdocs.annotation/filetype/fileformat) { get; } | Formato de archivo |

## Métodos

| Nombre | Descripción |
| --- | --- |
| static [FromFileNameOrExtension](../../groupdocs.annotation/filetype/fromfilenameorextension)(string) | Devuelve el tipo de archivo según el nombre o la extensión del archivo. |
| [Equals](../../groupdocs.annotation/filetype/equals#equals)(FileType) | Comprobación de equivalencia de tipo de archivo. |
| override [Equals](../../groupdocs.annotation/filetype/equals#equals_1)(object) | Comprobación de equivalencia con objeto. |
| override [GetHashCode](../../groupdocs.annotation/filetype/gethashcode)() | Obtener código hash. |
| override [ToString](../../groupdocs.annotation/filetype/tostring)() | Devuelve una cadena que representa el tipo de archivo. |
| static [GetSupportedFileTypes](../../groupdocs.annotation/filetype/getsupportedfiletypes)() | Obtener enumeración de tipos de archivo admitidos. |
| [operator ==](../../groupdocs.annotation/filetype/op_equality) | Sobrecarga de operador. |
| [operator !=](../../groupdocs.annotation/filetype/op_inequality) | Sobrecarga de operador. |

### Ver también

* espacio de nombres [GroupDocs.Annotation](../../groupdocs.annotation)
* asamblea [GroupDocs.Annotation](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Annotation.dll -->
