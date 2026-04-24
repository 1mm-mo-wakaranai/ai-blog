---
title: "【ChatGPT】CSVデータを貼り付けるだけで分析してくれる使い方"
date: 2026-04-21
tags: ["ChatGPT", "仕事効率化"]
description: "ChatGPTにCSVデータを貼り付けるだけで、集計・分析・グラフ作成までやってくれます。Excelが苦手な人でもデータ分析ができる方法を解説。"
draft: false
---

## この記事で解決すること

「データ分析したいけど、Excelのピボットテーブルとか分からない」

ChatGPTにCSVデータを貼り付けるだけで、集計・分析・グラフまで作ってくれます。

## 基本の使い方

### ステップ1：データを用意する

ExcelやGoogleスプレッドシートのデータをコピーするか、CSVファイルをアップロードします。

### ステップ2：ChatGPTに貼り付けて指示する

```
以下のデータを分析してください。

日付,商品名,売上金額,地域
2026-01-01,商品A,15000,東京
2026-01-01,商品B,8000,大阪
2026-01-02,商品A,12000,東京
2026-01-02,商品C,20000,名古屋
...

以下を教えてください：
1. 商品別の売上合計
2. 地域別の売上合計
3. 日別の売上推移
```

ChatGPTが表形式で集計結果を返してくれます。

### ステップ3：グラフも作れる

```
上記のデータで、商品別の売上を棒グラフにしてください。
```

ChatGPTのCode Interpreter機能を使えば、実際にグラフを生成してくれます。

{{< ad >}}

## 実践プロンプト集

### 売上データの分析

```
以下の売上データを分析して、以下を教えてください。
- 月別の売上推移
- 前月比の増減率
- 売上が最も高い商品TOP3
- 売上が低下している商品があれば警告

（ここにデータを貼り付ける）
```

### アンケート結果の集計

```
以下のアンケート結果を集計してください。
- 各質問の回答分布（割合付き）
- 自由記述欄のキーワード分析
- 全体の傾向まとめ（3行以内）

（ここにデータを貼り付ける）
```

### 勤怠データの分析

```
以下の勤怠データから、以下を算出してください。
- 社員別の月間労働時間
- 残業時間が多い社員TOP5
- 部署別の平均労働時間

（ここにデータを貼り付ける）
```

## 注意点

- 会社の機密データをそのまま貼り付けるのは避けてください
- 個人名や具体的な金額は仮のデータに置き換えてから入力しましょう
- ChatGPTの分析結果は参考値です。重要な意思決定には必ず自分で検証してください

## まとめ

- ChatGPTにデータを貼り付けるだけで分析できる
- 集計、グラフ作成、傾向分析まで対応
- Excelが苦手でもデータ分析ができる
- 機密データの取り扱いには注意

---

### あわせて読みたい
- [ChatGPTにExcelの作業を手伝ってもらう方法](/posts/chatgpt-excel/)
- [コピペで使えるChatGPTプロンプト10選](/posts/chatgpt-prompt-template/)

<!-- affiliate -->
## 関連リソース

データ分析をもっと学びたい方へ：

<!-- START MoshimoAffiliateEasyLink --><script type="text/javascript">(function(b,c,f,g,a,d,e){b.MoshimoAffiliateObject=a;b[a]=b[a]||function(){arguments.currentScript=c.currentScript||c.scripts[c.scripts.length-2];(b[a].q=b[a].q||[]).push(arguments)};c.getElementById(a)||(d=c.createElement(f),d.src=g,d.id=a,e=c.getElementsByTagName("body")[0],e.appendChild(d))})(window,document,"script","//dn.msmstatic.com/site/cardlink/bundle.js?20220329","msmaflink");msmaflink({"n":"ChatGPTによるプログラミング＆データ分析入門","b":"","t":"","d":"https:\/\/thumbnail.image.rakuten.co.jp","c_p":"","p":[""],"u":{"u":"https:\/\/search.rakuten.co.jp\/search\/mall\/ChatGPT%20%E3%83%87%E3%83%BC%E3%82%BF%E5%88%86%E6%9E%90%20%E5%85%A5%E9%96%80\/","t":"rakuten","r_v":""},"v":"2.1","b_l":[{"id":1,"u_tx":"楽天市場で見る","u_bc":"#f76956","u_url":"https:\/\/search.rakuten.co.jp\/search\/mall\/ChatGPT%20%E3%83%87%E3%83%BC%E3%82%BF%E5%88%86%E6%9E%90%20%E5%85%A5%E9%96%80\/","a_id":5490814,"p_id":54,"pl_id":27059,"pc_id":54,"s_n":"rakuten","u_so":1}],"eid":"Gbgl7","s":"s"});</script><div id="msmaflink-Gbgl7">リンク</div><!-- MoshimoAffiliateEasyLink END -->
<!-- /affiliate -->
