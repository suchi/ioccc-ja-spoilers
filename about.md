---
title: このサイトについて
layout: default
---

IOCCCの全作品を日本語でネタバレ紹介することを目指すサイトです。

## IOCCCとは

International Obfuscated C Code Contestの略で、直訳すると「国際難読化Cコードコンテスト」になります。
小さいのに読みにくく、独創性があって、とにかく面白いC言語プログラムで競い合います。

入賞した作品は公開されているので、眺めたり動かしたりして自由に鑑賞することができます。

## IOCCCの鑑賞方法

次のページから、これまでの全入賞作品のソースコードおよび添付ファイルがダウンロードできます。

[https://www.ioccc.org/years.html](https://www.ioccc.org/years.html)

個別にダウンロードしてもいいですが、all.tar.bz2で一括ダウンロードするのがおすすめです。
中に入っているC言語ソースコードたちが入賞作品です。
作品は通常、`"<作者名>.c"`や`"<作者名>/prog.c"`のようなファイル名になっています。

腕に覚えがあれば、それらを自力で解読したりコンパイル・実行したりして鑑賞してください。

各作品には、IOCCC審査員や作者が書いた説明（hintファイル）が付属しています。
プログラムの動かし方などが書いてあるので、適宜参照してください。

hintファイルを見てもわからないときや、ネタバレを見ながらもっと気楽に楽しみたいときは、このサイトの記事を見ながら鑑賞してください。

## なぜこのサイトを作った？

いろいろあります。

* 自分がやったコード読解を記録しておく
* 自分がわからなかったことや見落としていることを教えてもらえるかもしれない
* IOCCCをもっとみんなに知ってもらいたい

IOCCCの作品を鑑賞するには、C言語だけでなく、情報科学全般の知識とある程度の英語力が必要です。
これらのハードルのために、わかりやすい作品しか注目されていない現状があります。
これはもったいないので、筆者が理解できた範囲でネタバレを共有する価値があると思いました。

筆者の誤解や見逃しているネタに気づいたら、ぜひ[GitHubのissue](https://github.com/mame/ioccc-ja-spoilers/)や[Twitter: @mametter](https://twitter.com/mametter)などへご連絡ください。

本サイトの著作権は筆者（Yusuke Endoh）に帰属しますが、引用されているプログラムなどの著作権はそれぞれの作者に帰属します。
基本的にIOCCCの審査員がpublic domainまたはCC BY-SAで公開しているものを引用しています。
なお、IOCCCの審査員には個別にこのサイトを公開する許可をいただいています。

## ネタバレ解説の方針

記述が冗長になることを避けるため、あまり自信がないことでも断定的に書いています。
間違ってたら優しく指摘してくれると嬉しいです。

古くて動かなくなっているような作品には、なるべくパッチを付けています。
2020年現在で標準的なLinux環境（x86\_64、リトルエンディアン、signed char、gcc、最新のUbuntu）で動かすことを目標にしています。

また、興味を惹かれた作品は詳しく解析・批評しますが、そこまででもない作品に対してはあまり頑張りません。
おもしろポイントを見逃していたら教えてください。
