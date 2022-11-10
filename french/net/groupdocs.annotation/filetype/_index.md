---
title: FileType
second_title: Référence de l'API GroupDocs.Annotation pour .NET
description: Informations sur le fichier telles que le type lextension etc.
type: docs
weight: 120
url: /fr/net/groupdocs.annotation/filetype/
---
## FileType class

Informations sur le fichier, telles que le type, l'extension, etc.

```csharp
public sealed class FileType : IEquatable<FileType>
```

## Propriétés

| Nom | La description |
| --- | --- |
| static [Bmp](../../groupdocs.annotation/filetype/bmp) { get; } | Fichier image bitmap. |
| static [Doc](../../groupdocs.annotation/filetype/doc) { get; } | Format Microsoft Word. |
| static [Docm](../../groupdocs.annotation/filetype/docm) { get; } | Fichier macro Microsoft Word 2007. |
| static [Docx](../../groupdocs.annotation/filetype/docx) { get; } | Format Microsoft Word Open XML. |
| static [Dot](../../groupdocs.annotation/filetype/dot) { get; } | Modèle de document Microsoft Word. |
| static [Dotm](../../groupdocs.annotation/filetype/dotm) { get; } | Modèle de document prenant en charge les macros Microsoft Word. |
| static [Dotx](../../groupdocs.annotation/filetype/dotx) { get; } | Modèle Microsoft Word. |
| static [Dwg](../../groupdocs.annotation/filetype/dwg) { get; } | Fichier de base de données de dessin AutoCAD. |
| static [Dxf](../../groupdocs.annotation/filetype/dxf) { get; } | Fichier de format d'échange de dessin. |
| static [Eml](../../groupdocs.annotation/filetype/eml) { get; } | Fichier au standard MIME. |
| static [Emlx](../../groupdocs.annotation/filetype/emlx) { get; } | Format de fichier du programme Mail.app d'Apple. |
| static [Htm](../../groupdocs.annotation/filetype/htm) { get; } | Fichier de langage de balisage hypertexte. |
| static [Html](../../groupdocs.annotation/filetype/html) { get; } | Fichier de langage de balisage hypertexte. |
| static [Jpeg](../../groupdocs.annotation/filetype/jpeg) { get; } | Groupe mixte d'experts photographiques. |
| static [Jpg](../../groupdocs.annotation/filetype/jpg) { get; } | Groupe mixte d'experts photographiques. |
| static [Odp](../../groupdocs.annotation/filetype/odp) { get; } | Ouvrir la présentation du document. |
| static [Ods](../../groupdocs.annotation/filetype/ods) { get; } | Format de feuille de calcul OpenDocument |
| static [Odt](../../groupdocs.annotation/filetype/odt) { get; } | Ouvrir le texte du document. |
| static [Pdf](../../groupdocs.annotation/filetype/pdf) { get; } | Format de document portable Adobe. |
| static [Png](../../groupdocs.annotation/filetype/png) { get; } | Fichier graphique réseau portable. |
| static [Pps](../../groupdocs.annotation/filetype/pps) { get; } | Diaporama Microsoft PowerPoint (hérité). |
| static [Ppsx](../../groupdocs.annotation/filetype/ppsx) { get; } | Diaporama Microsoft PowerPoint. |
| static [Ppt](../../groupdocs.annotation/filetype/ppt) { get; } | Présentation Microsoft PowerPoint. |
| static [Pptx](../../groupdocs.annotation/filetype/pptx) { get; } | Présentation XML ouverte Microsoft PowerPoint. |
| static [Rtf](../../groupdocs.annotation/filetype/rtf) { get; } | Fichier au format RTF. |
| static [Tif](../../groupdocs.annotation/filetype/tif) { get; } | Fichier image balisé. |
| static [Tiff](../../groupdocs.annotation/filetype/tiff) { get; } | Format de fichier image balisé |
| static [Unknown](../../groupdocs.annotation/filetype/unknown) { get; } | Inconnu. |
| static [Vsd](../../groupdocs.annotation/filetype/vsd) { get; } | Format binaire Microsoft Visio VSD. |
| static [Vsdm](../../groupdocs.annotation/filetype/vsdm) { get; } | Dessin prenant en charge les macros Microsoft Visio. |
| static [Vsdx](../../groupdocs.annotation/filetype/vsdx) { get; } | Format de fichier Microsoft Visio 2013 VSDX. |
| static [Vss](../../groupdocs.annotation/filetype/vss) { get; } | Fichier de gabarit Microsoft Visio. |
| static [Vssx](../../groupdocs.annotation/filetype/vssx) { get; } | Fichier de gabarit Microsoft Visio. |
| static [Vst](../../groupdocs.annotation/filetype/vst) { get; } | Format de modèle binaire Microsoft Visio VST. |
| static [Vstm](../../groupdocs.annotation/filetype/vstm) { get; } | Modèle de dessin prenant en charge les macros Microsoft Visio. |
| static [Vsx](../../groupdocs.annotation/filetype/vsx) { get; } | Fichier XML Microsoft Visio Stencil. |
| static [Xls](../../groupdocs.annotation/filetype/xls) { get; } | Format de feuille de calcul Microsoft Excel. |
| static [Xlsb](../../groupdocs.annotation/filetype/xlsb) { get; } | Format de fichier binaire Excel |
| static [Xlsm](../../groupdocs.annotation/filetype/xlsm) { get; } | Format des macros de feuille de calcul Microsoft Excel |
| static [Xlsx](../../groupdocs.annotation/filetype/xlsx) { get; } | Feuille de calcul XML ouverte Microsoft Excel. |
| [Extension](../../groupdocs.annotation/filetype/extension) { get; } | Extension de fichier |
| [FileFormat](../../groupdocs.annotation/filetype/fileformat) { get; } | Format de fichier |

## Méthodes

| Nom | La description |
| --- | --- |
| static [FromFileNameOrExtension](../../groupdocs.annotation/filetype/fromfilenameorextension)(string) | Renvoie FileType en fonction du nom ou de l'extension du fichier. |
| [Equals](../../groupdocs.annotation/filetype/equals#equals)(FileType) | Vérification d'équivalence de type de fichier. |
| override [Equals](../../groupdocs.annotation/filetype/equals#equals_1)(object) | Contrôle d'équivalence avec objet. |
| override [GetHashCode](../../groupdocs.annotation/filetype/gethashcode)() | Obtenir le code de hachage. |
| override [ToString](../../groupdocs.annotation/filetype/tostring)() | Renvoie une chaîne qui représente le type de fichier. |
| static [GetSupportedFileTypes](../../groupdocs.annotation/filetype/getsupportedfiletypes)() | Obtenir l'énumération des types de fichiers pris en charge. |
| [operator ==](../../groupdocs.annotation/filetype/op_equality) | Surcharge de l'opérateur. |
| [operator !=](../../groupdocs.annotation/filetype/op_inequality) | Surcharge de l'opérateur. |

### Voir également

* espace de noms [GroupDocs.Annotation](../../groupdocs.annotation)
* Assemblée [GroupDocs.Annotation](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Annotation.dll -->
