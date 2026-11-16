---
title: "【Gemini 4 Hydrogen】速くて安い新モデル 無料版でも使える？検索・アプリでの使われ方まとめ"
date: 2026-11-16
tags: ["Gemini", "AIモデル", "初心者向け"]
description: "Googleは11月12日、Gemini 4シリーズの速いモデル「Gemini 4 Hydrogen」を公開しました。Gemini 3.8 Flashの後継で、Google検索のAIの答えには全員に使われます。Geminiアプリでは、無料版は自動で選ばれたときだけ、Plus以上なら名前で選べます。プランごとのちがいと、ArgonやCarbonとの使い分けをやさしくまとめました。"
answer: "Googleは2026年11月12日、Gemini 4シリーズの**速くて安いモデル「Gemini 4 Hydrogen」**を公開しました。**Gemini 3.8 Flashの後継**です。**Google検索のAIの答えには、すべての人に**使われはじめています。Geminiアプリでは、**無料版は自分では選べず**、Geminiが自動でモデルを選ぶときに使われることがあります。**Google AI Plus以上**なら、モデルの一覧から**名前で選べます**。Googleによると、3.8 Flashより**2.5倍速く**作業を終え、**事実でないことを言う割合は5分の1以下**に減りました。ふだんの文章づくりや要約にはHydrogen、むずかしい作業にはArgonやCarbon、という使い分けになります。"
checked: "2026-11-16"
faq:
  - q: "無料版でも使えますか？"
    a: "Geminiアプリの無料版では、モデルの一覧から選ぶことはできません。Geminiが自動でモデルを選ぶときに、Hydrogenが使われることがあります。Google検索のAIの答えには、無料で使われています。"
  - q: "どのプランなら選べますか？"
    a: "Google AI Plus以上です。Proでは、Googleスプレッドシートの中でも使えます。"
  - q: "ArgonやCarbonとは何がちがいますか？"
    a: "Hydrogenは速さと安さを重視した、ふだん使いのモデルです。ArgonとCarbonは、長くてむずかしい考えごと向けです。Googleは、Hydrogenが第三者の評価でArgonを少し上回ったとしていますが、いちばん深く考える設定では答えが出るまで時間がかかるという指摘もあります。"
  - q: "日本の検索でも使われていますか？"
    a: "Googleは、検索で全世界に順番に広げているとしています。いつ自分の検索に反映されるかは、人によってちがいます。"
  - q: "開発者向けの料金は？"
    a: "入力100万トークンあたり1.5ドル、出力7.5ドルです。無料の枠もあります。"
draft: false
cover:
  image: "images/cover.png"
  alt: "Gemini 4 Hydrogen 速くて安い新モデル"
  relative: true
  hidden: false
---
## この記事で分かること
{{< chat name="初心者ちゃん" icon="/images/rin-icon.png" direction="left" >}}
ArgonにCarbonに、今度は「Hydrogen」…。Geminiの名前が多すぎて、もう分からないよ〜。
{{< /chat >}}
{{< chat name="全知全能くん" icon="/images/zenchi-icon.png" direction="right" >}}
Hydrogenは、前の「Flash」にあたる速いモデルなんだ。しかも検索では全員に使われはじめていて、ふだんいちばん出会うモデルになりそう。プランごとに整理するね。
{{< /chat >}}
![Gemini 4 Hydrogenのポイント](images/point-overview.png)

こんな疑問はありませんか？
- Hydrogenって何？
- 無料版でも使える？
- Argon・Carbonとどう使い分ける？

この記事は、Googleの公式ブログ「[Introducing Gemini 4 Hydrogen](https://blog.google/intl/en-in/products/introducing-gemini-4-hydrogen/)」と、[Justin McKelvey氏のまとめ](https://justinmckelvey.com/blog/gemini-4-hydrogen)（2026年11月13日）などをもとにまとめています（2026年11月16日に確認）。筆者は日本のアカウントの画面ではまだ確かめられていないため、表示の名前は発表と報道をもとにしています。

## Gemini 4シリーズの3つのモデル
| モデル | 向いていること | 公開 |
|------|------|------|
| **Gemini 4 Hydrogen** | ふだん使い（文章・要約・資料のくらべっこ） | 11月12日 |
| Gemini 4 Argon | 長くてむずかしい仕事・プログラミング | 10月13日 |
| Gemini 4 Carbon | とくにむずかしい作業 | 11月10日 |

Hydrogenは**Gemini 3.8 Flashの後継**で、名前に「Flash」がつかなくなった初めてのモデルです。

{{< ad >}}

## プランごとの使え方
| 場所・プラン | Hydrogenの使え方 |
|------|------|
| **Google検索のAIの答え** | **全員**（全世界に順番に） |
| Geminiアプリ 無料版 | **自分では選べない**。自動選択のときに使われることがある |
| Google AI Plus | モデルの一覧から**名前で選べる** |
| Google AI Pro | 名前で選べる。**スプレッドシート**やAntigravityでも |
| Google AI Ultra | 名前で選べる。いちばん多く使える |
| 開発者（API） | 無料の枠あり。有料は入力1.5ドル・出力7.5ドル（100万トークンあたり） |

{{< chat name="初心者ちゃん" icon="/images/rin-icon.png" direction="left" >}}
無料版は「選べない」けど、自動で使われることはあるんだね。
{{< /chat >}}
{{< chat name="全知全能くん" icon="/images/zenchi-icon.png" direction="right" >}}
そう。それに、検索の答えには全員に使われるから、知らないうちにHydrogenの答えを読んでいることもあるよ。
{{< /chat >}}

## よくなったこと（Googleの発表）
- 作業を終えるのが、3.8 Flashの**2.5倍速い**
- **事実でないことを言う割合**が、**5分の1以下**に
- 第三者の評価で、標準の設定で51点（Argonは50点）
- 一度に**100万トークン**（数百ページ分）まで読める
- アップロードしたファイルや、Gmail・Googleドライブから情報を集めるのが上手に
- 「短く」「専門用語なし」といった**書き方のルールを守りやすく**

### 考える深さを4段階で選べる
Hydrogenには、考える深さの設定が**4段階**あります。いちばん深い設定にすると点数は上がりますが、**答えが出るまで時間がかかり**、使うトークンも増えるという指摘があります。

## どう使い分ける？
![モデルの使い分け](images/step-choose.png)

- **メールの下書き・要約・調べもの**：Hydrogen（速い）
- **長い資料の分析・ふつうのプログラミング**：Argon
- **ほかでうまくいかない、とてもむずかしい作業**：Carbon（Ultraだけ）

無料版の人は、特に何もしなくて大丈夫です。Geminiが内容に合わせて選んでくれます。

Carbonについては[Gemini 4 Carbon一般公開の記事](/posts/gemini-4-carbon-ultra-available/)でくわしく紹介しています。

{{< faq >}}

{{< chat name="初心者ちゃん" icon="/images/rin-icon.png" direction="left" >}}
ふだん使いはHydrogen。無料版は自動で、Plus以上なら自分で選べる、だね！
{{< /chat >}}
{{< chat name="全知全能くん" icon="/images/zenchi-icon.png" direction="right" >}}
その通り。答えが速くなって、まちがいも減ったから、まずはふつうに使ってみよう。
{{< /chat >}}

## まとめ
- Googleは11月12日、速くて安い「Gemini 4 Hydrogen」を公開。Gemini 3.8 Flashの後継
- Google検索のAIの答えには、全員に使われはじめている
- Geminiアプリの無料版は自動選択のときだけ。Plus以上なら名前で選べる
- 3.8 Flashより2.5倍速く、事実でないことを言う割合は5分の1以下に
- ふだん使いはHydrogen、むずかしい作業はArgonやCarbon

---
### あわせて読みたい
- [【Gemini 4 Carbon】ついに一般公開！使えるのはUltraだけ ProはArgonのまま・3.1 Proは選べなくなった](/posts/gemini-4-carbon-ultra-available/)
- [【Gemini】Gemini 4 Argonが登場！無料版で使える？Proに入るべき人](/posts/gemini-4-argon-free-or-pro/)
