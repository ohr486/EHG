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

### Elixirの実行バイナリ

Ch03.Elixirプログラムの実行

Ch04.Elixirコマンドの実体

### Elixirコンパイラ

[Ch05.一般的なコンパイラの概要](./ch06.md)

Ch06.Elixirコンパイラの概要

[Ch07.elixirコンパイラのコンパイル](./ch07.md)

[Ch08.yeccの使い方](./ch08.md)

### Elixirカーネル

[Ch09.Elixirコアモジュール](./ch09.md)

Ch10.elixirのxxxアプリ

### Appendix

[Makefile基礎](./apdA.md)

[ErlangのAST](./apdB.md)


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
