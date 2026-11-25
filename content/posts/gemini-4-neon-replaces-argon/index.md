---
title: "【Gemini 4 Neon】ProのArgonがNeonに入れかわった 考える深さは「低」が標準なので要注意"
date: 2026-11-25
tags: ["Gemini", "AIモデル", "初心者向け"]
description: "Googleは11月18日、Gemini 4シリーズの新しいモデル「Gemini 4 Neon」を公開しました。Google AI Proでは、これまでのGemini 4 ArgonがNeonに入れかわり、アプリから消えました。無料版とPlusでは使えません。プランごとの選べるモデル、見落としやすい「考える深さ」の設定、Neonでよくなったことをやさしくまとめました。"
answer: "Googleは2026年11月18日、**Gemini 4 Neon**を公開しました。Gemini 4シリーズで、速いHydrogenと、いちばん強いCarbonのあいだのモデルです。**Google AI Proでは、Gemini 4 ArgonがNeonに入れかわり**、Argonはアプリのモデル一覧から**なくなりました**。**無料版とGoogle AI Plusでは、Neonは使えません**。いまの一覧は、無料版が「自動」だけ、Plusが自動とHydrogen、Proが**自動・Hydrogen・Neon**、Ultraがそれに**Carbon**を加えたものです。注意したいのは、**モデルを自分で選ぶと、考える深さが「低」になる**ことです。むずかしい作業では「中」か「高」に変えましょう。"
checked: "2026-11-25"
faq:
  - q: "Argonはもう使えませんか？"
    a: "Geminiアプリのモデル一覧からはなくなりました。開発者向けのAPIでは、引き続き使えます。"
  - q: "無料版でNeonを使えますか？"
    a: "使えません。無料版は「自動」だけで、内容に合わせてHydrogenなどが選ばれます。Google AI Plusでも使えません。"
  - q: "考える深さはどこで変えますか？"
    a: "モデルを選ぶメニューで、モデルといっしょに考える深さを選びます。選ばないと「低」になります。一度選ぶと、その会話のあいだはずっと同じ設定が使われます。"
  - q: "「高」にするとどうなりますか？"
    a: "むずかしい問題で答えがよくなりやすい代わりに、時間がかかり、使える量を多く使います。ふだんの質問なら「低」や「中」で十分なことが多いです。"
  - q: "Neonで何がよくなりましたか？"
    a: "Googleによると、文章がわかりやすくなり、表・PDF・写真の読み取りが正確になりました。調べものでWeb検索をよく使うようになり、何段階もある作業も少ない量でこなせるようになったとしています。"
draft: false
cover:
  image: "images/cover.png"
  alt: "Gemini 4 Neon ProのArgonがNeonに入れかわった"
  relative: true
  hidden: false
---
## この記事で分かること
{{< chat name="初心者ちゃん" icon="/images/rin-icon.png" direction="left" >}}
GeminiのProを使ってるんだけど、いつも選んでたArgonが消えて「Neon」っていうのになってたの！何が起きたの？
{{< /chat >}}
{{< chat name="全知全能くん" icon="/images/zenchi-icon.png" direction="right" >}}
11月18日に、ArgonがNeonに入れかわったんだ。しかも、自分でモデルを選ぶと「考える深さ」が低になる落とし穴があるよ。そこも一緒に説明するね。
{{< /chat >}}
![Gemini 4 Neonのポイント](images/point-overview.png)

こんな疑問はありませんか？
- Neonって何？Argonはどこに行ったの？
- 自分のプランで使える？
- どう設定すればいいの？

この記事は、Googleの公式ブログ「[Introducing Gemini 4 Neon](https://blog.google/innovation-and-ai/models-and-research/gemini-models/introducing-gemini-4-neon/)」と、[Notebookcheckの記事](https://www.notebookcheck.net/Gemini-4-Neon-replaces-Argon-for-Google-AI-Pro-subscribers.1454281.0.html)をもとにまとめています（2026年11月25日に確認）。筆者は日本のProアカウントの画面ではまだ確かめられていないため、画面の名前は発表と報道をもとにしています。

## Gemini 4シリーズの4つのモデル
| モデル | 向いていること | 公開 |
|------|------|------|
| Gemini 4 Hydrogen | ふだん使い（速い） | 11月12日 |
| **Gemini 4 Neon** | **むずかしい仕事・プログラミング** | **11月18日** |
| Gemini 4 Carbon | とくにむずかしい作業 | 11月10日 |
| Gemini 4 Argon | （アプリからは引退） | 10月13日 |

Neonは、Hydrogenと**Carbonのあいだ**のモデルです。Googleは「Carbonに近い頭の良さを、もっと速く」としています。

{{< ad >}}

## プランごとに選べるモデル（11月25日時点）
| プラン | モデルの一覧 |
|------|------|
| 無料版 | 自動だけ |
| Google AI Plus | 自動、Hydrogen |
| **Google AI Pro** | 自動、Hydrogen、**Neon** |
| Google AI Ultra | 自動、Hydrogen、Neon、**Carbon** |

- **Argon**と**3.1 Pro**は、アプリの一覧から**なくなりました**
- Plusでは、**11月13日から**Proのモデルを選べなくなっています
- 提供は順番に進んでいるので、まだNeonが出ていない人もいます

{{< chat name="初心者ちゃん" icon="/images/rin-icon.png" direction="left" >}}
無料版とPlusだと、Neonは使えないんだね。
{{< /chat >}}
{{< chat name="全知全能くん" icon="/images/zenchi-icon.png" direction="right" >}}
そう。Proの人は、前のArgonの代わりにNeonを使う、と覚えておけばOKだよ。
{{< /chat >}}

## 見落としやすい「考える深さ」の設定
![考える深さを設定する流れ](images/step-thinking.png)

Googleのヘルプによると、**モデルを自分で選んで、考える深さを選ばないと「低」**になります。Argonのころと同じつもりで使うと、答えが浅く感じるかもしれません。

### ステップ1: モデルのメニューを開く
入力欄の近くにある、モデルを選ぶメニューを開きます。

### ステップ2: Neonを選ぶ
［**Gemini 4 Neon**］を選びます。

### ステップ3: 考える深さを選ぶ
- **低**：ふつうの質問、すぐ答えがほしいとき
- **中**：少しむずかしい資料の読み取りや文章づくり
- **高**：むずかしいプログラミングや分析（時間がかかり、使える量を多く使う）

### ステップ4: 会話のあいだは同じ設定
一度選ぶと、**その会話のあいだは同じモデルと深さ**が使われます。あとで同じ会話に戻ってきても同じです。

## Neonでよくなったこと（Googleの発表）
- 文章が**わかりやすく**なった
- 表・PDF・写真の**読み取りが正確**に
- 値段の比べっこなど、**Web検索をよく使う**ようになった
- 「タスク」の何段階もある作業を、**少ない量**でこなせる
- 第三者の評価で61点（Claude Opus 5.5は59点、GPT-6.2 Solは57点。Googleが選んだ比べ方）
- 隠れた指示でAIをだます攻撃のテストで、いちばん深い設定では攻撃が成功しなかった（Googleの自社テスト）

HydrogenとCarbonについては、[Hydrogenの記事](/posts/gemini-4-hydrogen/)と[Carbonの記事](/posts/gemini-4-carbon-ultra-available/)で紹介しています。

{{< faq >}}

{{< chat name="初心者ちゃん" icon="/images/rin-icon.png" direction="left" >}}
ProならArgonの代わりにNeon。むずかしいことを頼むときは、考える深さを「中」か「高」に、だね！
{{< /chat >}}
{{< chat name="全知全能くん" icon="/images/zenchi-icon.png" direction="right" >}}
その通り。ふだんの質問なら「自動」のままでも大丈夫だよ。
{{< /chat >}}

## まとめ
- Googleは11月18日、Gemini 4 Neonを公開。HydrogenとCarbonのあいだのモデル
- Google AI Proでは、ArgonがNeonに入れかわり、Argonと3.1 Proはアプリから消えた
- 無料版とPlusでは使えない。Carbonは引き続きUltraだけ
- モデルを自分で選ぶと、考える深さは「低」になる。むずかしい作業は「中」か「高」に
- 文章のわかりやすさや、表・PDF・写真の読み取りがよくなったとGoogleは説明している

---
### あわせて読みたい
- [【Gemini 4 Hydrogen】速くて安い新モデル 無料版でも使える？検索・アプリでの使われ方まとめ](/posts/gemini-4-hydrogen/)
- [【Gemini 4 Carbon】ついに一般公開！使えるのはUltraだけ ProはArgonのまま・3.1 Proは選べなくなった](/posts/gemini-4-carbon-ultra-available/)
