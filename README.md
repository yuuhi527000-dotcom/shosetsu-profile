# 📖 小説家のプロフィール

小説作家向けのプロフィールカードを無料で作成・PNG ダウンロードできる Web サービスです。

なろう・カクヨム・X（Twitter）のリプライ用画像を1分で生成できます。

## ✨ 機能

- 9テーマ × 10アクセントカラーの組み合わせ
- アイコン画像アップロード（正方形）
- ジャンル・活動場所・代表作タイトルの設定
- 累計PV数・更新頻度・執筆スタイルのステータス表示
- Canvas API による PNG ダウンロード
- Google AdSense 広告枠対応

## 🗂️ ファイル構成

```
shosetsu-profile/
├── index.html      # メインファイル（全機能が1ファイルに完結）
└── README.md
```

## 🚀 デプロイ（Vercel）

### 方法1：Vercel CLI

```bash
npm i -g vercel
vercel --prod
```

### 方法2：GitHub 連携

1. このリポジトリを Vercel にインポート
2. フレームワーク設定は **Other** を選択
3. そのままデプロイ

## 📢 Google AdSense の設定

`index.html` 内の以下4箇所を自分のIDに書き換えてください。

| 置換前 | 置換後 |
|---|---|
| `ca-pub-YOUR_ADSENSE_CLIENT_ID` | `ca-pub-XXXXXXXXXXXXXXXX`（全4箇所） |
| `YOUR_AD_SLOT_TOP` | ページ上部用スロットID |
| `YOUR_AD_SLOT_BEFORE_BTN` | 生成ボタン上スロットID |
| `YOUR_AD_SLOT_AFTER_BTN` | 生成ボタン下スロットID |
| `YOUR_AD_SLOT_BOTTOM` | ページ下部スロットID |

## 🔧 今後のアップデート予定

- [ ] QRコード生成機能
- [ ] カードサイズ切り替え（正方形・縦長）
- [ ] 秋・夏テーマ追加

## 📄 ライセンス

MIT License — 生成したカードの著作権は利用者に帰属します。商用利用可。
