# KPJ Betimo 資料ポータル

KPJ Betimoプロジェクトの各種資料をまとめたポータルサイトです。

## 📚 資料一覧

### 1. Slack × LINE WORKS 統合提案書
- **URL**: https://goalgoda.github.io/slack-lineworks-proposal/slack-lineworks/
- **内容**: 
  - 完全同期システムの技術提案
  - コスト見積もり（フル開発版・Zapier版）
  - 実装スケジュール
  - システム構成図

### 2. KPJ Betimo 運営体制（統合版）
- **URL**: https://goalgoda.github.io/slack-lineworks-proposal/kpj-integrated/
- **内容**: 
  - 運営体制の全体像
  - 組織図
  - 役割分担
  - 1ページに統合された概要版

### 3. KPJ Betimo 運営体制（複数ページ版）
- **URL**: https://goalgoda.github.io/slack-lineworks-proposal/kpj-multipage/
- **内容**: 
  - 詳細な運営体制説明
  - プレゼンテーション形式
  - 各部門の詳細説明
  - 複数ページ構成

## 🔐 アクセス方法

すべての資料はパスワード保護されています。
各資料のURLにアクセスすると、パスワード入力画面が表示されます。

## 🏗️ プロジェクト構造

```
/
├── README.md                # このファイル
├── index.html              # 資料選択メニュー
├── slack-lineworks/        # Slack × LINE WORKS提案書
│   ├── index.html         # 提案書本体
│   └── auth.html          # パスワード認証ページ
├── kpj-integrated/         # KPJ運営体制（統合版）
│   ├── index.html         # 統合版本体
│   └── auth.html          # パスワード認証ページ
└── kpj-multipage/          # KPJ運営体制（複数ページ版）
    ├── index.html         # 複数ページ版本体
    └── auth.html          # パスワード認証ページ
```

## 📝 更新履歴

- 2025/07/13 - 3つの資料を別フォルダに再構成
- 2025/07/13 - Zapier版（30分構築）オプションを追加
- 2025/07/13 - KPJ運営体制資料を追加
- 2025/07/13 - 初版公開

## 🛠️ 技術仕様

- **ホスティング**: GitHub Pages
- **認証方式**: sessionStorageベースの簡易認証
- **対応ブラウザ**: Chrome, Firefox, Safari, Edge（最新版）
- **レスポンシブ対応**: モバイル・タブレット・デスクトップ

## 📞 お問い合わせ

KPJ Betimo プロジェクトチーム

---

© 2025 KPJ Betimo. All rights reserved.