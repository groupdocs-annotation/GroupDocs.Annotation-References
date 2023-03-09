---
title: FileType
second_title: GroupDocs.Annotation for .NET API リファレンス
description: タイプ拡張子などのファイルに関する情報.
type: docs
weight: 120
url: /ja/net/groupdocs.annotation/filetype/
---
## FileType class

タイプ、拡張子などのファイルに関する情報.

```csharp
public sealed class FileType : IEquatable<FileType>
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| static [Bmp](../../groupdocs.annotation/filetype/bmp) { get; } | ビットマップ イメージ ファイル. |
| static [Doc](../../groupdocs.annotation/filetype/doc) { get; } | Microsoft Word 形式. |
| static [Docm](../../groupdocs.annotation/filetype/docm) { get; } | Microsoft Word 2007 マクロ ファイル. |
| static [Docx](../../groupdocs.annotation/filetype/docx) { get; } | Microsoft Word Open XML 形式。 |
| static [Dot](../../groupdocs.annotation/filetype/dot) { get; } | Microsoft Word ドキュメント テンプレート. |
| static [Dotm](../../groupdocs.annotation/filetype/dotm) { get; } | Microsoft Word マクロ有効ドキュメント テンプレート. |
| static [Dotx](../../groupdocs.annotation/filetype/dotx) { get; } | Microsoft Word テンプレート. |
| static [Dwg](../../groupdocs.annotation/filetype/dwg) { get; } | AutoCAD 図面データベース ファイル. |
| static [Dxf](../../groupdocs.annotation/filetype/dxf) { get; } | 図面交換フォーマット ファイル. |
| static [Eml](../../groupdocs.annotation/filetype/eml) { get; } | MIME 標準のファイル。 |
| static [Emlx](../../groupdocs.annotation/filetype/emlx) { get; } | Apple の Mail.app プログラム ファイル形式。 |
| static [Htm](../../groupdocs.annotation/filetype/htm) { get; } | ハイパーテキスト マークアップ言語ファイル. |
| static [Html](../../groupdocs.annotation/filetype/html) { get; } | ハイパーテキスト マークアップ言語ファイル. |
| static [Jpeg](../../groupdocs.annotation/filetype/jpeg) { get; } | 合同写真専門家グループ. |
| static [Jpg](../../groupdocs.annotation/filetype/jpg) { get; } | 合同写真専門家グループ. |
| static [Odp](../../groupdocs.annotation/filetype/odp) { get; } | ドキュメント プレゼンテーションを開く. |
| static [Ods](../../groupdocs.annotation/filetype/ods) { get; } | OpenDocument スプレッドシート ドキュメント format |
| static [Odt](../../groupdocs.annotation/filetype/odt) { get; } | ドキュメント テキストを開く. |
| static [Pdf](../../groupdocs.annotation/filetype/pdf) { get; } | Adobe Portable Document 形式. |
| static [Png](../../groupdocs.annotation/filetype/png) { get; } | ポータブル ネットワーク グラフィック ファイル. |
| static [Pps](../../groupdocs.annotation/filetype/pps) { get; } | Microsoft PowerPoint スライド ショー (レガシー). |
| static [Ppsx](../../groupdocs.annotation/filetype/ppsx) { get; } | Microsoft PowerPoint スライド ショー. |
| static [Ppt](../../groupdocs.annotation/filetype/ppt) { get; } | Microsoft PowerPoint プレゼンテーション. |
| static [Pptx](../../groupdocs.annotation/filetype/pptx) { get; } | Microsoft PowerPoint オープン XML プレゼンテーション. |
| static [Rtf](../../groupdocs.annotation/filetype/rtf) { get; } | リッチテキスト形式ファイル. |
| static [Tif](../../groupdocs.annotation/filetype/tif) { get; } | タグ付き画像ファイル. |
| static [Tiff](../../groupdocs.annotation/filetype/tiff) { get; } | タグ付き画像ファイル形式 |
| static [Unknown](../../groupdocs.annotation/filetype/unknown) { get; } | 不明. |
| static [Vsd](../../groupdocs.annotation/filetype/vsd) { get; } | Microsoft Visio VSD バイナリ形式. |
| static [Vsdm](../../groupdocs.annotation/filetype/vsdm) { get; } | Microsoft Visio マクロ有効図面. |
| static [Vsdx](../../groupdocs.annotation/filetype/vsdx) { get; } | Microsoft Visio 2013 VSDX ファイル形式. |
| static [Vss](../../groupdocs.annotation/filetype/vss) { get; } | Microsoft Visio ステンシル ファイル. |
| static [Vssx](../../groupdocs.annotation/filetype/vssx) { get; } | Microsoft Visio ステンシル ファイル. |
| static [Vst](../../groupdocs.annotation/filetype/vst) { get; } | Microsoft Visio VST バイナリ テンプレート形式. |
| static [Vstm](../../groupdocs.annotation/filetype/vstm) { get; } | Microsoft Visio マクロ有効図面テンプレート. |
| static [Vsx](../../groupdocs.annotation/filetype/vsx) { get; } | Microsoft Visio ステンシル XML ファイル. |
| static [Xls](../../groupdocs.annotation/filetype/xls) { get; } | Microsoft Excel スプレッドシート形式. |
| static [Xlsb](../../groupdocs.annotation/filetype/xlsb) { get; } | Excel バイナリ ファイル形式 |
| static [Xlsm](../../groupdocs.annotation/filetype/xlsm) { get; } | Microsoft Excel スプレッドシート マクロ format |
| static [Xlsx](../../groupdocs.annotation/filetype/xlsx) { get; } | Microsoft Excel Open XML スプレッドシート. |
| [Extension](../../groupdocs.annotation/filetype/extension) { get; } | ファイル拡張子 |
| [FileFormat](../../groupdocs.annotation/filetype/fileformat) { get; } | ファイル形式 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| static [FromFileNameOrExtension](../../groupdocs.annotation/filetype/fromfilenameorextension)(string) | ファイル名または拡張子に基づいて FileType を返します。 |
| [Equals](../../groupdocs.annotation/filetype/equals#equals)(FileType) | ファイルタイプの等価性チェック. |
| override [Equals](../../groupdocs.annotation/filetype/equals#equals_1)(object) | オブジェクトとの等価性チェック. |
| override [GetHashCode](../../groupdocs.annotation/filetype/gethashcode)() | ハッシュコードを取得. |
| override [ToString](../../groupdocs.annotation/filetype/tostring)() | ファイルの種類を表す文字列を返します。 |
| static [GetSupportedFileTypes](../../groupdocs.annotation/filetype/getsupportedfiletypes)() | サポートされているファイル タイプの列挙を取得します。 |
| [operator ==](../../groupdocs.annotation/filetype/op_equality) | オペレーターのオーバーロード。 |
| [operator !=](../../groupdocs.annotation/filetype/op_inequality) | オペレーターのオーバーロード。 |

### 関連項目

* 名前空間 [GroupDocs.Annotation](../../groupdocs.annotation)
* 組み立て [GroupDocs.Annotation](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Annotation.dll -->
