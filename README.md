# 🐻 おやすみ宣言 - 睡眠ピーク予測アプリ

## 🌙 概要

**「おやすみ宣言」** は、あなたの睡眠習慣を記録・可視化し、AIが眠くなるタイミングを予測してくれるWebアプリです。

- **眠気を感じた時間**
- **実際に寝た時間・起きた時間**
- **1日の運動量（カロリー）**
- **夜更かしの理由**

これらをもとに、**Gemini AIがパーソナルな生活アドバイス**をしてくれます。

---

## 🧠 背景

リモートワークの増加により、「**睡眠時間は増えているが、質は下がっている**」という課題を感じたのがきっかけです。

眠気のピークを逃すことで、寝つきが悪くなることに着目し、  
**「いつ眠くなって、いつ寝たか」の記録をもとに生活改善のヒントを得られる仕組み**を作りたいと考えました。

---

## 🔧 技術スタック

| 技術 | 理由・補足 |
|------|------------|
| **React + Vite** | 開発スピードを重視。Reactはコンポーネント分割が容易でチーム開発に向いている。|
| **Tailwind CSS + shadcn/ui** | UIの構築を素早く、かつ美しく仕上げるため。|
| **Node.js + Express** | 軽量かつ学習コストが低く、メンバーの習熟度を考慮。|
| **PostgreSQL** | 安定性が高く、スキーマ設計を活かせるリレーショナルDB。|
| **Gemini AI API** | 記録データからパーソナライズされたアドバイスを生成。|

---

## 🧩 主な機能

- ✅ 睡眠記録（眠気・就寝・起床）
- ✅ 運動量と夜更かしの内容の記録
- ✅ AI（Gemini）によるパーソナルアドバイス
- ✅ 時間帯に応じた応援メッセージ
- ✅ 睡眠時間の自動計算
- ✅ 直近記録の確認機能（モックデータ）

---

## 🔨 担当・役割（Responsibility）

**主にバックエンドを担当しました。**

- API設計・実装（Express）
- DB設計（PostgreSQL）
- Gemini API連携ロジックの構築
- GitHubでのリポジトリ管理、ブランチ戦略
- チームメンバーの技術支援・進行役も兼任

---

## 👨‍💻 開発の工夫（How we worked）

- 定期ミーティングで認識齟齬を防ぐよう努めました
- 初学者がいても貢献しやすいよう技術選定を調整
- 「チーム開発」自体を学びの一環として重視
- 開発時間が短いため、学習コストと効率のバランスを常に意識

---

## 📈 今後の展望（Next Step）

- 📊 **グラフ化**：1週間分のカロリー消費量・睡眠時間の可視化
- 👥 **ユーザー認証**：日付ごとのユーザー記録管理
- 🤝 **友達機能**：睡眠習慣の共有や応援機能
- 🤒 **体調予測**：体調ログとの連携によるアドバイス精度向上

---

## 📝 フィードバック
- 記録にとどまらず、**他者との共有・競争・気づき**があればもっと使いたくなる

---
