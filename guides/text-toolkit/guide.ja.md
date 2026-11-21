---
title: 文字数カウント：Text Toolkit
name: Text Toolkit
tagline: 文字数カウント、大文字小文字の変換、整形、並べ替え、比較をオフラインで。
project: text-toolkit
package: io.github.varian1.texttoolkit
version: 1.0
updated: 2026-11-18
privacy: https://varian1.github.io/text-toolkit/privacy.html
---

## What it does

Text Toolkit は、9つのテキストツールが1つの画面にまとまったアプリです。上のボックスに文字を入力するか貼り付けて、ツールを選び、結果をコピーまたは共有します。文字数や単語数のカウント、大文字小文字の変換、空白の整理、行の並べ替え、検索と置換、反転、エンコード、JSON の整形、2つのテキストの比較ができます。

- すべてのツールは端末の中で動き、インターネットなしで使えます。
- アカウントは不要です。テキストはアップロードされません。カメラ、写真、連絡先、位置情報も使いません。
- テキストは保存されません。アプリを閉じると消えます。
- 無料です。画面の下にバナー広告が表示されることがあります。

## Get started

1. Text Toolkit を開きます。**YOUR TEXT** ボックスには短いサンプルが入っているので、各ツールをすぐに試せます。
2. **Clear** をタップして自分のテキストを入力するか、**Paste** をタップして、ほかのアプリでコピーした内容に置き換えます。**Sample** をタップすると、サンプルのテキストに戻ります。
3. ボックスの下の列からツールを選びます。**Counter**、**Case**、**Clean**、**Lines**、**Replace**、**Reverse**、**Encode**、**Format**、**Diff** があります。列を横にスワイプすると、すべて表示できます。

![メイン画面：Paste、Sample、Clear が付いた YOUR TEXT ボックス、ツールの列、Counter の数値](shots/01-home.png)

アプリはスマートフォンの言語設定に合わせて表示されます。対応言語は11言語で、英語、スペイン語、ポルトガル語、ドイツ語、フランス語、ヒンディー語、インドネシア語、アラビア語、イタリア語、ロシア語、トルコ語です。

## Count words and characters

1. **Counter** をタップします。
2. 数値を確認します。**Characters**、**No spaces**、**Words**、**Sentences**、**Paragraphs**、**Lines**、**Reading time** が表示されます。
3. 下の **TOP WORDS** で、よく使った単語を最大8つまで、回数と一緒に確認できます。

数値は入力に合わせて変わります。Reading time は1分あたり200語で計算されます。

## Change the letter case

1. **Case** をタップします。
2. カードをスクロールします。それぞれのカードに、テキストが別のスタイルで表示されます。**UPPERCASE**、**lowercase**、**Title Case**、**Sentence case**、**Capitalized Case**、**aLtErNaTiNg**、**iNVERSE**、**camelCase**、**PascalCase**、**snake_case**、**kebab-case**、**CONSTANT_CASE**、**URL slug** があります。
3. 使いたいカードの **Copy** をタップします。

![Case ツール：UPPERCASE、lowercase、Title Case のカード。それぞれに Use input、Share、Copy が付いています](shots/02-case.png)

## Clean up text

1. **Clean** をタップします。
2. 操作を1つタップします。
   - **Clean all**：タブ、連続した空白、行末の空白、空行、重複した行をまとめて削除します。
   - **Extra spaces**、**Trim lines**、**No empty lines**、**No duplicates**、**Remove tabs**：それぞれ、その1つだけを行います。
   - 改行の操作：テキストから改行を削除します。
3. 結果は **CLEANED RESULT** の下に表示されます。ボックスに入力したテキストはそのまま残ります。

![Clean ツール：整理のボタンと CLEANED RESULT カード](shots/03-clean.png)

## Sort or reverse

1. 行ごとに処理するには **Lines** をタップします。**A to Z**、**Z to A**、**Reverse lines**、**Shortest first**、**No duplicates**、**Reverse characters** があります。並べ替えでは、大文字小文字と行頭の空白は無視されます。
2. テキストを反転するには **Reverse** をタップします。**Entire text**、**Each word**、**Word order**、**Line order**、**Characters per line** があります。
3. 結果はボタンの下のカードに表示されます。

## Find and replace

1. **Replace** をタップします。
2. **Find** に探すテキストを、**Replace with** に新しいテキストを入力します。
3. オプションをタップして、オンとオフを切り替えます。**Replace all**（オフにすると最初の一致だけを変更）、**Case sensitive**、**Whole word** があります。
4. 置換の件数と **REPLACEMENT PREVIEW** を確認します。どちらも入力に合わせて更新されます。

![Replace ツール：Find と Replace with の入力欄、3つのオプションボタン、置換の件数、プレビュー](shots/04-replace.png)

検索は、入力したとおりの文字列を探します。パターンやワイルドカードは使えません。

## Encode, decode and format

1. **Encode** をタップし、**URL**、**Base64**、**HTML Entities** のいずれかを選んでから、**Encode** または **Decode** をタップします。
2. **Format** をタップして、**Format JSON**（JSON を半角スペース2つでインデント）、**Minify JSON**（JSON を1行にまとめる）、**Strip Markdown**（Markdown をプレーンテキストにする）のいずれかを選びます。
3. JSON に誤りがあると、画面の上のほうに "Invalid JSON" で始まる行が表示され、何が間違っているかを教えてくれます。

## Compare two texts

1. 最初のバージョンを **YOUR TEXT** に入れて、**Diff** をタップします。
2. 2つ目のバージョンを **COMPARE WITH** に入力するか貼り付けます。
3. **DIFF COMPARISON** を確認します。2つ目にだけある行は緑色で **+** が付きます。最初のほうにだけある行は赤色で **-** が付きます。一致する行には印が付きません。
4. **Copy Diff** をタップすると、+ と - の印が付いたまま比較結果をコピーできます。

![Diff ツール：COMPARE WITH ボックスと、追加された緑の行1つ、削除された赤の行1つが表示された DIFF COMPARISON カード](shots/05-diff.png)

## Copy, share or keep working

1. 結果カードの **Copy** をタップすると、クリップボードにコピーされます。
2. **Share** をタップすると、ほかのアプリに送れます。
3. **Use input** をタップすると、結果が **YOUR TEXT** に移るので、そのテキストに別のツールを使えます。

## Premium

すべてのツールは無料です。広告を消すための買い切りの購入(任意)が1つあります。支払いは1回だけで、サブスクリプションではありません。

## Questions

**オフラインでも使えますか？**
はい。9つのツールはすべて端末の中で動きます。ネットワークを使うのは、広告と、広告を消す購入だけです。

**入力したテキストは保存されますか？**
いいえ。アプリはテキストを、開いている間だけ保持します。残したい結果は、コピーまたは共有してください。

**ツールを切り替えたら結果が空になったのはなぜですか？**
Clean、Lines、Reverse、Encode、Format は1つの結果カードを共有していて、ツールを切り替えるとクリアされます。もう一度操作をタップしてください。テキストを編集したあとも同じです。Counter、Case、Replace、Diff は自動で更新されます。

**ダークモードに対応していますか？**
はい。スマートフォンで設定しているライトまたはダークのテーマに合わせます。

**ライセンスはどこで見られますか？**
画面の一番下までスクロールして、**Open-source licenses** をタップします。**Privacy policy** はその隣にあります。

## Privacy

テキストは端末の中で処理され、アップロードも保存もされません。アプリには Google AdMob の広告が表示されることがあります。法律で必要な場合は、最初に選択を求められ、あとからメイン画面の **Ad privacy choices** で変更できます。詳しくは[プライバシーポリシー](https://varian1.github.io/text-toolkit/privacy.html)をご覧ください。
