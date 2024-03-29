---
title: Document
second_title: .NET API 참조용 GroupDocs.Annotation
description: 문서 속성을 나타냅니다
type: docs
weight: 50
url: /ko/net/groupdocs.annotation/document/
---
## Document class

문서 속성을 나타냅니다

```csharp
public class Document
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [Document](document#constructor)(Stream) | 의 새 인스턴스를 초기화합니다.[`Document`](../document) 클래스. |
| [Document](document#constructor_1)(Stream, string) | 의 새 인스턴스를 초기화합니다.[`Document`](../document) 클래스. |

## 속성

| 이름 | 설명 |
| --- | --- |
| [Name](../../groupdocs.annotation/document/name) { get; set; } | 문서 이름 |
| [Password](../../groupdocs.annotation/document/password) { get; } | 문서 암호 |
| [Stream](../../groupdocs.annotation/document/stream) { get; } | 문서 stream |

## 행동 양식

| 이름 | 설명 |
| --- | --- |
| [AddImageToDocument](../../groupdocs.annotation/document/addimagetodocument)(string, string, int, int) | 이미지 품질을 변경하고 document 에 이미지 추가 |
| [GeneratePreview](../../groupdocs.annotation/document/generatepreview)(PreviewOptions) | 문서 페이지 미리보기를 생성합니다. |
| [GetDocumentInfo](../../groupdocs.annotation/document/getdocumentinfo)() | 문서에 대한 정보 가져오기 - 문서 유형 및 크기, 페이지 수 등 |

### 또한보십시오

* 네임스페이스 [GroupDocs.Annotation](../../groupdocs.annotation)
* 집회 [GroupDocs.Annotation](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Annotation.dll -->
