---
title: FileType
second_title: .NET API संदर्भ के लिए GroupDocs.Annotation
description: फ़इल के बरे में जनकर जैसे प्रकर एक्सटेंशन आद.
type: docs
weight: 120
url: /hi/net/groupdocs.annotation/filetype/
---
## FileType class

फ़ाइल के बारे में जानकारी, जैसे प्रकार, एक्सटेंशन, आदि.

```csharp
public sealed class FileType : IEquatable<FileType>
```

## गुण

| नाम | विवरण |
| --- | --- |
| static [Bmp](../../groupdocs.annotation/filetype/bmp) { get; } | बिटमैप छवि फ़ाइल. |
| static [Doc](../../groupdocs.annotation/filetype/doc) { get; } | माइक्रोसॉफ्ट वर्ड प्रारूप। |
| static [Docm](../../groupdocs.annotation/filetype/docm) { get; } | माइक्रोसॉफ्ट वर्ड 2007 मैक्रो फ़ाइल। |
| static [Docx](../../groupdocs.annotation/filetype/docx) { get; } | माइक्रोसॉफ्ट वर्ड ओपन एक्सएमएल प्रारूप. |
| static [Dot](../../groupdocs.annotation/filetype/dot) { get; } | माइक्रोसॉफ्ट वर्ड दस्तावेज़ टेम्पलेट। |
| static [Dotm](../../groupdocs.annotation/filetype/dotm) { get; } | माइक्रोसॉफ्ट वर्ड मैक्रो-सक्षम दस्तावेज़ टेम्पलेट। |
| static [Dotx](../../groupdocs.annotation/filetype/dotx) { get; } | माइक्रोसॉफ्ट वर्ड टेम्पलेट. |
| static [Dwg](../../groupdocs.annotation/filetype/dwg) { get; } | ऑटोकैड आरेखण डेटाबेस फ़ाइल। |
| static [Dxf](../../groupdocs.annotation/filetype/dxf) { get; } | आरेखण विनिमय प्रारूप फ़ाइल। |
| static [Eml](../../groupdocs.annotation/filetype/eml) { get; } | MIME मानक में फ़ाइल। |
| static [Emlx](../../groupdocs.annotation/filetype/emlx) { get; } | Apple का Mail.app प्रोग्राम फाइल फॉर्मेट. |
| static [Htm](../../groupdocs.annotation/filetype/htm) { get; } | हाइपरटेक्स्ट मार्कअप लैंग्वेज फ़ाइल। |
| static [Html](../../groupdocs.annotation/filetype/html) { get; } | हाइपरटेक्स्ट मार्कअप लैंग्वेज फ़ाइल। |
| static [Jpeg](../../groupdocs.annotation/filetype/jpeg) { get; } | संयुक्त फोटोग्राफिक विशेषज्ञ समूह। |
| static [Jpg](../../groupdocs.annotation/filetype/jpg) { get; } | संयुक्त फोटोग्राफिक विशेषज्ञ समूह। |
| static [Odp](../../groupdocs.annotation/filetype/odp) { get; } | खुला दस्तावेज़ प्रस्तुति। |
| static [Ods](../../groupdocs.annotation/filetype/ods) { get; } | OpenDocument स्प्रेडशीट दस्तावेज़ प्रारूप |
| static [Odt](../../groupdocs.annotation/filetype/odt) { get; } | दस्तावेज़ टेक्स्ट खोलें. |
| static [Pdf](../../groupdocs.annotation/filetype/pdf) { get; } | एडोब पोर्टेबल दस्तावेज़ स्वरूप. |
| static [Png](../../groupdocs.annotation/filetype/png) { get; } | पोर्टेबल नेटवर्क ग्राफ़िक फ़ाइल. |
| static [Pps](../../groupdocs.annotation/filetype/pps) { get; } | Microsoft PowerPoint स्लाइड शो (लीगेसी). |
| static [Ppsx](../../groupdocs.annotation/filetype/ppsx) { get; } | Microsoft PowerPoint स्लाइड शो. |
| static [Ppt](../../groupdocs.annotation/filetype/ppt) { get; } | Microsoft PowerPoint प्रस्तुति। |
| static [Pptx](../../groupdocs.annotation/filetype/pptx) { get; } | Microsoft PowerPoint ओपन XML प्रस्तुति। |
| static [Rtf](../../groupdocs.annotation/filetype/rtf) { get; } | रिच टेक्स्ट फ़ॉर्मेट फ़ाइल. |
| static [Tif](../../groupdocs.annotation/filetype/tif) { get; } | टैग की गई छवि फ़ाइल. |
| static [Tiff](../../groupdocs.annotation/filetype/tiff) { get; } | टैग की गई छवि फ़ाइल प्रारूप |
| static [Unknown](../../groupdocs.annotation/filetype/unknown) { get; } | अज्ञात। |
| static [Vsd](../../groupdocs.annotation/filetype/vsd) { get; } | Microsoft Visio VSD बाइनरी फ़ॉर्मैट. |
| static [Vsdm](../../groupdocs.annotation/filetype/vsdm) { get; } | Microsoft Visio मैक्रो-सक्षम आरेखण. |
| static [Vsdx](../../groupdocs.annotation/filetype/vsdx) { get; } | Microsoft Visio 2013 VSDX फ़ाइल स्वरूप. |
| static [Vss](../../groupdocs.annotation/filetype/vss) { get; } | Microsoft Visio स्टैंसिल फ़ाइल. |
| static [Vssx](../../groupdocs.annotation/filetype/vssx) { get; } | Microsoft Visio स्टैंसिल फ़ाइल. |
| static [Vst](../../groupdocs.annotation/filetype/vst) { get; } | Microsoft Visio VST बाइनरी टेम्प्लेट फ़ॉर्मैट. |
| static [Vstm](../../groupdocs.annotation/filetype/vstm) { get; } | Microsoft Visio मैक्रो-सक्षम आरेखण टेम्पलेट. |
| static [Vsx](../../groupdocs.annotation/filetype/vsx) { get; } | Microsoft Visio स्टैंसिल XML फ़ाइल. |
| static [Xls](../../groupdocs.annotation/filetype/xls) { get; } | माइक्रोसॉफ्ट एक्सेल स्प्रेडशीट प्रारूप। |
| static [Xlsb](../../groupdocs.annotation/filetype/xlsb) { get; } | एक्सेल बाइनरी फ़ाइल स्वरूप |
| static [Xlsm](../../groupdocs.annotation/filetype/xlsm) { get; } | माइक्रोसॉफ्ट एक्सेल स्प्रेडशीट मैक्रो प्रारूप |
| static [Xlsx](../../groupdocs.annotation/filetype/xlsx) { get; } | माइक्रोसॉफ्ट एक्सेल ओपन एक्सएमएल स्प्रेडशीट. |
| [Extension](../../groupdocs.annotation/filetype/extension) { get; } | फ़ाइल विस्तार |
| [FileFormat](../../groupdocs.annotation/filetype/fileformat) { get; } | फ़ाइल स्वरूप |

## तरीकों

| नाम | विवरण |
| --- | --- |
| static [FromFileNameOrExtension](../../groupdocs.annotation/filetype/fromfilenameorextension)(string) | फ़ाइल नाम या एक्सटेंशन के आधार पर रिटर्न फ़ाइल प्रकार। |
| [Equals](../../groupdocs.annotation/filetype/equals#equals)(FileType) | फ़ाइल प्रकार तुल्यता जाँच. |
| override [Equals](../../groupdocs.annotation/filetype/equals#equals_1)(object) | वस्तु के साथ तुल्यता की जाँच करें। |
| override [GetHashCode](../../groupdocs.annotation/filetype/gethashcode)() | हैश कोड प्राप्त करें. |
| override [ToString](../../groupdocs.annotation/filetype/tostring)() | एक स्ट्रिंग लौटाता है जो फ़ाइल प्रकार का प्रतिनिधित्व करता है। |
| static [GetSupportedFileTypes](../../groupdocs.annotation/filetype/getsupportedfiletypes)() | समर्थित फ़ाइल प्रकार गणना प्राप्त करें। |
| [operator ==](../../groupdocs.annotation/filetype/op_equality) | ऑपरेटर ओवरलोड. |
| [operator !=](../../groupdocs.annotation/filetype/op_inequality) | ऑपरेटर ओवरलोड. |

### यह सभी देखें

* नाम स्थान [GroupDocs.Annotation](../../groupdocs.annotation)
* सभा [GroupDocs.Annotation](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Annotation.dll -->
