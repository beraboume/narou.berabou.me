[narou.berabou.me](http://narou.berabou.me/)
---

![2015-09-27 10 57 49](https://cloud.githubusercontent.com/assets/1548478/10120736/be1b5182-6506-11e5-9b9e-32ac6a12f428.png)

# ショートカットキー

長時間ホイールを動かすのは面倒なため、ビジュアルノベルのようにキーボード入力で読み進められるように操作を追加しています。

* `j/z` 次の章へ進む
* `k/x` 前の章へ戻る
* それ以外は、１行左へスクロールを進めます
* Shiftを押しながらの場合、１行右へスクロールを戻します

# Setup & Boot

gitおよびNodeJSとbowerのインストールが終了していることが前提です。ターミナル／cmder環境下で

```bash
git clone https://github.com/59naga/narou.berabou.me.git
cd narou.berabou.me

npm install
npm start
# Server running at http://localhost:59798
```

とすることで、`http://localhost:59798`上に、開発環境を起動できます。

# 更新履歴

* `0.0.4` 平成２８年０１月１６日（金）
  削除された小説は[Internet Archive](https://archive.org/)へ問い合わせて、最終の魚拓を使用する機能を追加

* `0.0.3` 平成２８年０１月１３日（水）
  短編が閲覧出来ない不具合（[#1][#1]）の修正

* `0.0.2` 平成２８年０１月０１日（金）
  トップページ下部に`縦書き変換ブックマークレット`を追加

* `0.0.0` 平成２７年０９月２８日（月）
  初版公開

[#1]: https://github.com/59naga/narou.berabou.me/issues/1

# 謝辞

このアプリケーションは非公式のもので、[株式会社ヒナプロジェクト](http://hinaproject.co.jp/)が提供しているものではありません。

License
---
[MIT][License]

[License]: http://59naga.mit-license.org/
