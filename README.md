# PureScript by Example

This repository contains a [community fork](https://github.com/purescript-contrib/purescript-book/) of _PureScript by Example_ by Phil Freeman, also known as "the PureScript book". This version differs from the original in that it has been updated so that the code and exercises work with up-to-date versions of the compiler, libraries, and tools. Some chapters have also been rewritten to showcase the latest features of the PureScript ecosystem.

このリポジトリには"PureScript book"としても知られる Phil Freeman著の _PureScript by Example_ の [community fork](https://github.com/purescript-contrib/purescript-book/) が含まれています．このバージョンがオリジナルと異なる点として，コードと練習問題が最新バージョンのコンパイラ，ライブラリ，ツールで動作するように更新されています．また，いくつかの章ではPureScriptエコシステムの最新機能を紹介するように書き換えられています．

If you enjoyed the book or found it useful, please consider buying a copy of [the original on Leanpub](https://leanpub.com/purescript).

この本を楽しんでくださった方，お役に立った方は，ぜひ[Leanpubで原書](https://leanpub.com/purescript)の購入を検討してみてください．

## Status

This book is being continuously updated as the language evolves, so please report any [issues](https://github.com/purescript-contrib/purescript-book/issues) you discover with the material. We appreciate any feedback you have to share, even if it's as simple as pointing out a confusing section that we could make more beginner-friendly.

この本は言語の進化に合わせて継続的に更新されていますので，資料に[問題](https://github.com/purescript-contrib/purescript-book/issues)を発見した場合は報告してください．分かりづらい部分を指摘するだけの簡単なものでもであっても，より初心者に優しいものになるようなフィードバックであればありがたく思います．

Unit tests are also being added to each chapter so you can check if your answers to the exercises are correct. See [#79](https://github.com/purescript-contrib/purescript-book/issues/79) for the latest status on tests.

各章にはユニットテストが追加されており，演習問題の解答が正しいかどうかを確認することができるようになっています．テストの最新の状況については [#79](https://github.com/purescript-contrib/purescript-book/issues/79) を参照してください．

## About the Book

PureScript is a small strongly, statically typed programming language with expressive types, written in and inspired by Haskell, and compiling to Javascript.

PureScriptはHaskellにインスパイアされて書かれた，表現力の高い型を持つ静的に型付けされた小さく強力なプログラミング言語で、Javascriptにコンパイルされます．

Functional programming in JavaScript has seen quite a lot of popularity recently, but large-scale application development is hindered by the lack of a disciplined environment in which to write code. PureScript aims to solve that problem by bringing the power of strongly-typed functional programming to the world of JavaScript development.

JavaScriptで関数型プログラミングが近年非常に人気を博していますが，大規模なアプリケーション開発ではコードを書くための規律ある環境がないため，開発の妨げになっています．PureScriptは，JavaScript開発の世界に強力に型付けされた関数型プログラミングの力を持ち込むことで，この問題を解決することを目指しています．

This book will show you how to get started with the PureScript programming language, from the basics (setting up a development environment) to the advanced.

本書では、基礎（開発環境の設定）から発展まで，プログラミング言語PureScriptを使いこなすための方法を紹介します．

Each chapter will be motivated by a particular problem, and in the course of solving that problem, new functional programming tools and techniques will be introduced. Here are some examples of problems that will be solved in this book:

各章では特定の問題を動機づけとして，その問題を解決する過程で，新しい関数型プログラミングのツールやテクニックを紹介します．本書で解決する問題の例を紹介します：

- Transforming data structures with maps and folds
- Form field validation using applicative functors
- Testing code with QuickCheck
- Using the canvas
- Domain specific language implementation
- Working with the DOM
- JavaScript interoperability
- Parallel asynchronous execution

- マップと畳み込みを使ったデータ構造の変換
- アプリ課ティブファンクタを使用したフォームフィールドの検証
- QuickCheckを使用したコードのテスト
- キャンバスの使用
- ドメイン固有言語の実装
- DOMとの連携
- JavaScriptとの相互運用性
- 並列非同期実行

## License

Copyright (c) 2014-2017 Phil Freeman.

The text of this book is licensed under the Creative Commons Attribution-NonCommercial-ShareAlike 3.0 Unported License: <https://creativecommons.org/licenses/by-nc-sa/3.0/deed.en_US>.

Some text is derived from the [PureScript Documentation Repo](https://github.com/purescript/documentation), which uses the same license, and is copyright [various contributors](https://github.com/purescript/documentation/blob/master/CONTRIBUTORS.md).

The exercises are licensed under the MIT license.
