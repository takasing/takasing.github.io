---
layout: post
title: Jekyll Nowでブログ始めてみる
---

## やったこと
1. [jekyll-now](https://github.com/barryclark/jekyll-now)をfork
1. Settingsでリポジトリ名を**$username.github.io**に変更
1. ```_config.yml```を編集

## 記事の書き方
普通にMarkdownで書く

## 画像の使い方
![松中フライング]({{ site.baseurl }}/images/matsunaka_flying.gif)  
```
![alt here]({{ site.baseurl }}/images/画像ファイル名)
```  
すでに画像用ディレクトリ掘られてるっぽいのでそれを利用したらよさそう。

## 感想
構築めちゃ楽だった。  
markdownを本気で書いたこと無いのでこのブログで色々更新するのも有りかな。

## 参考
* [クリック1発で、Github上にブログを無料で作成できる「Jekyll Now」が超絶便利！](http://plus.appgiga.jp/masatolan/2015/01/13/55047/)

## 追記
1. GoogleAnalyticsの設定を入れた。```_config.yml```にプロパティIDを書くだけ。
1. コメントフォームを追加した。```_config.yml```のdisqusにdisqusで取得したshortnameを書くだけ。  
disqusではユーザー登録した後、サイトを登録したらshortnameが取得できる。
