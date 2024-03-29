---
title: AnnotationType
second_title: .NET API 참조용 GroupDocs.Annotation
description: .NET 에 대한 GroupDocs.Annotation에서 지원하는 주석 유형을 설명하는 열거
type: docs
weight: 960
url: /ko/net/groupdocs.annotation.options/annotationtype/
---
## AnnotationType enumeration

.NET 에 대한 GroupDocs.Annotation에서 지원하는 주석 유형을 설명하는 열거

```csharp
[Flags]
public enum AnnotationType
```

### 가치

| 이름 | 값 | 설명 |
| --- | --- | --- |
| None | `0` | 기본값 |
| Area | `2` | 문서 page 내의 사각형 영역을 강조 표시하는 영역 주석 유형 |
| Arrow | `4` | 문서 page 에 화살표를 그리는 주석 유형 |
| Distance | `8` | 문서 페이지의 요소 간 거리를 측정하는 주석 유형 |
| Ellipse | `10` | 문서 내용 의 일부를 표시하는 타원형 주석 |
| Link | `20` | 원격 리소스 에 대한 하이퍼링크를 나타내는 주석 유형 |
| Point | `40` | 문서 page 내 임의의 위치에 주석을 붙이는 포인트 주석 유형 |
| Polyline | `80` | 문서 page 에 그림 모양과 자유형 선을 추가할 수 있는 폴리라인 주석 유형 |
| ResourcesRedaction | `100` | 검은색 사각형 뒤에 텍스트 내용을 숨기는 주석 유형 |
| TextField | `200` | 텍스트 필드 주석 유형은 컬러 프레임 내부의 텍스트 주석을 나타냅니다. |
| TextHighlight | `400` | 선택한 텍스트를 강조 표시하고 주석을 추가하는 주석 유형 text |
| TextRedaction | `800` | 선택한 텍스트의 일부를 검은색 사각형으로 채우는 주석 유형입니다. |
| TextReplacement | `1000` | 원본 텍스트를 제공된 다른 텍스트로 대체하는 주석 유형 fragment |
| TextStrikeout | `2000` | 텍스트 조각에 취소선을 표시하는 주석 유형 styling |
| TextUnderline | `4000` | 밑줄로 텍스트를 표시하는 주석 유형 styling |
| Watermark | `8000` | 문서 page 에 텍스트 워터마크를 추가하는 주석 유형 |
| Image | `10000` | 문서 페이지 content 위에 이미지 오버레이를 추가하는 주석 유형 |
| Dropdown | `20000` | PDF 문서에 대한 드롭다운 구성 요소를 추가하는 구성 요소 유형**오직** |
| Checkbox | `21000` | pdf document 에 대한 확인란을 추가하는 주석 유형 |
| Button | `22000` | pdf document 에 대한 버튼을 추가하는 주석 유형 |
| TextSquiggly | `2500` | 구불구불하고 주석이 선택된 주석 유형 text |
| SearchText | `2700` | document 에서 조각 텍스트를 검색하는 주석 유형 |
| All | `7FFFFFFF` | 모든 |

### 비고

**더 알아보기**

* [C#에서 문서에 주석을 다는 방법](https://docs.groupdocs.com/display/annotationnet/Add+annotation+to+the+document)
* [C#에서 영역 주석을 추가하는 방법](https://docs.groupdocs.com/display/annotationnet/Add+area+annotation)
* [C#에서 화살표 주석을 추가하는 방법](https://docs.groupdocs.com/display/annotationnet/Add+arrow+annotation)
* [C#에서 거리 주석을 추가하는 방법](https://docs.groupdocs.com/display/annotationnet/Add+distance+annotation)
* [C#에서 타원 주석을 추가하는 방법](https://docs.groupdocs.com/display/annotationnet/Add+ellipse+annotation)
* [C#에서 링크 주석을 추가하는 방법](https://docs.groupdocs.com/display/annotationnet/Add+link+annotation)
* [C#에서 점 주석을 추가하는 방법](https://docs.groupdocs.com/display/annotationnet/Add+point+annotation)
* [C#에서 다중선 주석을 추가하는 방법](https://docs.groupdocs.com/display/annotationnet/Add+polyline+annotation)
* [C#에서 리소스 수정 주석을 추가하는 방법](https://docs.groupdocs.com/display/annotationnet/Add+resource+redaction+annotation)
* [C#에서 텍스트 필드 주석을 추가하는 방법](https://docs.groupdocs.com/display/annotationnet/Add+text+field+annotation)
* [C#에서 하이라이트 주석을 추가하는 방법](https://docs.groupdocs.com/display/annotationnet/Add+highlight+annotation)
* [C#에서 텍스트 편집 주석을 추가하는 방법](https://docs.groupdocs.com/display/annotationnet/Add+text+redaction+annotation)
* [C#에서 대체 주석을 추가하는 방법](https://docs.groupdocs.com/display/annotationnet/Add+replacement+annotation)
* [C#에서 취소선 주석을 추가하는 방법](https://docs.groupdocs.com/display/annotationnet/Add+strikeout+annotation)
* [C#에서 밑줄 주석을 추가하는 방법](https://docs.groupdocs.com/display/annotationnet/Add+underline+annotation)
* [C#에서 워터마크 주석을 추가하는 방법](https://docs.groupdocs.com/display/annotationnet/Add+watermark+annotation)
* [C#에서 이미지 주석을 추가하는 방법](https://docs.groupdocs.com/display/annotationnet/Add+image+annotation)

### 또한보십시오

* 네임스페이스 [GroupDocs.Annotation.Options](../../groupdocs.annotation.options)
* 집회 [GroupDocs.Annotation](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Annotation.dll -->
