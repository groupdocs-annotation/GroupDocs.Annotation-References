---
title: WatermarkAnnotation
second_title: .NET API संदर्भ के लिए GroupDocs.Annotation
description: वटरमर्क एनटेशन गुणं क प्रतनधत्व करत है
type: docs
weight: 740
url: /hi/net/groupdocs.annotation.models.annotationmodels/watermarkannotation/
---
## WatermarkAnnotation class

वॉटरमार्क एनोटेशन गुणों का प्रतिनिधित्व करता है

```csharp
public class WatermarkAnnotation : AnnotationBase, IEquatable<WatermarkAnnotation>, 
    IWatermarkAnnotation
```

## कंस्ट्रक्टर्स

| नाम | विवरण |
| --- | --- |
| [WatermarkAnnotation](watermarkannotation)() | का नया उदाहरण शुरू करता है[`WatermarkAnnotation`](../watermarkannotation) वर्ग. |

## गुण

| नाम | विवरण |
| --- | --- |
| [Angle](../../groupdocs.annotation.models.annotationmodels/watermarkannotation/angle) { get; set; } | वॉटरमार्क रोटेशन कोण प्राप्त या सेट करता है |
| [AutoScale](../../groupdocs.annotation.models.annotationmodels/watermarkannotation/autoscale) { get; set; } | वॉटरमार्क के लिए ऑटो स्केल सेट करता है |
| [Box](../../groupdocs.annotation.models.annotationmodels/watermarkannotation/box) { get; set; } | एनोटेशन स्थिति प्राप्त या सेट करता है |
| [CreatedOn](../../groupdocs.annotation.models.annotationmodels/annotationbase/createdon) { get; set; } | एनोटेशन निर्माण दिनांक प्राप्त या सेट करता है |
| [FontColor](../../groupdocs.annotation.models.annotationmodels/watermarkannotation/fontcolor) { get; set; } | वॉटरमार्क टेक्स्ट फ़ॉन्ट रंग प्राप्त या सेट करता है |
| [FontFamily](../../groupdocs.annotation.models.annotationmodels/watermarkannotation/fontfamily) { get; set; } | वॉटरमार्क टेक्स्ट फ़ॉन्ट परिवार प्राप्त या सेट करता है |
| [FontSize](../../groupdocs.annotation.models.annotationmodels/watermarkannotation/fontsize) { get; set; } | वॉटरमार्क टेक्स्ट फ़ॉन्ट आकार प्राप्त या सेट करता है |
| [HorizontalAlignment](../../groupdocs.annotation.models.annotationmodels/watermarkannotation/horizontalalignment) { get; set; } | दस्तावेज़ पर वॉटरमार्क क्षैतिज संरेखण प्राप्त या सेट करता है |
| [Id](../../groupdocs.annotation.models.annotationmodels/annotationbase/id) { get; set; } | एनोटेशन अद्वितीय पहचानकर्ता प्राप्त या सेट करता है |
| [Message](../../groupdocs.annotation.models.annotationmodels/annotationbase/message) { get; set; } | एनोटेशन संदेश प्राप्त या सेट करता है |
| [Opacity](../../groupdocs.annotation.models.annotationmodels/watermarkannotation/opacity) { get; set; } | वॉटरमार्क अपारदर्शिता प्राप्त या सेट करता है |
| [PageNumber](../../groupdocs.annotation.models.annotationmodels/annotationbase/pagenumber) { get; set; } | एनोटेट होने के लिए पृष्ठ संख्या प्राप्त या सेट करता है |
| [Replies](../../groupdocs.annotation.models.annotationmodels/annotationbase/replies) { get; set; } | एनोटेशन जवाब संग्रह का प्रतिनिधित्व करता है |
| [Text](../../groupdocs.annotation.models.annotationmodels/watermarkannotation/text) { get; set; } | वॉटरमार्क टेक्स्ट प्राप्त या सेट करता है |
| [Type](../../groupdocs.annotation.models.annotationmodels/annotationbase/type) { get; set; } | एनोटेशन टाइप प्राप्त या सेट करता है |
| [User](../../groupdocs.annotation.models.annotationmodels/annotationbase/user) { get; set; } | एनोटेशन क्रिएटर प्राप्त या सेट करता है |
| [VerticalAlignment](../../groupdocs.annotation.models.annotationmodels/watermarkannotation/verticalalignment) { get; set; } | दस्तावेज़ पर वॉटरमार्क लंबवत संरेखण प्राप्त या सेट करता है |

## तरीकों

| नाम | विवरण |
| --- | --- |
| override [Clone](../../groupdocs.annotation.models.annotationmodels/watermarkannotation/clone)() | समान मानों के साथ नया उदाहरण लौटाता है |
| [Equals](../../groupdocs.annotation.models.annotationmodels/annotationbase/equals)(AnnotationBase) | IEquatable Equals पद्धति का उपयोग करके आधार एनोटेशन की तुलना करता है |
| override [Equals](../../groupdocs.annotation.models.annotationmodels/watermarkannotation/equals#equals_2)(object) | मानक ऑब्जेक्ट बराबर विधि का उपयोग करके वॉटरमार्क एनोटेशन की तुलना करता है |
| [Equals](../../groupdocs.annotation.models.annotationmodels/watermarkannotation/equals#equals_1)(WatermarkAnnotation) | IEquatable Equals विधि का उपयोग करके वॉटरमार्क एनोटेशन की तुलना करता है |
| override [GetHashCode](../../groupdocs.annotation.models.annotationmodels/watermarkannotation/gethashcode)() | वॉटरमार्क एनोटेशन का हैशकोड लौटाता है |

### टिप्पणियों

**और अधिक जानें**

* एनोटेशन प्रकार और पीडीएफ और माइक्रोसॉफ्ट वर्ड दस्तावेज़ों, एक्सेल स्प्रेडशीट्स और पावरपॉइंट प्रस्तुतियों की व्याख्या करने के बारे में अधिक जानकारी: [.NET के लिए GroupDocs.Annotation का उपयोग करके दस्तावेज़ों की व्याख्या कैसे करें](https://docs.groupdocs.com/display/annotationnet/Add+annotation+to+the+document)
* विभिन्न प्रकार के दस्तावेज़ों में वॉटरमार्क एनोटेशन जोड़ने के बारे में अधिक: [सी # में वॉटरमार्क एनोटेशन कैसे जोड़ें](https://docs.groupdocs.com/display/annotationnet/Add+watermark+annotation)

### यह सभी देखें

* class [AnnotationBase](../annotationbase)
* interface [IWatermarkAnnotation](../../groupdocs.annotation.models.annotationmodels.interfaces.annotations/iwatermarkannotation)
* नाम स्थान [GroupDocs.Annotation.Models.AnnotationModels](../../groupdocs.annotation.models.annotationmodels)
* सभा [GroupDocs.Annotation](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Annotation.dll -->
