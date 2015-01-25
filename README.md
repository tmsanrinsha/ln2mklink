Note
====

わざわざラッパーを書かなくても、環境変数CYGWINにwinsymlinksを設定することで Cygwinのln -sコマンドをWindowsのシンボリックリンク作成コマンドへ変更することができるらしい。

* [Cygwin内外でリンクを共有する](http://rcmdnk.github.io/blog/2013/06/25/computer-windows-cygwin/)

Usage
=====

```
$ mkdir -p ~/bin
$ curl -L https://raw.github.com/tmsanrinsha/ln2mklink/master/ln > ~/bin/ln
$ chmod a+x ~/bin/ln
$ export PATH="$HOME/bin:$PATH"
```

Link
=====

* [Cygwinのlnをmklinkに変換するスクリプト | SanRin舎](http://sanrinsha.lolipop.jp/blog/2012/09/cygwin%e3%81%aeln%e3%82%92mklink%e3%81%ab%e5%a4%89%e6%8f%9b%e3%81%99%e3%82%8b%e3%82%b9%e3%82%af%e3%83%aa%e3%83%97%e3%83%88.html)
