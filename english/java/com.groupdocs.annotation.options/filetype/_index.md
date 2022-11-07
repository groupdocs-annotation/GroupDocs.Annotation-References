---
title: FileType
second_title: GroupDocs.Annotation for Java API Reference
description: Information about file such as type extension etc.
type: docs
weight: 10
url: /java/com.groupdocs.annotation.options/filetype/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.ms.System.IEquatable
```
public final class FileType implements System.IEquatable<FileType>
```

Information about file, such as type, extension, etc.
## Fields

| Field | Description |
| --- | --- |
| [UNKNOWN](#UNKNOWN) | Unknown. |
| [DOC](#DOC) | Microsoft Word format. |
| [DOCX](#DOCX) | Microsoft Word Open XML format. |
| [DOCM](#DOCM) | Microsoft Word 2007 Macro file. |
| [DOT](#DOT) | Microsoft Word Document Template. |
| [DOTX](#DOTX) | Microsoft Word Template. |
| [DOTM](#DOTM) | Microsoft Word Macro-Enabled Document Template. |
| [RTF](#RTF) | Rich Text Format File. |
| [ODT](#ODT) | Open Document Text. |
| [XLS](#XLS) | Microsoft Excel Spreadsheet format. |
| [XLSX](#XLSX) | Microsoft Excel Open XML Spreadsheet. |
| [XLSM](#XLSM) | Microsoft Excel Spreadsheet Macros format |
| [XLSB](#XLSB) | Excel Binary File Format |
| [ODS](#ODS) | OpenDocument Spreadsheet Document format |
| [PPT](#PPT) | Microsoft PowerPoint Presentation. |
| [PPTX](#PPTX) | Microsoft PowerPoint Open XML Presentation. |
| [PPS](#PPS) | Microsoft PowerPoint Slide Show (Legacy). |
| [PPSX](#PPSX) | Microsoft PowerPoint Slide Show. |
| [ODP](#ODP) | Open Document Presentation. |
| [TIF](#TIF) | Tagged Image File. |
| [TIFF](#TIFF) | Tagged Image File Format |
| [JPEG](#JPEG) | Joint Photographic Experts Group. |
| [JPG](#JPG) | Joint Photographic Experts Group. |
| [PNG](#PNG) | Portable Network Graphic File. |
| [BMP](#BMP) | Bitmap Image File. |
| [DWG](#DWG) | AutoCAD Drawing Database File. |
| [DXF](#DXF) | Drawing Exchange Format File. |
| [PDF](#PDF) | Adobe Portable Document format. |
| [HTM](#HTM) | Hypertext Markup Language File. |
| [HTML](#HTML) | Hypertext Markup Language File. |
| [EML](#EML) | File in the MIME standard. |
| [EMLX](#EMLX) | Apple's Mail.app program file format. |
| [VSD](#VSD) | Microsoft Visio VSD binary format. |
| [VSDX](#VSDX) | Microsoft Visio 2013 VSDX file format. |
| [VSDM](#VSDM) | Microsoft Visio Macro-Enabled Drawing. |
| [VSS](#VSS) | Microsoft Visio Stencil File. |
| [VSX](#VSX) | Microsoft Visio Stencil XML File. |
| [VSSX](#VSSX) | Microsoft Visio Stencil File. |
| [VST](#VST) | Microsoft Visio VST binary template format. |
| [VSTM](#VSTM) | Microsoft Visio Macro-Enabled Drawing Template. |
## Methods

| Method | Description |
| --- | --- |
| [getFileFormat()](#getFileFormat--) | File format |
| [getExtension()](#getExtension--) | File extention |
| [fromFileNameOrExtension(String fileNameOrExtension)](#fromFileNameOrExtension-java.lang.String-) | Return FileType based on file name or extension. |
| [getSupportedFileTypes()](#getSupportedFileTypes--) | Get supported file types enumeration. |
| [equals(FileType other)](#equals-com.groupdocs.annotation.options.FileType-) | File type equivalence check. |
| [equals(Object obj)](#equals-java.lang.Object-) | Equivalence check with object. |
| [hashCode()](#hashCode--) | Get hash code. |
| [op_Equality(FileType left, FileType right)](#op-Equality-com.groupdocs.annotation.options.FileType-com.groupdocs.annotation.options.FileType-) | Operator overload. |
| [op_Inequality(FileType left, FileType right)](#op-Inequality-com.groupdocs.annotation.options.FileType-com.groupdocs.annotation.options.FileType-) | Operator overload. |
| [toString()](#toString--) | Returns a string that represents the file type. |
### UNKNOWN {#UNKNOWN}
```
public static FileType UNKNOWN
```


Unknown.

### DOC {#DOC}
```
public static FileType DOC
```


Microsoft Word format.

### DOCX {#DOCX}
```
public static FileType DOCX
```


Microsoft Word Open XML format.

### DOCM {#DOCM}
```
public static FileType DOCM
```


Microsoft Word 2007 Macro file.

### DOT {#DOT}
```
public static FileType DOT
```


Microsoft Word Document Template.

### DOTX {#DOTX}
```
public static FileType DOTX
```


Microsoft Word Template.

### DOTM {#DOTM}
```
public static FileType DOTM
```


Microsoft Word Macro-Enabled Document Template.

### RTF {#RTF}
```
public static FileType RTF
```


Rich Text Format File.

### ODT {#ODT}
```
public static FileType ODT
```


Open Document Text.

### XLS {#XLS}
```
public static FileType XLS
```


Microsoft Excel Spreadsheet format.

### XLSX {#XLSX}
```
public static FileType XLSX
```


Microsoft Excel Open XML Spreadsheet.

### XLSM {#XLSM}
```
public static FileType XLSM
```


Microsoft Excel Spreadsheet Macros format

### XLSB {#XLSB}
```
public static FileType XLSB
```


Excel Binary File Format

### ODS {#ODS}
```
public static FileType ODS
```


OpenDocument Spreadsheet Document format

### PPT {#PPT}
```
public static FileType PPT
```


Microsoft PowerPoint Presentation.

### PPTX {#PPTX}
```
public static FileType PPTX
```


Microsoft PowerPoint Open XML Presentation.

### PPS {#PPS}
```
public static FileType PPS
```


Microsoft PowerPoint Slide Show (Legacy).

### PPSX {#PPSX}
```
public static FileType PPSX
```


Microsoft PowerPoint Slide Show.

### ODP {#ODP}
```
public static FileType ODP
```


Open Document Presentation.

### TIF {#TIF}
```
public static FileType TIF
```


Tagged Image File.

### TIFF {#TIFF}
```
public static FileType TIFF
```


Tagged Image File Format

### JPEG {#JPEG}
```
public static FileType JPEG
```


Joint Photographic Experts Group.

### JPG {#JPG}
```
public static FileType JPG
```


Joint Photographic Experts Group.

### PNG {#PNG}
```
public static FileType PNG
```


Portable Network Graphic File.

### BMP {#BMP}
```
public static FileType BMP
```


Bitmap Image File.

### DWG {#DWG}
```
public static FileType DWG
```


AutoCAD Drawing Database File.

### DXF {#DXF}
```
public static FileType DXF
```


Drawing Exchange Format File.

### PDF {#PDF}
```
public static FileType PDF
```


Adobe Portable Document format.

### HTM {#HTM}
```
public static FileType HTM
```


Hypertext Markup Language File.

### HTML {#HTML}
```
public static FileType HTML
```


Hypertext Markup Language File.

### EML {#EML}
```
public static FileType EML
```


File in the MIME standard.

### EMLX {#EMLX}
```
public static FileType EMLX
```


Apple's Mail.app program file format.

### VSD {#VSD}
```
public static FileType VSD
```


Microsoft Visio VSD binary format.

### VSDX {#VSDX}
```
public static FileType VSDX
```


Microsoft Visio 2013 VSDX file format.

### VSDM {#VSDM}
```
public static FileType VSDM
```


Microsoft Visio Macro-Enabled Drawing.

### VSS {#VSS}
```
public static FileType VSS
```


Microsoft Visio Stencil File.

### VSX {#VSX}
```
public static FileType VSX
```


Microsoft Visio Stencil XML File.

### VSSX {#VSSX}
```
public static FileType VSSX
```


Microsoft Visio Stencil File.

### VST {#VST}
```
public static FileType VST
```


Microsoft Visio VST binary template format.

### VSTM {#VSTM}
```
public static FileType VSTM
```


Microsoft Visio Macro-Enabled Drawing Template.

### getFileFormat() {#getFileFormat--}
```
public final String getFileFormat()
```


File format

**Returns:**
java.lang.String - 
### getExtension() {#getExtension--}
```
public final String getExtension()
```


File extention

**Returns:**
java.lang.String - 
### fromFileNameOrExtension(String fileNameOrExtension) {#fromFileNameOrExtension-java.lang.String-}
```
public static FileType fromFileNameOrExtension(String fileNameOrExtension)
```


Return FileType based on file name or extension.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fileNameOrExtension | java.lang.String | The file name or file extension. |

**Returns:**
[FileType](../../com.groupdocs.annotation.options/filetype) - The file type.
### getSupportedFileTypes() {#getSupportedFileTypes--}
```
public static List<FileType> getSupportedFileTypes()
```


Get supported file types enumeration.

**Returns:**
java.util.List<com.groupdocs.annotation.options.FileType> - Enumeration of FileType.
### equals(FileType other) {#equals-com.groupdocs.annotation.options.FileType-}
```
public final boolean equals(FileType other)
```


File type equivalence check.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| other | [FileType](../../com.groupdocs.annotation.options/filetype) | FileType object. |

**Returns:**
boolean - True if file types are equivalent, false if not.
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Equivalence check with object.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| obj | java.lang.Object | Any object. |

**Returns:**
boolean - True if file types are equivalent, false if not.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Get hash code.

**Returns:**
int - Hash code.
### op_Equality(FileType left, FileType right) {#op-Equality-com.groupdocs.annotation.options.FileType-com.groupdocs.annotation.options.FileType-}
```
public static boolean op_Equality(FileType left, FileType right)
```


Operator overload.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| left | [FileType](../../com.groupdocs.annotation.options/filetype) | The left file type. |
| right | [FileType](../../com.groupdocs.annotation.options/filetype) | The right file type. |

**Returns:**
boolean - True if file types are equivalent, false if not.
### op_Inequality(FileType left, FileType right) {#op-Inequality-com.groupdocs.annotation.options.FileType-com.groupdocs.annotation.options.FileType-}
```
public static boolean op_Inequality(FileType left, FileType right)
```


Operator overload.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| left | [FileType](../../com.groupdocs.annotation.options/filetype) | The left file type. |
| right | [FileType](../../com.groupdocs.annotation.options/filetype) | The right file type. |

**Returns:**
boolean - True if file types are different, false if not.
### toString() {#toString--}
```
public String toString()
```


Returns a string that represents the file type.

**Returns:**
java.lang.String - A string that represents the file type.
