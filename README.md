# けいばAI

AIを活用して競馬予想を自動生成・記録・改善できるRailsアプリケーションです。  
ユーザーはレース情報を入力するだけで、Gemini APIによる予想結果が生成されます。

---

## 開発言語

- Ruby 3.4.5  
- Rails 8.0.2.1

---

## 実行手順

```bash
# リポジトリをクローン
$ git clone git@github.com:Naoyukisan/keiba-ai.git
$ cd keiba-ai

# 依存関係をインストール
$ bundle install

# DB作成・マイグレーション
$ rails db:create && rails db:migrate

# サーバ起動
$ rails s
```

---

## 関連ドキュメント

以下の資料は Google Drive フォルダにまとめています。  
➡️ [📂 ドキュメント一式（Google Drive）](https://drive.google.com/drive/folders/1eoSSmyzq5_9JbOi5T4XQzosxz3btLFkd?usp=drive_link)

| ドキュメント名 | 説明 | リンク |
|----------------|------|--------|
| ✅ チェックシート | 開発・設計・レビュー用の品質チェック項目 | 同上 |
| 📘 カタログ設計 | 機能一覧・画面構成・業務フローを定義 | 同上 |
| 🧾 テーブル定義書 | DB設計・項目定義・リレーション設計 | 同上 |
| 🖼 ワイヤーフレーム | 画面UIの構成案・ページ遷移図 | 同上 |

---

