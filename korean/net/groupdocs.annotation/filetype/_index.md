---
title: FileType
second_title: .NET API 참조용 GroupDocs.Annotation
description: 유형 확장자 등과 같은 파일에 대한 정보
type: docs
weight: 120
url: /ko/net/groupdocs.annotation/filetype/
---
## FileType class

유형, 확장자 등과 같은 파일에 대한 정보

```csharp
public sealed class FileType : IEquatable<FileType>
```

## 속성

| 이름 | 설명 |
| --- | --- |
| static [Bmp](../../groupdocs.annotation/filetype/bmp) { get; } | 비트맵 이미지 파일. |
| static [Doc](../../groupdocs.annotation/filetype/doc) { get; } | 마이크로소프트 워드 형식. |
| static [Docm](../../groupdocs.annotation/filetype/docm) { get; } | Microsoft Word 2007 매크로 파일. |
| static [Docx](../../groupdocs.annotation/filetype/docx) { get; } | Microsoft Word Open XML 형식. |
| static [Dot](../../groupdocs.annotation/filetype/dot) { get; } | Microsoft Word 문서 템플릿. |
| static [Dotm](../../groupdocs.annotation/filetype/dotm) { get; } | Microsoft Word 매크로 사용 문서 템플릿. |
| static [Dotx](../../groupdocs.annotation/filetype/dotx) { get; } | 마이크로소프트 워드 템플릿. |
| static [Dwg](../../groupdocs.annotation/filetype/dwg) { get; } | AutoCAD 드로잉 데이터베이스 파일. |
| static [Dxf](../../groupdocs.annotation/filetype/dxf) { get; } | 도면 교환 형식 파일. |
| static [Eml](../../groupdocs.annotation/filetype/eml) { get; } | MIME 표준 파일. |
| static [Emlx](../../groupdocs.annotation/filetype/emlx) { get; } | Apple의 Mail.app 프로그램 파일 형식. |
| static [Htm](../../groupdocs.annotation/filetype/htm) { get; } | 하이퍼텍스트 마크업 언어 파일. |
| static [Html](../../groupdocs.annotation/filetype/html) { get; } | 하이퍼텍스트 마크업 언어 파일. |
| static [Jpeg](../../groupdocs.annotation/filetype/jpeg) { get; } | 공동 사진 전문가 그룹. |
| static [Jpg](../../groupdocs.annotation/filetype/jpg) { get; } | 공동 사진 전문가 그룹. |
| static [Odp](../../groupdocs.annotation/filetype/odp) { get; } | 문서 프레젠테이션 열기. |
| static [Ods](../../groupdocs.annotation/filetype/ods) { get; } | OpenDocument 스프레드시트 문서 format |
| static [Odt](../../groupdocs.annotation/filetype/odt) { get; } | 문서 텍스트 열기. |
| static [Pdf](../../groupdocs.annotation/filetype/pdf) { get; } | Adobe 휴대용 문서 형식. |
| static [Png](../../groupdocs.annotation/filetype/png) { get; } | 휴대용 네트워크 그래픽 파일. |
| static [Pps](../../groupdocs.annotation/filetype/pps) { get; } | Microsoft PowerPoint 슬라이드 쇼(레거시). |
| static [Ppsx](../../groupdocs.annotation/filetype/ppsx) { get; } | Microsoft PowerPoint 슬라이드 쇼. |
| static [Ppt](../../groupdocs.annotation/filetype/ppt) { get; } | Microsoft PowerPoint 프레젠테이션. |
| static [Pptx](../../groupdocs.annotation/filetype/pptx) { get; } | Microsoft PowerPoint Open XML 프레젠테이션. |
| static [Rtf](../../groupdocs.annotation/filetype/rtf) { get; } | 리치 텍스트 형식 파일. |
| static [Tif](../../groupdocs.annotation/filetype/tif) { get; } | 태그가 지정된 이미지 파일. |
| static [Tiff](../../groupdocs.annotation/filetype/tiff) { get; } | 태그가 지정된 이미지 파일 형식 |
| static [Unknown](../../groupdocs.annotation/filetype/unknown) { get; } | 알 수 없음. |
| static [Vsd](../../groupdocs.annotation/filetype/vsd) { get; } | Microsoft Visio VSD 바이너리 형식. |
| static [Vsdm](../../groupdocs.annotation/filetype/vsdm) { get; } | Microsoft Visio 매크로 사용 도면. |
| static [Vsdx](../../groupdocs.annotation/filetype/vsdx) { get; } | Microsoft Visio 2013 VSDX 파일 형식. |
| static [Vss](../../groupdocs.annotation/filetype/vss) { get; } | Microsoft Visio 스텐실 파일. |
| static [Vssx](../../groupdocs.annotation/filetype/vssx) { get; } | Microsoft Visio 스텐실 파일. |
| static [Vst](../../groupdocs.annotation/filetype/vst) { get; } | Microsoft Visio VST 바이너리 템플릿 형식. |
| static [Vstm](../../groupdocs.annotation/filetype/vstm) { get; } | Microsoft Visio 매크로 사용 드로잉 템플릿. |
| static [Vsx](../../groupdocs.annotation/filetype/vsx) { get; } | Microsoft Visio 스텐실 XML 파일. |
| static [Xls](../../groupdocs.annotation/filetype/xls) { get; } | Microsoft Excel 스프레드시트 형식. |
| static [Xlsb](../../groupdocs.annotation/filetype/xlsb) { get; } | Excel 이진 파일 형식 |
| static [Xlsm](../../groupdocs.annotation/filetype/xlsm) { get; } | Microsoft Excel 스프레드시트 매크로 format |
| static [Xlsx](../../groupdocs.annotation/filetype/xlsx) { get; } | Microsoft Excel Open XML 스프레드시트. |
| [Extension](../../groupdocs.annotation/filetype/extension) { get; } | 파일 확장자 |
| [FileFormat](../../groupdocs.annotation/filetype/fileformat) { get; } | 파일 형식 |

## 행동 양식

| 이름 | 설명 |
| --- | --- |
| static [FromFileNameOrExtension](../../groupdocs.annotation/filetype/fromfilenameorextension)(string) | 파일 이름 또는 확장자에 따라 FileType을 반환합니다. |
| [Equals](../../groupdocs.annotation/filetype/equals#equals)(FileType) | 파일 형식 동등성 검사. |
| override [Equals](../../groupdocs.annotation/filetype/equals#equals_1)(object) | 개체와의 동등성 검사. |
| override [GetHashCode](../../groupdocs.annotation/filetype/gethashcode)() | 해시 코드를 가져옵니다. |
| override [ToString](../../groupdocs.annotation/filetype/tostring)() | 파일 형식을 나타내는 문자열을 반환합니다. |
| static [GetSupportedFileTypes](../../groupdocs.annotation/filetype/getsupportedfiletypes)() | 지원되는 파일 형식 열거를 가져옵니다. |
| [operator ==](../../groupdocs.annotation/filetype/op_equality) | 운영자 과부하. |
| [operator !=](../../groupdocs.annotation/filetype/op_inequality) | 운영자 과부하. |

### 또한보십시오

* 네임스페이스 [GroupDocs.Annotation](../../groupdocs.annotation)
* 집회 [GroupDocs.Annotation](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Annotation.dll -->
