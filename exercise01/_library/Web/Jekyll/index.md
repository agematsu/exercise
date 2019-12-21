---
title: "Jekyll"
permalink: /Web/Jekyll/
---
[Jekyll](https://jekyllrb.com/)は静的サイトジェネレータのうちの一つで、大体のことは[この](https://jekyllrb.com/docs/)チュートリアルを見ればわかります。 


## はじめに
JekyllはRubyの上で動くので、まずRubyをインストールする必要があります。  
つぎに、Jekyllをインストールします。

```
gem install jekyll
```  
<!--Tips Bundler

-->
これで一応の準備は整ったので、ブログを作ってみましょう。
```
Jekyll new myblog --blank
```  
これで、ホームディレクトリにmyblogフォルダが作られました。  
このmyblogフォルダをVSCodeで開いてみると、次のようになると思います。

<img src="../Jekyll/myblog.png" width="500" height="300">  
ブログを開くには、VSCodeからターミナルを開いて、
```
Jekyll serve
```
と入力し、ブラウザで**[http://127.0.0.1:4000](http://127.0.0.1:4000)**を開くと、次のようなブログ?が表示されます。

<img src="../Jekyll/myblog_output.png" width="500" height="300">  

## テンプレートの読み込み

##  参考文献
[Webjeda](https://blog.webjeda.com/tags/)  
[Jekyll](https://jekyllrb.com)  
[Jekyll[日本語]](https://jekyllrb-ja.github.io/)  
[New option: create a blank site, without a template by default #5260](https://github.com/jekyll/jekyll/issues/5260)