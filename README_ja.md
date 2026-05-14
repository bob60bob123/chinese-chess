# 楚漢争雄 - 中国将棋

<p align="center">
  <img src="https://img.shields.io/badge/version-1.0.0-blue.svg" alt="バージョン">
  <img src="https://img.shields.io/badge/license-MIT-green.svg" alt="ライセンス">
  <img src="https://img.shields.io/badge/HTML5-Game-orange.svg" alt="HTML5">
</p>

**楚漢争雄** は純粋な HTML5 実装的中国将棋ゲームです。外部依存なしで、ブラウザに直接てプレイできます。人vs人モードと人vs AIモードをサポートしています。

[English](README.md) | [简体中文](README_zh-CN.md) | [日本語](README_ja.md) | [한국어](README_ko.md) | [Español](README_es.md)

---

## 機能

### 将棋ルール
- ✅ 完全な中国将棋ルールの実装
- ✅ 7 種類の駒：帥/将、仕/士、相/象、车/俥、馬、砲/炮、兵/卒
- ✅ 足を妨げるルール、眼賽塞ぎルール
- ✅ 将と帥の対面ルール
- ✅ 王手-check、詰み-checkmate、動きなし-stalemate 判定

### ゲームモード
- 🔹 **人vs人** - 二人でプレイ
- 🔹 **人vs AI** - AI と对战、三段階の難易度

### AI 難易度
| 難易度 | 説明 |
|--------|------|
| 入門 | 初心者向け、AI は間違うことがあります |
| 中級 | 基本的な攻守の意識あり |
| 上級 | 布局と戦術に擅长 |

### 機能
- 🎵 駒を動かす音、取る音、王手告知音
- 📜 棋譜記録
- ↩️ 待った機能
- 🔄 重新開始

---

## 遊び方

### 方法一：直接開く
`index.html` ファイルをダブルクリックし任意のモダンブ라우ザで開きます。

### 方法二：ローカルサーバー
```bash
# Python 3
python -m http.server 8080

# Node.js
npx serve .

# PHP
php -S localhost:8080
```
`http://localhost:8080` にアクセス

---

## 技術スタック

| 技術 | 説明 |
|------|------|
| HTML5 | セマンティック構造 |
| CSS3 | 盤面スタイル、アニメーション |
| JavaScript | ゲームロジック、AI、インタラクション |

- **ゼロ依存** - 純粋なネイティブ実装
- **レスポンシブ** - デスクトップとモバイル対応
- **アクセシビリティ** - ARIA ラベル対応

---

## ブラウザ互換性

| ブラウザ | 対応バージョン |
|----------|----------------|
| Chrome | 80+ |
| Firefox | 75+ |
| Safari | 13+ |
| Edge | 80+ |

---

## プロジェクト構造

```
chinese-chess/
├── index.html        # メインページ（全コード 포함）
├── SPEC.md          # プロジェクト仕様
├── README.md         # 英語
├── README_zh-CN.md   # 簡体字中文
├── README_ja.md      # 日本語
├── README_ko.md      # 한국어
├── README_es.md      # Español
├── LICENSE           # MIT ライセンス
└── .gitignore        # Git 無視ファイル
```

---

## 開発

### テスト実行
ブラウザコンソールで：
```javascript
runSelfTests()
```

---

## ライセンス

MIT ライセンス采用（[LICENSE](LICENSE)）。