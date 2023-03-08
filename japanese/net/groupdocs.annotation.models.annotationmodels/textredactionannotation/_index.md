---
title: TextRedactionAnnotation
second_title: GroupDocs.Annotation for .NET API リファレンス
description: テキスト編集注釈プロパティを表します
type: docs
weight: 720
url: /ja/net/groupdocs.annotation.models.annotationmodels/textredactionannotation/
---
## TextRedactionAnnotation class

テキスト編集注釈プロパティを表します

```csharp
public class TextRedactionAnnotation : AnnotationBase, IEquatable<TextRedactionAnnotation>, 
    ITextRedactionAnnotation
```

## コンストラクター

| 名前 | 説明 |
| --- | --- |
| [TextRedactionAnnotation](textredactionannotation)() | の新しいインスタンスを初期化します[`TextRedactionAnnotation`](../textredactionannotation)class. |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [CreatedOn](../../groupdocs.annotation.models.annotationmodels/annotationbase/createdon) { get; set; } | 注釈の作成日を取得または設定します |
| [FontColor](../../groupdocs.annotation.models.annotationmodels/textredactionannotation/fontcolor) { get; set; } | 注釈テキストのフォントを取得または設定します color |
| [Id](../../groupdocs.annotation.models.annotationmodels/annotationbase/id) { get; set; } | 注釈の一意の識別子を取得または設定します |
| [Message](../../groupdocs.annotation.models.annotationmodels/annotationbase/message) { get; set; } | 注釈メッセージを取得または設定します |
| [PageNumber](../../groupdocs.annotation.models.annotationmodels/annotationbase/pagenumber) { get; set; } | 注釈を付けるページ番号を取得または設定します |
| [Points](../../groupdocs.annotation.models.annotationmodels/textredactionannotation/points) { get; set; } | text で四角形を表すポイントのコレクションを取得または設定します |
| [Replies](../../groupdocs.annotation.models.annotationmodels/annotationbase/replies) { get; set; } | 注釈の返信を表します collection |
| [Type](../../groupdocs.annotation.models.annotationmodels/annotationbase/type) { get; set; } | 注釈 type を取得または設定します |
| [User](../../groupdocs.annotation.models.annotationmodels/annotationbase/user) { get; set; } | 注釈を取得または設定します Creator |

## メソッド

| 名前 | 説明 |
| --- | --- |
| override [Clone](../../groupdocs.annotation.models.annotationmodels/textredactionannotation/clone)() | 同じ値を持つ新しいインスタンスを返します |
| [Equals](../../groupdocs.annotation.models.annotationmodels/annotationbase/equals)(AnnotationBase) | IEquatable Equals メソッドを使用してベース アノテーションを比較します |
| override [Equals](../../groupdocs.annotation.models.annotationmodels/textredactionannotation/equals#equals_2)(object) | 標準オブジェクト Equals メソッドを使用してテキスト編集注釈を比較します |
| [Equals](../../groupdocs.annotation.models.annotationmodels/textredactionannotation/equals#equals_1)(TextRedactionAnnotation) | IEquatable Equals メソッドを使用してテキスト編集注釈を比較します |
| override [GetHashCode](../../groupdocs.annotation.models.annotationmodels/textredactionannotation/gethashcode)() | テキスト編集注釈の HashCode を返します |

### 備考

**もっと詳しく知る**

* 注釈の種類と、PDF および Microsoft Word ドキュメント、Excel スプレッドシート、PowerPoint プレゼンテーションへの注釈の詳細: [GroupDocs.Annotation for .NET を使用してドキュメントに注釈を付ける方法](https://docs.groupdocs.com/display/annotationnet/Add+annotation+to+the+document)
* さまざまなタイプのドキュメントへのテキスト編集注釈の追加の詳細: [C# でテキスト リダクション アノテーションを追加する方法](https://docs.groupdocs.com/display/annotationnet/Add+text+redaction+annotation)

### 関連項目

* class [AnnotationBase](../annotationbase)
* interface [ITextRedactionAnnotation](../../groupdocs.annotation.models.annotationmodels.interfaces.annotations/itextredactionannotation)
* 名前空間 [GroupDocs.Annotation.Models.AnnotationModels](../../groupdocs.annotation.models.annotationmodels)
* 組み立て [GroupDocs.Annotation](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Annotation.dll -->