# kintai - LINE勤怠管理システム

🚀 LINEで簡単に勤怠管理ができる革新的なシステム

## 📋 概要

**kintai**は、LINE Messaging APIとGoogle Apps Scriptを活用した無料の勤怠管理システムです。従業員はLINEから簡単に出勤・退勤の打刻ができ、管理者は自動計算された勤怠データをリアルタイムで確認できます。

## ✨ 主な機能

### 🔄 LINE勤怠Bot
- **簡単打刻**: LINEから「出勤」「退勤」「休憩開始」「休憩終了」を送信するだけ
- **企業認証**: 企業コードによる安全なユーザー登録
- **複数企業対応**: 一つのシステムで複数の企業を管理
- **自動計算**: 労働時間・休憩時間の自動計算

### 📊 勤怠ビューア（LIFF）
- **月別表示**: 詳細な勤怠記録を月別に確認
- **リアルタイム更新**: 最新の勤怠情報をすぐに確認
- **レスポンシブデザイン**: スマートフォン・タブレット対応
- **グラフィカル表示**: 見やすい表形式とサマリー

### 🔒 セキュリティ・管理機能
- **Google Spreadsheet連携**: 安全なクラウドデータ管理
- **企業別データ分離**: 企業ごとに独立したデータ管理
- **バックアップ**: Google Drive自動バックアップ

## 🌐 デモ・公開ページ

### 📄 サービス紹介ページ
- **URL**: `https://あなたのユーザー名.github.io/kintai-viewer/landing.html`
- 無料申し込みフォーム付きのランディングページ

### 📊 勤怠ビューア
- **URL**: `https://あなたのユーザー名.github.io/kintai-viewer/index.html`
- LINEアプリから利用する勤怠確認ページ

## 🚀 導入方法

### 1. LINE Bot設定
1. LINE Developersコンソールでチャネルを作成
2. Messaging API設定を有効化
3. Webhook URLにGASのデプロイURLを設定

### 2. Google Apps Script設定
1. `kintai/コード.js`をGASプロジェクトに配置
2. スプレッドシートを作成し、IDを設定
3. Webアプリとしてデプロイ

### 3. LIFF設定
1. LINE DevelopersでLIFFアプリを作成
2. `index.html`のLIFF IDを更新
3. GitHub Pagesで公開

## 💰 料金

**完全無料**でご利用いただけます
- 初期費用: ¥0
- 月額費用: ¥0
- 従業員数制限: なし
- 機能制限: なし

## 📞 サポート・お問い合わせ

### 🆓 無料申し込み
[サービス紹介ページ](./landing.html)からお申し込みください

### 🏢 カスタム開発・業務改善
その他の業務改善システムの開発もお受けしています：
- 在庫管理システム
- 顧客管理システム
- 売上分析ツール
- 業務自動化ツール

## 🛠️ 技術仕様

### システム構成
- **Frontend**: HTML5, CSS3, JavaScript (LIFF)
- **Backend**: Google Apps Script
- **Database**: Google Spreadsheet
- **API**: LINE Messaging API
- **ホスティング**: GitHub Pages

### 対応ブラウザ
- LINEアプリ内ブラウザ（推奨）
- Chrome, Safari, Firefox（デバッグ用）

## 📁 ファイル構成

```
kintai-viewer/
├── landing.html          # サービス紹介・申し込みページ
├── index.html            # 勤怠ビューア（LIFF）
├── index_stable.html     # 安定版バックアップ
├── README.md            # このファイル
└── "/                   # その他のファイル
```

## 🚀 GitHub Pagesでの公開手順

1. **リポジトリ設定**
   ```bash
   git add .
   git commit -m "Add landing page and documentation"
   git push origin main
   ```

2. **GitHub Pages有効化**
   - GitHub リポジトリの Settings → Pages
   - Source: "Deploy from a branch"
   - Branch: "main" / "root"
   - Save

3. **公開URL確認**
   - `https://ユーザー名.github.io/kintai-viewer/landing.html`

## 📈 今後の拡張予定

- [ ] 打刻修正機能
- [ ] 管理者ダッシュボード
- [ ] CSV出力機能
- [ ] LINEリッチメニュー対応
- [ ] プッシュ通知機能
- [ ] 多言語対応

## 📄 ライセンス

このプロジェクトは教育・商用利用可能です。

## 🤝 貢献

バグ報告や機能要望は Issues でお知らせください。プルリクエストも歓迎いたします。

---

💡 **kintai**で、あなたの会社の勤怠管理を革新しませんか？

[🚀 無料で始める](./landing.html) | [📊 デモを見る](./index.html) 