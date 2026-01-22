# RINslider

モダンなウェブサイト向けに設計された、軽量なVanilla JavaScriptスライダー：高速で、アクセシブル、依存なし。

このリポジトリは、RINsliderの**CDN向けコンパイル済みファイル**を提供します。

👉 **完全なドキュメント＆サンプル:**  
[https://rinslider.com](https://rinslider.com)

---

## ✨ 主な機能

- 🚀 純粋なVanilla JavaScript – 依存なし
- 📱 レスポンシブ対応・タッチ対応
- 🖱️ マウスドラッグ & 💨 慣性スクロール
- ♾️ 無限ループ対応
- ⏯️ 自動再生 + 進行バー
- 🎯 ドット・矢印・サムネイルナビゲーション
- ♿ アクセシビリティ対応 (ARIA, キーボード, モーション削減)
- 🎭 `prefers-reduced-motion`対応
- 🎢 ネストスライダー対応
- 🌍 RTL (右から左) 完全対応
- 🎬 オプションのパララックス効果
- 🖼️ 遅延読み込み、キャプション、スライド間のギャップ対応

---

## 📦 CDNによるインストール（推奨）

### CSS
```
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/rin-ws/rin-slider-cdn@v1.0.0/slider.min.css">
```
### JavaScript
```
<script src="https://cdn.jsdelivr.net/gh/rin-ws/rin-slider-cdn@v1.0.0/slider.min.js"></script>
```
## 🚀 クイックスタート
```
<div id="mySlider" data-slider>
  <div class="slide">スライド 1</div>
  <div class="slide">スライド 2</div>
  <div class="slide">スライド 3</div>
</div>

<script>
  new Slider('#mySlider', {
    infinite: true,
    autoplay: true,
    dots: true,
    arrows: true
  });
</script>
```
## 📚 ドキュメント
完全なドキュメントには以下が含まれます：

設定オプションの完全リファレンス

公開APIメソッド

アクセシビリティの詳細

RTL、ネストスライダー、パララックス、遅延読み込み対応

各種フレームワーク（React, Vue, WordPressなど）での使用例

👉 RINslider ドキュメント
https://rinslider.com

## 🔖 バージョン管理
RINsliderはセマンティックバージョニングを採用しています：

- PATCH – バグ修正

- MINOR – 後方互換性のある新機能

- MAJOR – 後方互換性のない変更

## ❤️ サポート
RINsliderはボランティアによるオープンソースプロジェクトです。
便利だと思ったら、以下でサポートできます：

- Patreon: https://www.patreon.com/rinslider

- Ko-fi: https://ko-fi.com/rinws

すべての機能は無料で利用可能です。サポートは任意です。

## 📄 ライセンス
MIT
