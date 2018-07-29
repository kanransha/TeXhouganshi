# TeXで方眼紙

## できあがり
このスタイルシートを使って夏目漱石の「吾輩は猫である」を書いてみたものが以下
![吾輩は猫である](https://user-images.githubusercontent.com/16703594/43363150-ab030190-9338-11e8-817c-a5d3ccf348ee.png "吾輩は猫である")

## 使い方

読み込まれる位置にhougan.styを配置し，以下のように利用してください。

```tex:usage
\usepackage{hougan}
\begin{hougan}{横の文字数}{縦の文字数}{フォントサイズ}
    \danraku{段落ごとにここに記入していきます。}
    \danraku{段落のはじめは改行され，字下げされます。}
\end{hougan}
```

## 機能

* 美しい方眼紙が描かれ，5文字ごとに枠ができる
* 段落ごとに字下げされる
* 数字と英語の小文字は2文字で1マスになる
* 句読点は。と、に統一され，綺麗な位置に
* 鉤括弧閉じは句読点と同じマスに置かれる
* 文頭に句読点が来ないように位置が調整される
* 文頭に鉤括弧閉じがこないように調整される

## ファイルの説明

<dl>
  <dt>hougan.sty</dt>
    <dd>スタイルシート本体</dd>
  <dt>kokoro.tex</dt>
    <dd>夏目漱石の「こころ」の1ページをこのスタイルシートで書いてみたもの</dd>
  <dt>kokoro.pdf</dt>
    <dd>夏目漱石の「こころ」の1ページをこのスタイルシートで書いてみたもの</dd>
</dl> 