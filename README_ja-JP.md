# 🚀 Gemini 3 プロンプト集

[![Awesome](https://awesome.re/badge.svg)](https://github.com/sindresorhus/awesome)
[![GitHub stars](https://img.shields.io/github/stars/YouMind-OpenLab/awesome-gemini-3-prompts?style=social)](https://github.com/YouMind-OpenLab/awesome-gemini-3-prompts)
[![License: CC BY 4.0](https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by/4.0/)
[![Update README](https://github.com/YouMind-OpenLab/awesome-gemini-3-prompts/actions/workflows/update-readme.yml/badge.svg)](https://github.com/YouMind-OpenLab/awesome-gemini-3-prompts/actions)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](docs/CONTRIBUTING.md)

> 🎨 Google Gemini 3 のマルチモーダル AI プロンプトコレクション

> 💡 **Note**: Nano Banana Pro の画像プロンプトに興味がある場合は、500以上の厳選されたプロンプトを含む別のリポジトリをご覧ください：https://github.com/YouMind-OpenLab/awesome-nano-banana-pro-prompts

> ⚠️ **著作権に関する通知**: すべてのプロンプトは教育目的でコミュニティから収集されています。権利を侵害していると思われるコンテンツがある場合は、[issue を作成](https://github.com/YouMind-OpenLab/awesome-gemini-3-prompts/issues/new?template=bug-report.yml)してください。速やかに削除いたします。

---

[![English](https://img.shields.io/badge/English-Click%20to%20View-lightgrey)](README.md) [![简体中文](https://img.shields.io/badge/%E7%AE%80%E4%BD%93%E4%B8%AD%E6%96%87-Click%20to%20View-lightgrey)](README_zh.md) [![繁體中文](https://img.shields.io/badge/%E7%B9%81%E9%AB%94%E4%B8%AD%E6%96%87-Click%20to%20View-lightgrey)](README_zh-TW.md) [![日本語](https://img.shields.io/badge/%E6%97%A5%E6%9C%AC%E8%AA%9E-Current-brightgreen)](README_ja-JP.md) [![한국어](https://img.shields.io/badge/%ED%95%9C%EA%B5%AD%EC%96%B4-Click%20to%20View-lightgrey)](README_ko-KR.md) [![ไทย](https://img.shields.io/badge/%E0%B9%84%E0%B8%97%E0%B8%A2-Click%20to%20View-lightgrey)](README_th-TH.md) [![Tiếng Việt](https://img.shields.io/badge/Ti%E1%BA%BFng%20Vi%E1%BB%87t-Click%20to%20View-lightgrey)](README_vi-VN.md) [![हिन्दी](https://img.shields.io/badge/%E0%A4%B9%E0%A4%BF%E0%A4%A8%E0%A5%8D%E0%A4%A6%E0%A5%80-Click%20to%20View-lightgrey)](README_hi-IN.md) [![Español](https://img.shields.io/badge/Espa%C3%B1ol-Click%20to%20View-lightgrey)](README_es-ES.md) [![Español (Latinoamérica)](https://img.shields.io/badge/Espa%C3%B1ol%20(Latinoam%C3%A9rica)-Click%20to%20View-lightgrey)](README_es-419.md) [![Deutsch](https://img.shields.io/badge/Deutsch-Click%20to%20View-lightgrey)](README_de-DE.md) [![Français](https://img.shields.io/badge/Fran%C3%A7ais-Click%20to%20View-lightgrey)](README_fr-FR.md) [![Italiano](https://img.shields.io/badge/Italiano-Click%20to%20View-lightgrey)](README_it-IT.md) [![Português (Brasil)](https://img.shields.io/badge/Portugu%C3%AAs%20(Brasil)-Click%20to%20View-lightgrey)](README_pt-BR.md) [![Português](https://img.shields.io/badge/Portugu%C3%AAs-Click%20to%20View-lightgrey)](README_pt-PT.md) [![Türkçe](https://img.shields.io/badge/T%C3%BCrk%C3%A7e-Click%20to%20View-lightgrey)](README_tr-TR.md)

---

## 🌐 Web ギャラリーで見る

<div align="center">

<img src="public/images/gemini-3-prompts-cover-en.png" alt="Gemini 3 Prompts Cover" width="800">

<img src="public/images/gemini-3-prompts-list-en.png" alt="Gemini 3 Prompts List" width="800">

</div>

**[👉 YouMind Gemini 3 プロンプトギャラリーを見る](https://youmind.com/gemini-3-prompts)**

ギャラリーを使用する理由

| Feature | GitHub README | youmind.com ギャラリー |
|---------|--------------|---------------------|
| 🎨 ビジュアルレイアウト | 線形リスト | 美しいメイソンリグリッド |
| 🔍 検索 | Ctrl+F のみ | 全文検索とフィルター |
| 🤖 AI ワンクリック生成 | - | AI ワンクリック生成 |
| 📱 モバイル | 基本 | 完全レスポンシブ |

---

## 📖 目次

- [🌐 Web ギャラリーで見る](#-view-in-web-gallery)
- [🤔 Gemini 3 とは？](#-what-is-gemini-3)
- [📊 統計](#-statistics)
- [🔥 おすすめプロンプト](#-featured-prompts)
- [📋 すべてのプロンプト](#-all-prompts)
- [🤝 貢献方法](#-how-to-contribute)
- [📄 ライセンス](#-license)
- [🙏 謝辞](#-acknowledgements)
- [⭐ スター履歴](#-star-history)

---

## 🤔 Gemini 3 とは？

**Gemini 3** は、Google がリリースした次世代マルチモーダル大規模言語モデルで、以下の特徴があります：

- 🎯 **超大コンテキストウィンドウ** - 100万トークンをサポートし、包括的な理解を実現
- 🎨 **マルチモーダルインテリジェンス** - テキスト、画像、音声、動画、コードを理解し生成
- ⚡ **実行型 AI** - 自動実行、リアルタイムプレビューでウェブサイトを直接生成、ワンクリックで公開
- 🌈 **強力な推論能力** - 高度な問題解決と複雑なタスク処理

📚 **詳細はこちら**：[Gemini 3: 10 の実例](https://youmind.com/blog/gemini-3-10-real-cases)

### 🚀 Raycast 統合

一部のプロンプトは [Raycast Snippets](https://raycast.com/help/snippets) 構文を使用した**動的引数**をサポートしています。🚀 Raycast Friendly バッジを探してください！

**例：**
```
A quote card with "{argument name="quote" default="Stay hungry, stay foolish"}"
by {argument name="author" default="Steve Jobs"}
```

Raycast で使用すると、引数を動的に置き換えて迅速に反復できます！

---

## 📊 統計

<div align="center">

| 指標 | 数 |
|--------|-------|
| 📝 プロンプト総数 | **0** |
| ⭐ おすすめ | **0** |
| 🔄 最終更新 | **2025年12月5日金曜日 3:39:03 UTC** |

</div>

---

## 🤝 貢献方法

貢献を歓迎します！以下の方法でプロンプトを提出できます：

### 🐛 GitHub Issue

1. Click [**新しいプロンプトを提出**](https://github.com/YouMind-OpenLab/awesome-gemini-3-prompts/issues/new?template=submit-prompt.yml)
2. フォームにプロンプトの詳細と画像を記入
3. 提出してチームのレビューを待つ
4. 承認された場合（`approved` ラベルを追加します）、CMS に自動的に同期されます
5. プロンプトは 4 時間以内に README に表示されます

**注意：** 品質管理のため、GitHub Issues 経由の提出のみ受け付けています。

詳細なガイドラインについては [CONTRIBUTING.md](docs/CONTRIBUTING.md) を参照してください。

---

## 📄 ライセンス

[CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) の下でライセンスされています。

---

## 🙏 謝辞

- [Payload CMS](https://payloadcms.com/)
- [youmind.com](https://youmind.com)

---

## ⭐ スター履歴

[![Star History Chart](https://api.star-history.com/svg?repos=YouMind-OpenLab/awesome-gemini-3-prompts&type=Date)](https://star-history.com/#YouMind-OpenLab/awesome-gemini-3-prompts&Date)

---

<div align="center">

**[🌐 Web ギャラリーで見る](https://youmind.com/gemini-3-prompts)** •
**[📝 プロンプトを提出](https://github.com/YouMind-OpenLab/awesome-gemini-3-prompts/issues/new?template=submit-prompt.yml)** •
**[⭐ このリポジトリにスターを付ける](https://github.com/YouMind-OpenLab/awesome-gemini-3-prompts)**

<sub>🤖 この README は自動生成されています。最終更新： 2025-12-05T03:39:03.683Z</sub>

</div>
