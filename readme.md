## 課題
せらく銀行 Webページコーディング

## 使用言語等
- HTML5
- CSS
- jQuery
  -- Slick

##動作確認
- Google Chrome
- Mozilla Firefox
- Internet Explore / 10 11


##ライブラリ等
- [Slick](http://kenwheeler.github.io/slick/)
  -- 画像のスライドショー

- [Flexibility.js](https://github.com/jonathantneal/flexibility)
  -- flexboxに対応させるために利用

- トピックスのタブ切り替えはjQueryのみで対応

##懸念点

###IEへの対応
上記にあるようにFlexibility.jsでflexboxに対応しているはずですが、IE11の機能である仮想ブラウザでのチェックだと正しく動作しませんでした。  
[参考](http://taak.biz/archives/860)によると、実機だと正しく動作するそうですが、まず旧バージョンのブラウザがインストールできませんでした。  
本来であればfloatで実装し直した方が良いと思ったのですが、とりあえず提出しました。  

###文字の大きさ切り替えボタン
jQueryでマウスオーバーで画像の置換を行っていますが、実際の切り替えはできないようになっています。

##反省点

- 概要を読み込んでいなかったので提出直前になって気づいた修正がいくつかあった
- Flexboxの実装についても知識があれば事前にfloatにするかどうか考える余地があったのではないか
- 実機での動作確認ができなかった
