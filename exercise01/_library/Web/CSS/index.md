---
title: "ページの装飾"
permalink: /Web/ページの装飾/
date: 2019-11-13
---
HTMLで作った文章は、CSSで装飾していきます。
CSSはhtmlとは別のファイルに書いていきます。index.htmlファイルと同じフォルダに、main.cssというファイルを作ってください。このファイルをindex.htmlファイルから読み込むために、headタグの中に  `<link rel="stylesheet" type="text/css" href="main.css">`を挿入します。

<pre class="pre-scrollable">
body {
    width: 1170px;
    margin-right:auto;
    margin-left:auto;
    padding-left:15px;
    padding-right:15px;
}
h1 {
    font-size: 3em;
    font-family:'Helvetica', 'Arial', 'Sans-Serif';
}
p {
    font-size: 1.5em;
    line-height: 1.4em;
    color: #333;
}
</pre>
出力結果は<a href="../CSS/exercise.html">この</a>ようになると思います。以下、CSSについて説明していきます。
## CSSのルール
```
h1 {font-size: 3em;}
```
CSSの基本的なルールは、
- h1はセレクターと言ってCSSが適用される箇所を指定する
- font-sizeはプロパティと言って適用するCSSの種類を決める。
- 3emはCSSの値を表す。

## セレクタ
HTML文書なかのある部分を指定するには、セレクタを使います。
### 要素型セレクタ

### Classセレクタ
指定されたクラス属性を持つすべての要素を選択する。
.class名 {}
### IDセレクタ

## プロパティ



## 参考文献
[w3schools.com/CSS Tutorial](https://www.w3schools.com/css/default.asp)  
[MDN web docs/CSS セレクター](https://developer.mozilla.org/ja/docs/Web/CSS/CSS_Selectors)  
[MDN web docs/CSS: カスケーディングスタイルシート](https://developer.mozilla.org/ja/docs/Web/CSS)  