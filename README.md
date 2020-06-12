Elixir Hacking Guide
====================

本文章について
--------------

本文章は[Rubyソースコード完全解説(RHG)](http://i.loveruby.net/ja/rhg/book/)にインスパイアされて作成しました。

[Elixir](http://elixir-lang.org/)はErlangVM上で動作する関数型・メタプログラミング可能な言語です。

またElixirは[Erlang](http://www.erlang.org/)の

- 分散環境
- 障害耐性(フォルトトレラント)
- 無停止稼動

といった仕組み・機能を効率良く使う事ができる動的言語でもあります。

本文章のテーマは

- Elixirの構造を知る
- ErlangのOTPアプリケーションの構築方法を知る
- Elixir,Erlangについての勉強のアウトプット
- 日本語の適当な文章が無かったので書く事にした
- etc

です。

本文章の構成について
--------------------

本文章は以下の章から構成されます。

### Elixirのビルド

[Ch00.事前準備](./ch00.md)

[Ch01.Elixirアプリのフォルダ構成](./ch01.md)

[Ch02.Elixirビルド時に何が起こっているか](./ch02.md)

### Elixirコンパイラ

Ch03.elixirコンパイラのコンパイル

Ch04.yeccの使い方

### Elixirカーネル

[Ch05.Elixirコアモジュール](./ch05.md)

Ch0x.elixir:start_cliによるElixirカーネルコンパイル

Ch0x.elixir:start_cliによる標準ライブラリコンパイル

Ch0x.elixir:start_cliによるUnicodeモジュールコンパイル

Ch0x.実行ファイル(`elixir`,`elixirc`,`iex`,`mix`)について

### Appendix

[rebarの使い方](./apdA.md)

[ErlangのATS](./apdB.md)

Ch0x.関連ライブラリ(`eex`,`elixir`,`ex_unit`,`iex,logger`,`mix`)について

Ch0x.Erlangとの関係について

Ch0x.Elixirの構文について

参考にした文献・書籍・文章について
----------------------------------

本文章は以下の書籍・Webサイトを参考に作成しています。

### 書籍

- [プログラミングErlang](http://www.amazon.co.jp/プログラミングErlang-Joe-Armstrong/dp/4274067149/)
- [すごいErlangゆかいに学ぼう!](http://www.amazon.co.jp/すごいErlangゆかいに学ぼう-Fred-Hebert/dp/4274069125)
- [Erlangプログラミング](http://www.amazon.co.jp/Erlangプログラミング-Francesco-Cesarini/dp/4873114659/)
- [Erlang and OTP in Action](http://www.amazon.co.jp/Erlang-OTP-Action-Martin-Logan/dp/1933988789/)
- [Rubyを256倍使うための本 無道編](http://www.amazon.co.jp/Rubyを256倍使うための本-無道編-青木-峰郎/dp/4756137091)

### Webサイト

- [Elixir公式サイト](http://elixir-lang.org/)
- [Erlang公式サイト](http://www.erlang.org/)
- [Erlangユーザーズガイド](http://erlang.shibu.jp/)
- [Rubyソースコード完全解説(RHG)](http://i.loveruby.net/ja/rhg/book/)
- [awesome-elixir](https://github.com/h4cc/awesome-elixir)
- [awesome-erlang](https://github.com/drobakowski/awesome-erlang)

ライセンスについて
------------------

この文章は個人の範囲でご利用下さい。
この文章へのハイパーリンクはリンク先を問わず御自由になさって下さい。 報告は一切不要です。
