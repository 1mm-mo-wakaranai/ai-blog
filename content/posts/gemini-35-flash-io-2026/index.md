---
title: "【速報】Gemini 3.5 Flash発表！Google I/O 2026の目玉AIモデルを解説"
date: 2026-05-20
draft: true
tags: ["AI", "Google", "Gemini", "Google I/O"]
categories: ["AI"]
description: "Google I/O 2026で発表されたGemini 3.5 Flashを解説。前世代Proを超える性能、4倍の速度、40%安い料金。無料で使える方法やGemini Sparkについてもまとめます。"
cover:
  image: "images/cover.png"
  alt: "Gemini 3.5 Flash Google I/O 2026発表まとめ"
  relative: true
  hidden: false
---

## この記事で分かること

{{< chat name="初心者ちゃん" icon="/images/rin-icon.png" direction="left" >}}
Gemini 3.5 Flash発表！Google I/O 2026の目玉AIモデルを解説って何？初心者でも分かるように教えて…！
{{< /chat >}}

{{< chat name="全知全能くん" icon="/images/zenchi-icon.png" direction="right" >}}
もちろん！Gemini 3.5 Flash発表！Google I/O 2026の目玉AIモデルを解説について、初心者でも分かるように解説するよ。一緒に見ていこう。
{{< /chat >}}

「Google I/O 2026で何が発表されたの？」「Gemini 3.5 Flashって何がすごいの？」という方へ。

この記事では、2026年5月19日のGoogle I/O 2026で発表されたGemini 3.5 Flashの性能、料金、使い方をわかりやすくまとめています。

## Google I/O 2026で何が発表されたか

2026年5月19日、Googleの年次開発者会議「Google I/O 2026」が開催されました。

今年の目玉は**Gemini 3.5 Flash**です。これまで「安くて速いけど性能は控えめ」だったFlashモデルが、前世代の最上位モデル（Gemini 3.1 Pro）を超える性能を実現しました。

### 主な発表内容

| 発表内容 | 概要 |
|----------|------|
| Gemini 3.5 Flash | 新AIモデル。コーディングとエージェント性能が大幅向上 |
| Gemini Spark | 24時間稼働のパーソナルAIエージェント |
| Gemini Omni | マルチモーダル対応の新モデル |
| AI Mode強化 | Google検索のAIモードがGemini 3.5 Flashに |

## Gemini 3.5 Flashとは

Gemini 3.5 Flashは、Googleが開発した最新のAIモデルです。

「Flash」はこれまで速度重視・コスト重視のモデルでしたが、今回は性能面でも前世代のフラッグシップモデルを超えました。

### 基本スペック

| 項目 | 内容 |
|------|------|
| モデル名 | gemini-3.5-flash |
| リリース日 | 2026年5月19日 |
| コンテキストウィンドウ | 100万トークン（入力） |
| 最大出力 | 64,000トークン |
| 知識カットオフ | 2026年1月 |
| 料金（API） | 入力$1.50 / 出力$9.00（100万トークンあたり） |

## 何がすごいのか — 性能比較

Gemini 3.5 Flashが注目される理由は、「安いモデルが高いモデルを超えた」という点です。

### Gemini 3.5 Flash vs Gemini 3.1 Pro

| ベンチマーク | 3.5 Flash | 3.1 Pro | 用途 |
|-------------|-----------|---------|------|
| Terminal-Bench 2.1 | 76.2% | 70.3% | コーディング |
| GDPval-AA | 1,656 Elo | 1,314 Elo | エージェント作業 |
| MCP Atlas | 83.6% | 78.2% | ツール活用 |
| CharXiv Reasoning | 84.2% | — | マルチモーダル理解 |
| 出力速度 | 4倍速い | 基準 | レスポンス速度 |

特にエージェント性能（GDPval-AA）では342ポイントもの差がついています。

### Gemini 3.1 Proがまだ勝つ分野

すべてでFlashが勝っているわけではありません。

- **Humanity's Last Exam**（超難問推論）: Pro 44.4% vs Flash 40.2%
- **ARC-AGI-2**（抽象推論）: Pro 77.1% vs Flash 72.1%
- **長文コンテキスト検索**: Proの方が精度が高い

つまり「深い推論」が必要な場面ではまだProに分がありますが、日常的な使い方ではFlashで十分です。

## 料金 — 40%安くなった

### API料金の比較

| 項目 | Gemini 3.5 Flash | Gemini 3.1 Pro |
|------|-----------------|----------------|
| 入力（100万トークン） | $1.50 | $2.50 |
| 出力（100万トークン） | $9.00 | $15.00 |
| キャッシュ入力 | $0.15 | — |

前世代Proと比べて約40%のコスト削減です。

### 無料で使う方法

開発者でなくても、以下の方法で無料で使えます。

1. **Geminiアプリ** — Web・Android・iOSで利用可能。デフォルトモデルがGemini 3.5 Flashに変更済み
2. **Google検索のAIモード** — 検索結果にAI回答が表示される機能がGemini 3.5 Flashに

つまり、Geminiアプリを開くだけで最新モデルが使えます。

## Gemini Sparkとは

Google I/O 2026で同時に発表された**Gemini Spark**は、24時間バックグラウンドで動くパーソナルAIエージェントです。

### Gemini Sparkの特徴

- 繰り返しのタスクを自動で処理してくれる
- デジタルライフ全体をサポート
- 現在はテスター向けに提供中
- Google AI Ultraユーザー向けベータが来週開始予定（米国）

日本での提供時期は未発表ですが、今後のアップデートに注目です。

## ChatGPTやClaudeとの比較

2026年5月時点での主要AIモデルの立ち位置を整理します。

| モデル | 強み | 弱み |
|--------|------|------|
| Gemini 3.5 Flash | 速度・コスパ・エージェント性能 | 深い推論はやや弱い |
| GPT-5.5 | エージェントワークフロー全般 | 料金が高め |
| Claude Opus 4.7 | コーディング・低ハルシネーション | 速度はGeminiに劣る |

どのモデルも一長一短があり、用途に応じて使い分けるのがベストです。

Gemini 3.5 Flashの強みは「無料で使える」「速い」「十分賢い」の3拍子が揃っている点です。

## 今すぐ試す方法

### ステップ1: Geminiアプリを開く

[Geminiアプリ](https://gemini.google.com/)にアクセスするだけでOKです。すでにデフォルトモデルがGemini 3.5 Flashに切り替わっています。

### ステップ2: 何か質問してみる

普段ChatGPTで聞いているような質問をGeminiに投げてみましょう。回答速度の違いを体感できます。

### ステップ3: AI Modeを試す

Google検索で「AIモード」を有効にすると、検索結果がGemini 3.5 Flashで生成されます。

## Gemini 3.5 Proはいつ出る？

Gemini 3.5 Proは**2026年6月**に公開予定です。

Google I/O 2026では発表されず、CEOのスンダー・ピチャイ氏が「来月までお待ちください」とコメントしました。Proモデルはすでに社内で使用されているとのことです。

Proモデルが出れば、深い推論タスクでもGemini 3.5ファミリーで完結できるようになります。

## よくある質問（FAQ）

### Q: Gemini 3.5 Flashは日本語に対応していますか？

A: はい。Geminiアプリは日本語に対応しており、日本語での質問・回答が可能です。

### Q: 無料で使えるのはいつまでですか？

A: GeminiアプリとAI Modeでの利用は無料プランに含まれています。現時点で期限の発表はありません。

### Q: Gemini 3.5 FlashとChatGPT、どちらを使うべきですか？

A: 速度重視ならGemini 3.5 Flash、複雑なタスクの完遂力ならGPT-5.5がおすすめです。どちらも無料プランがあるので、両方試して比較するのが一番です。

### Q: Gemini Sparkは日本で使えますか？

A: 現時点では米国のテスター向けです。日本での提供時期は未発表ですが、Geminiアプリ自体は日本で利用可能です。

{{< chat name="初心者ちゃん" icon="/images/rin-icon.png" direction="left" >}}
なるほど…！分かりやすかった。ありがとう！
{{< /chat >}}

{{< chat name="全知全能くん" icon="/images/zenchi-icon.png" direction="right" >}}
どういたしまして。分からないことがあったらいつでも聞いてね。
{{< /chat >}}

## まとめ

- Google I/O 2026でGemini 3.5 Flashが発表（2026年5月19日）
- 前世代のProモデルを超える性能を、Flashの速度と価格で実現
- コーディング・エージェント性能で大幅な向上
- 出力速度は4倍、料金は40%安い
- Geminiアプリを開くだけで無料で使える
- Gemini 3.5 Proは2026年6月に公開予定

---
### あわせて読みたい
- [【2026年最新】Google I/O 2026 直前まとめ！Gemini新モデルやAI検索の注目ポイントを解説](/posts/google-io-2026-preview/)
- [GeminiとChatGPTどっちがいい？用途別に比較してみた](/posts/gemini-vs-chatgpt/)
