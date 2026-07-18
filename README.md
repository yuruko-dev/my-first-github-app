# AI業務自動化ツール ランディングページ

AIを活用した業務自動化サービスの紹介ランディングページです。

---

## プロジェクト概要

「AI業務自動化ツール」は、企業の繰り返し業務をAIで自動化し、チームの生産性向上を支援するサービスです。  
本リポジトリは、そのサービスを紹介するランディングページ（静的HTML）のソースコードです。

白と青を基調としたモダンなデザインで構築しており、PC・スマートフォン・タブレットに対応したレスポンシブレイアウトを採用しています。

---

## 使用技術

| 技術 | 詳細 |
|------|------|
| HTML5 | セマンティックなマークアップ |
| CSS3 | Flexbox / Grid / カスタムプロパティ / アニメーション |
| Google Fonts | Noto Sans JP |
| GitHub Pages | 静的サイトホスティング（予定） |

> バックエンド・ビルドツール不要。`index.html` 単体で動作します。

---

## 機能一覧

### ページ構成

| セクション | 内容 |
|------------|------|
| ヘッダー | スティッキーナビゲーション・「無料相談」CTAボタン |
| ヒーロー | メインキャッチコピー・統計数値（4項目）・CTAボタン2種 |
| AIでできること | 6つの機能紹介カード（書類生成・メール対応・データ分析など） |
| 開発実績 | 導入事例カード（随時追加可能な構造） |
| お問い合わせ | メールリンク付きCTAセクション |
| フッター | コピーライト表記 |

### UI / UX

- スクロール時に追従するスティッキーヘッダー
- スムーズスクロールナビゲーション
- カードホバー時のアニメーション
- グラデーション背景・ブラーエフェクト
- レスポンシブ対応（モバイルでナビを非表示化）

---

## 使い方

### 1. リポジトリをクローン

```bash
git clone https://github.com/yuruko-dev/my-first-github-app.git
cd my-first-github-app
```

### 2. ブラウザで開く

```bash
# そのままファイルを開く
open index.html          # macOS
start index.html         # Windows
xdg-open index.html      # Linux
```

ビルド不要・依存パッケージなし。`index.html` をブラウザで開くだけで動作します。

### 3. 開発実績を追加する

`index.html` 内の `#works` セクションにある `.works-grid` に、以下のカードを追加してください。

```html
<div class="work-card">
  <div class="work-thumb" style="background: linear-gradient(135deg,#e8f0fd,#c7d8fb);">🏢</div>
  <div class="work-body">
    <span class="work-tag">業種タグ</span>
    <div class="work-title">事例タイトル</div>
    <div class="work-desc">事例の説明文をここに記載します。</div>
  </div>
</div>
```

### 4. お問い合わせ先を変更する

`index.html` 内の以下の箇所をご自身のメールアドレスに変更してください。

```html
<a class="btn-cta" href="mailto:contact@example.com">お問い合わせする →</a>
```

---

## 今後追加予定の機能

- [ ] お問い合わせフォームの実装（フォーム送信機能）
- [ ] GitHub Pages による本番公開
- [ ] アニメーション強化（スクロールトリガーのフェードイン）
- [ ] 料金プラン紹介セクションの追加
- [ ] お客様の声・テスティモニアルセクションの追加
- [ ] 多言語対応（日本語 / 英語）
- [ ] ダークモード対応
- [ ] OGP・SEOメタタグの整備

---

## ライセンス

This project is licensed under the [MIT License](LICENSE).
