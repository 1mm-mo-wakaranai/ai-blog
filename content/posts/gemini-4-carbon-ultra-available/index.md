---
title: "【Gemini 4 Carbon】ついに一般公開！使えるのはUltraだけ ProはArgonのまま・3.1 Proは選べなくなった"
date: 2026-11-12
tags: ["Gemini", "AIモデル", "初心者向け"]
description: "Googleは11月10日、いちばん性能の高いモデル「Gemini 4 Carbon」を一般公開しました。Geminiアプリで使えるのはGoogle AI Ultraの人だけで、Proの人はGemini 4 Argonのままです。モデルの選び方、Argonとの使い分け、選べなくなった3.1 Proのこと、開発者向けの料金をやさしくまとめました。"
answer: "Googleは2026年11月10日、**Gemini 4 Carbon**を一般公開しました。10月28日の発表時はサイバー防御の専門家などに限られていましたが、今回から**Geminiアプリ・Google検索のAIモード・Antigravityで、Google AI Ultraの人が使える**ようになりました。**Google AI Proの人は、これまでどおりGemini 4 Argon**です。モデルの一覧では、Argonが「コードと分析」、Carbonが「いちばん複雑な作業」と表示されます。Googleは、**ふだんの仕事の多くはArgonで十分**で、Carbonは**むずかしいプログラミングや研究**向けとしています。今回、アプリのモデル一覧からは**Gemini 3.1 Proがなくなりました**。開発者向けのAPIは、11月30日までの特別価格で入力100万トークンあたり2ドル、出力10ドルです。"
checked: "2026-11-12"
faq:
  - q: "無料プランやProでもCarbonを使えますか？"
    a: "Geminiアプリで使えるのはGoogle AI Ultraだけです。Proの人はGemini 4 Argonを使います。無料プランでは使えません。"
  - q: "ArgonとCarbon、どちらを選べばいいですか？"
    a: "Googleは、ふだんのプログラミングや仕事の多くはArgonで十分としています。Carbonは、何段階もあるむずかしいコードの直しや、答えのない研究のような、とくにむずかしい作業向けです。"
  - q: "Gemini 3.1 Proはどうなりましたか？"
    a: "今回の公開にあわせて、Geminiアプリのモデル一覧から3.1 Proがなくなったと報じられています。"
  - q: "日本でも使えますか？"
    a: "発表で地域を限るとは書かれていません。検索のAIモードでは、18歳以上・対応する国の個人アカウントで、1日の回数の上限があります。"
  - q: "開発者向けの料金は？"
    a: "11月30日までは入力100万トークンあたり2ドル、出力10ドルの特別価格です。そのあとは入力4ドル、出力20ドルになります。"
draft: false
cover:
  image: "images/cover.png"
  alt: "Gemini 4 Carbon 一般公開 使えるのはUltraだけ"
  relative: true
  hidden: false
---
## この記事で分かること
{{< chat name="初心者ちゃん" icon="/images/rin-icon.png" direction="left" >}}
前に「Carbonはまだ使えない」って教えてもらったけど、ついに使えるようになったって聞いたの。わたしのGeminiでも使える？
{{< /chat >}}
{{< chat name="全知全能くん" icon="/images/zenchi-icon.png" direction="right" >}}
11月10日に一般公開されたよ。ただ、Geminiアプリで使えるのはいちばん上のUltraプランだけなんだ。Proの人はArgonのまま。だれが何を使えるのか、整理して説明するね。
{{< /chat >}}
![Gemini 4 Carbon一般公開のポイント](images/point-overview.png)

こんな疑問はありませんか？
- だれがCarbonを使えるの？
- ArgonとCarbon、どちらを選べばいい？
- Gemini 3.1 Proはどうなったの？

この記事は、Googleの公式ブログ「[Gemini 4 Carbon is now available](https://blog.google/innovation-and-ai/models-and-research/gemini-models/gemini-4-carbon-now-available/)」と[9to5Googleの記事](https://9to5google.com/2026/11/10/gemini-app-4-carbon/)（2026年11月10日）をもとにまとめています（2026年11月12日に確認）。筆者はUltraプランに入っていないため、実際の画面では確かめられていません。

10月に書いた[Gemini 4 Carbonはいつ使える？の記事](/posts/gemini-4-carbon-when-available/)の続きです。

## だれが使えるようになったの？
| 使う人 | 使える場所 |
|------|------|
| **Google AI Ultra** | Geminiアプリ、検索のAIモード、Antigravity |
| Google AI Pro | **Carbonは使えない**（Gemini 4 Argonを使う） |
| 無料プラン | 使えない |
| 開発者（有料API） | Google AI Studio、Android Studio |
| 会社（Gemini for business） | APIやモデルの一覧から |

検索の**AIモード**では、18歳以上・対応する国の**個人アカウント**で使え、**1日の回数に上限**があります。

{{< ad >}}

## ArgonとCarbonの使い分け
Geminiアプリのモデル一覧では、次のように表示されます。

| モデル | 一覧の説明 | 向いていること |
|------|------|------|
| **Gemini 4 Argon** | コードと分析 | ふだんのプログラミングや仕事の**ほとんど** |
| **Gemini 4 Carbon** | いちばん複雑な作業 | 何段階もあるむずかしいコードの直し、答えのない研究 |

Googleは、**ほとんどの仕事はArgonで十分**としています。Carbonは「モデルの頭の良さの限界を試すような作業」のためのモデルです。

{{< chat name="初心者ちゃん" icon="/images/rin-icon.png" direction="left" >}}
じゃあ、Proのわたしは、Argonで困ってないならそのままでいいんだね。
{{< /chat >}}
{{< chat name="全知全能くん" icon="/images/zenchi-icon.png" direction="right" >}}
そういうこと。Carbonのために、わざわざUltraに上げる必要はないよ。Argonでうまくいかない、とてもむずかしい作業がある人だけ考えればいいんだ。
{{< /chat >}}

## Gemini 3.1 Proは一覧からなくなった
今回の公開にあわせて、Geminiアプリのモデル一覧から**Gemini 3.1 Pro**がなくなったと報じられています。3.1 Proをえらんで使っていた人は、**Argon**などに切りかわります。

あわせて、Google AI Plusの人は**11月13日から**、GeminiアプリとAIモードで**Proのモデルを選べなくなる**とGoogleが案内しています。

## Carbonで強くなったこと
発表では、次のような点が紹介されています。

- 何人ものAIが手分けする**大きなプログラミング作業**（引っ越しや、原因さがし、設計の見直し）
- Webアプリを**作って、動かして、まちがいを直す**のをくり返す
- グラフ・図・表が入った**むずかしい資料を読む**作業。新しい評価「MKA」で1位
- **表・スライド・報告書**を、決められた形式どおりに作る

開発ツールのAntigravityでは、1つの指示を**複数のAIのチーム**に分けて進める「/swarm」も試験公開されています。

## 開発者向けの料金
| 期間 | 入力（100万トークンあたり） | 出力（100万トークンあたり） |
|------|------|------|
| 11月30日まで | 2ドル | 10ドル |
| 12月1日から | 4ドル | 20ドル |

Geminiのプランや料金の考え方は、[Gemini 4 Argonは無料版で使える？の記事](/posts/gemini-4-argon-free-or-pro/)でも紹介しています。

{{< faq >}}

{{< chat name="初心者ちゃん" icon="/images/rin-icon.png" direction="left" >}}
CarbonはUltraだけ。Proの人はArgonでOK。3.1 Proは一覧からなくなった、だね！
{{< /chat >}}
{{< chat name="全知全能くん" icon="/images/zenchi-icon.png" direction="right" >}}
その通り。Plusの人は11月13日からProのモデルが選べなくなるから、そこも覚えておいてね。
{{< /chat >}}

## まとめ
- Googleは11月10日、Gemini 4 Carbonを一般公開した
- Geminiアプリ・AIモード・Antigravityで使えるのはGoogle AI Ultraだけ。Proの人はArgonのまま
- Googleは、ふだんの仕事の多くはArgonで十分、Carbonはとくにむずかしい作業向けとしている
- Geminiアプリのモデル一覧から、Gemini 3.1 Proがなくなった
- 開発者向けAPIは、11月30日まで入力2ドル・出力10ドルの特別価格

---
### あわせて読みたい
- [【Gemini 4 Carbon】Googleの新しい最強モデル いつ使える？Argonとのちがい](/posts/gemini-4-carbon-when-available/)
- [【Gemini】「メモリーの概要」で覚えられていることを見て消せる 日本ではいつ？今できる確認方法](/posts/gemini-memory-summary/)
