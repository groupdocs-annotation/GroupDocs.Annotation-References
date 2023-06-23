---
title: ReplacementAnnotation
second_title: .NET API 참조용 GroupDocs.Annotation
description: 대체 주석 properties 를 나타냅니다.
type: docs
weight: 660
url: /ko/net/groupdocs.annotation.models.annotationmodels/replacementannotation/
---
## ReplacementAnnotation class

대체 주석 properties 를 나타냅니다.

```csharp
public class ReplacementAnnotation : AnnotationBase, IEquatable<ReplacementAnnotation>, 
    IReplacementAnnotation
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [ReplacementAnnotation](replacementannotation)() | 의 새 인스턴스를 초기화합니다.[`ReplacementAnnotation`](../replacementannotation) 클래스. |

## 속성

| 이름 | 설명 |
| --- | --- |
| [CreatedOn](../../groupdocs.annotation.models.annotationmodels/annotationbase/createdon) { get; set; } | 주석 생성 날짜 를 가져오거나 설정합니다. |
| [FontColor](../../groupdocs.annotation.models.annotationmodels/replacementannotation/fontcolor) { get; set; } | 주석 텍스트 글꼴 color 를 가져오거나 설정합니다. |
| [FontSize](../../groupdocs.annotation.models.annotationmodels/replacementannotation/fontsize) { get; set; } | 주석 텍스트 글꼴 크기를 가져오거나 설정합니다. |
| [Id](../../groupdocs.annotation.models.annotationmodels/annotationbase/id) { get; set; } | 주석 고유 식별자를 가져오거나 설정합니다. |
| [Message](../../groupdocs.annotation.models.annotationmodels/annotationbase/message) { get; set; } | 주석 message 를 가져오거나 설정합니다. |
| [Opacity](../../groupdocs.annotation.models.annotationmodels/replacementannotation/opacity) { get; set; } | 주석 opacity 를 가져오거나 설정합니다. |
| [PageNumber](../../groupdocs.annotation.models.annotationmodels/annotationbase/pagenumber) { get; set; } | annotated 할 페이지 번호를 가져오거나 설정합니다. |
| [Points](../../groupdocs.annotation.models.annotationmodels/replacementannotation/points) { get; set; } | text 로 사각형을 설명하는 점 모음을 가져오거나 설정합니다. |
| [Replies](../../groupdocs.annotation.models.annotationmodels/annotationbase/replies) { get; set; } | 주석 응답을 나타냅니다. collection |
| [TextToReplace](../../groupdocs.annotation.models.annotationmodels/replacementannotation/texttoreplace) { get; set; } | 바꿀 텍스트를 가져오거나 설정합니다 |
| [Type](../../groupdocs.annotation.models.annotationmodels/annotationbase/type) { get; set; } | 주석 type 를 가져오거나 설정합니다. |
| [User](../../groupdocs.annotation.models.annotationmodels/annotationbase/user) { get; set; } | 주석 creator 를 가져오거나 설정합니다. |

## 행동 양식

| 이름 | 설명 |
| --- | --- |
| override [Clone](../../groupdocs.annotation.models.annotationmodels/replacementannotation/clone)() | 동일한 values 를 가진 새 인스턴스를 반환합니다. |
| [Equals](../../groupdocs.annotation.models.annotationmodels/annotationbase/equals)(AnnotationBase) | IEquatable Equals method 를 사용하여 기본 주석을 비교합니다. |
| override [Equals](../../groupdocs.annotation.models.annotationmodels/replacementannotation/equals#equals_2)(object) | 표준 개체 Equals method 를 사용하여 대체 주석을 비교합니다. |
| [Equals](../../groupdocs.annotation.models.annotationmodels/replacementannotation/equals#equals_1)(ReplacementAnnotation) | IEquatable Equals method 를 사용하여 대체 주석을 비교합니다. |
| override [GetHashCode](../../groupdocs.annotation.models.annotationmodels/replacementannotation/gethashcode)() | 교체 Annotation 의 해시 코드를 반환합니다. |

### 비고

**더 알아보기**

* 주석 유형 및 PDF 및 Microsoft Word 문서, Excel 스프레드시트 및 PowerPoint 프리젠테이션에 주석 추가: [.NET용 GroupDocs.Annotation을 사용하여 문서에 주석을 추가하는 방법](https://docs.groupdocs.com/display/annotationnet/Add+annotation+to+the+document)
* 다양한 유형의 문서에 대체 주석을 추가하는 방법에 대해 자세히 알아보기: [C#에서 대체 주석을 추가하는 방법](https://docs.groupdocs.com/display/annotationnet/Add+replacement+annotation)

### 또한보십시오

* class [AnnotationBase](../annotationbase)
* interface [IReplacementAnnotation](../../groupdocs.annotation.models.annotationmodels.interfaces.annotations/ireplacementannotation)
* 네임스페이스 [GroupDocs.Annotation.Models.AnnotationModels](../../groupdocs.annotation.models.annotationmodels)
* 집회 [GroupDocs.Annotation](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Annotation.dll -->