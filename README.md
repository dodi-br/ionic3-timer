# ionic3-timer

ionic3によるタイマーアプリ

詳細は以下
http://twosquirrel.mints.ne.jp/?p=16984

## Requirement

- Node.js
- Ionic CLI

## Installation

    $ git clone git@github.com:adash333/ionic3-timer.git
    $ cd ionic3-timer
    $ npm install @ionic/app-scripts@latest --save-dev
    $ npm install

imageは、  
https://www.photo-ac.com/　  
などからダウンロードして、sakura.jpgという名前に変更して、  
www/assets/img/ フォルダの中に保存。(img/　フォルダがなければ新規作成) 　　

    $ ionic serve

androidアプリの作成

    $ ionic platform add android
    $ ionic build android
  
(参考)  
http://twosquirrel.mints.ne.jp/?p=15712  
http://twosquirrel.mints.ne.jp/?p=15745  

## Anything Else

このコードは、以下の本の「Chapter 6 イベントドリブンのきほんを学ぼう」のソースコードを参考に、Ionic3アプリに書き直しています。

これからWebをはじめる人のHTML＆CSS、JavaScriptのきほんのきほん Kindle版  
たにぐち まこと (著)  
発売日：2017年03月27日  
https://www.amazon.co.jp/dp/B06XT19H2D/

## Author

adash333
