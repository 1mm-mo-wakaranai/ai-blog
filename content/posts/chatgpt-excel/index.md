---
title: "ChatGPTにExcelの作業を手伝ってもらう方法 ― 関数もマクロもAIに聞ける"
date: 2026-04-13
tags: ["ChatGPT", "仕事効率化"]
description: "Excelの関数やマクロが分からないとき、ChatGPTに聞けば一瞬で解決します。具体的な聞き方を解説。"
draft: false
---

## この記事で解決すること

「Excelの関数が分からない」「マクロって何？」

そんなとき、ChatGPTに聞けば数秒で答えが返ってきます。ググるより速いです。


{{< ad >}}

## 基本の聞き方

### 関数を教えてもらう

```
Excelで、A列の数値が100以上のセルだけを合計したいです。
使うべき関数と、具体的な数式を教えてください。
```

ChatGPTの回答例：

> SUMIF関数を使います。
> `=SUMIF(A:A,">=100")`

### やりたいことを日本語で伝える

関数名を知らなくても大丈夫です。やりたいことをそのまま伝えてください。

```
Excelで、名前の列に「田中」が含まれる行だけを
別のシートにコピーしたいです。手動でやる方法と、
自動でやる方法の両方を教えてください。
```

## 実践例

### 例1: VLOOKUP が分からない

```
ExcelのVLOOKUP関数の使い方を、具体例付きで教えてください。
商品コードから商品名を検索したいです。
```

### 例2: IF関数のネスト

```
Excelで、点数に応じてA〜Dの評価をつけたいです。
90点以上: A
70点以上: B
50点以上: C
それ以下: D
IF関数で書く方法を教えてください。
```

### 例3: マクロの作成

```
Excelで以下の作業を自動化するマクロを作ってください。

1. A列の空白セルがある行を削除する
2. B列の日付を新しい順に並べ替える
3. 結果を新しいシートにコピーする

VBAのコードと、マクロの実行方法も教えてください。
```

マクロ（VBA）は、Excelの操作を自動化するプログラムです。ChatGPTにコードを書いてもらえば、プログラミングの知識がなくても使えます。

## コツ

- データの構造を伝える（「A列に名前、B列に売上、C列に日付が入っています」）
- 期待する結果を伝える（「〜という表を作りたい」）
- エラーが出たらエラーメッセージをそのまま貼る

## 注意点

- 会社の機密データをそのままChatGPTに貼り付けるのは避けてください
- 個人名や金額などは「田中→Aさん」「100万円→XXX円」のように置き換えてから質問しましょう
- ChatGPTの回答は必ず自分で動作確認してから使ってください

## まとめ

- Excelの関数やマクロはChatGPTに聞くのが最速
- 関数名を知らなくても、やりたいことを日本語で伝えればOK
- 機密データは置き換えてから質問する

---
### あわせて読みたい
- [コピペで使えるChatGPTプロンプト10選 ― 仕事がすぐ楽になる](/posts/chatgpt-prompt-template/)
- [ChatGPTカスタム指示の設定方法 ― 毎回同じ説明をしなくて済む裏技](/posts/chatgpt-custom-instructions/)

<!-- affiliate -->
## 関連リソース

ChatGPT×Excelをもっと学びたい方へ：

<!-- START MoshimoAffiliateEasyLink --><script type="text/javascript">(function(b,c,f,g,a,d,e){b.MoshimoAffiliateObject=a;b[a]=b[a]||function(){arguments.currentScript=c.currentScript||c.scripts[c.scripts.length-2];(b[a].q=b[a].q||[]).push(arguments)};c.getElementById(a)||(d=c.createElement(f),d.src=g,d.id=a,e=c.getElementsByTagName("body")[0],e.appendChild(d))})(window,document,"script","//dn.msmstatic.com/site/cardlink/bundle.js?20220329","msmaflink");msmaflink({"n":"ChatGPT×Excel 最強の仕事術","b":"","t":"","d":"https:\/\/thumbnail.image.rakuten.co.jp","c_p":"","p":[""],"u":{"u":"https:\/\/search.rakuten.co.jp\/search\/mall\/ChatGPT%20Excel%20%E4%BB%95%E4%BA%8B%E8%A1%93\/","t":"rakuten","r_v":""},"v":"2.1","b_l":[{"id":1,"u_tx":"楽天市場で見る","u_bc":"#f76956","u_url":"https:\/\/search.rakuten.co.jp\/search\/mall\/ChatGPT%20Excel%20%E4%BB%95%E4%BA%8B%E8%A1%93\/","a_id":5490814,"p_id":54,"pl_id":27059,"pc_id":54,"s_n":"rakuten","u_so":1}],"eid":"TGGz3","s":"s"});</script><div id="msmaflink-TGGz3">リンク</div><!-- MoshimoAffiliateEasyLink END -->
<!-- /affiliate -->
