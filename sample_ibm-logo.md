---
marp: true
theme: ibm-logo
paginate: true
header: "IBM Theme for Marp"
footer: '© 2025 IBM Corporation. All rights reserved.'
---

<!-- _class: title -->
<div class="left">

  # Marp Theme@IBM

  ## 1つのテーマで多彩なカラーバリエーションを実現

  <p class="date">Jan 1, 2025</p>
  
  <div class="profile">
    <img src="https://avatars.githubusercontent.com/u/54477647?s=400&u=933d42c82fd2126c0c149410ba06fe7ac7d42ad0&v=4"/>
    <div class="content">
      <div class="name">Bunzo Akama</div>
      <div class="job-title">IT Specialist - Data Science Lab., DX Solution Center</div>
      <div class="company">IBM Systems Engineering</div>
    </div>
  </div>

  </div>

<div class="right">
  <img 
    class="illustration" 
    src="https://images.unsplash.com/photo-1636955735635-b4c0fd54f360?q=80&w=2070&auto=format&fit=crop&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D" >
</div>

---

# 基本的な使い方

この統一テーマでは、セクションごとに異なる色調を適用できます。

- デフォルトはIBMブルー
- セクションごとに `<!-- _class: 色名 -->` を指定
- カラーバリエーション、グラデーション、ダークテーマに対応
  - カラーパレット:  https://www.ibm.com/design/language/color

> このスライドはデフォルトのブルーテーマを使用しています。

---

<!-- _class: red -->
# 赤色テーマ


## 特徴
- 注意喚起や警告に最適
- セキュリティ関連のトピックに
- インパクトのある発表に

```python
def security_alert():
    if risk_level > THRESHOLD:
        send_notification("警告: リスクを検出")
        log_event("セキュリティアラート")
```


---

<!-- _class: green -->
# 緑色テーマ

## 特徴
- 成長や持続可能性を表現
- 環境関連のトピックに
- 安定と信頼を伝えるデザイン

| 四半期 | 成長率 | 新規顧客 |
|-------|-------|---------|
| Q1    | 12%   | 158 |
| Q2    | 15%   | 203 |
| Q3    | 18%   | 247 |
| Q4    | 22%   | 312 |

---

<!-- _class: purple -->
# 紫色テーマ

<div class="columns">
<div>

## 特徴
- 創造性と革新を表現
- 先進的なコンセプトに
- 高級感のある印象を与える

</div>
<div>

> 私たちのアプローチは、既存の枠組みを超えて新たな価値を創造することにあります。顧客体験を根本から見直し、AIと人間の創造性を融合させた革新的なソリューションを提供します。

</div>
</div>

---

<!-- _class: teal -->
# ティール色テーマ

<div class="columns">
<div>

## 特徴
- バランスと調和を表現
- 医療や健康関連のトピックに
- 落ち着きと専門性を伝える

</div>
<div>

### 重要ポイント
1. データの整合性
2. システム間の連携
3. <mark>セキュアな通信</mark>
4. スケーラブルな設計

</div>
</div>

---

<!-- _class: magenta -->
# マゼンタ色テーマ

マーケティングやデザイン関連のプレゼンテーションに最適です。

<div class="columns">
<div>

## ブランディング要素
- ロゴデザイン
- カラーパレット
- タイポグラフィ
- ビジュアルアセット

</div>
<div>

## マーケティング戦略
- ターゲットオーディエンス分析
- コンテンツマーケティング
- ソーシャルメディア戦略
- パフォーマンス指標

</div>
</div>

---

<!-- _class: cyan -->
# シアン色テーマ

テクノロジーやデータ分析のプレゼンテーションに適しています。

```javascript
// データ処理パイプライン
function processData(rawData) {
  const filtered = rawData.filter(item => item.value > threshold);
  const aggregated = groupBy(filtered, 'category');
  return analyze(aggregated);
}
```

> クラウドネイティブなアーキテクチャにより、スケーラビリティと耐障害性を両立しています。

---

<!-- _class: gray -->
# グレー色テーマ

ビジネスや企業報告などフォーマルな場面に適したニュートラルな印象です。

<div class="columns">
<div>

## 2025年度計画
- 市場シェア拡大
- 製品ポートフォリオ見直し
- コスト最適化
- 人材育成・強化

</div>
<div>

## リスク対応
- 市場変動への対応
- 競合動向の監視
- 規制変更への準備
- 内部統制の強化

</div>
</div>

---

<!-- _class: warm-gray -->
# ウォームグレーテーマ

歴史や文化、教育関連のトピックに温かみのある印象を与えます。

<div class="columns">
<div>

## 教育プログラム
- 基礎コース
- 応用コース
- 専門講座
- メンタリング

</div>
<div>

> 学びは単なる知識の習得ではなく、思考力や創造性を育む過程です。私たちのアプローチは、体験を通じた深い理解を促進します。

</div>
</div>

---

<!-- _class: cool-gray -->
# クールグレーテーマ

建築やプロダクトデザインなど、モダンで洗練された印象を与えます。

<div class="columns">
<div>

## デザイン原則
- 機能性
- 美しさ
- 持続可能性
- ユーザー中心設計

</div>
<div>

## 実装ステップ
1. コンセプト設計
2. プロトタイピング
3. ユーザーテスト
4. 製品化・展開

</div>
</div>

---

<!-- _class: blue-gradient smalltext -->
# グラデーションテーマ

グラデーション背景を使用すると、より視覚的なインパクトを与えられます。

> このスライドは青色のグラデーション背景を使用しています。

他にも以下のグラデーションが利用可能です:
- red-gradient
- green-gradient
- purple-gradient
- teal-gradient
- magenta-gradient
- cyan-gradient
- gray-gradient

---

<!-- _class: dark-blue -->
# ダークブルーテーマ

夜間のプレゼンテーションや、視覚的なインパクトを与えたい時に。

```javascript
// ナイトモード切替機能
function toggleDarkMode() {
  const isDark = localStorage.getItem('darkMode') === 'true';
  document.body.classList.toggle('dark-theme', !isDark);
  localStorage.setItem('darkMode', !isDark);
}
```

---

<!-- _class: dark-purple -->
# ダークパープルテーマ

神秘的で高級感のある印象を与えるダークテーマです。

<div class="columns">
<div>

## 特徴
- 高いコントラスト
- 洗練された印象
- 視覚的なインパクト
- 夜間のプレゼンに最適

</div>
<div>

> イノベーションの本質は未知の領域へ踏み出す勇気にあります。私たちは常識の境界を超え、新たな可能性を切り開いていきます。

</div>
</div>

---

<!-- _class: dark-green -->
# ダークグリーンテーマ

環境や自然科学のトピックに適した深みのあるテーマです。

<div class="columns">
<div>

## 調査結果
- 生物多様性の向上
- 炭素吸収量の増加
- 水源の浄化
- 地域生態系の回復

</div>
<div>

## 今後の展望
- 保全地域の拡大
- コミュニティの参画
- 長期モニタリング
- 国際連携の強化

</div>
</div>

---

<!-- _class: lead -->
# スタイルの組み合わせ

カラーとレイアウトを自由に組み合わせられます

---

<!-- _class: red primary -->
# 赤色の強調スライド

- 重大な警告や注意事項
- 緊急性の高い内容
- 絶対に見逃せないポイント

---

<!-- _class: smalltext purple -->
# 参考文献・リソース

<div class="columns">
<div>

- Anderson, J. (2023). "Color Theory in Modern Presentations". _Design Quarterly_, 45(2), 78-92.
- Martinez, S. & Lee, K. (2024). "The Impact of Visual Design on Information Retention". _Journal of Communication Studies_, 31(1), 112-128.
- Wang, H. (2025). "Cognitive Load and Presentation Design". _International Journal of Human-Computer Interaction_, 17(3), 203-219.
- IBM Design Language Team. (2024). "IBM Design Language: Color Guidelines". IBM Corporation.

</div>
<div>

- Roberts, A. & Johnson, T. (2023). "Effective Slide Design Principles for Technical Presentations". _IEEE Professional Communication_, 66(1), 45-61.
- Smith, R. (2024). "Accessibility in Slide Design". _Universal Design Quarterly_, 12(4), 88-103.
- Yamamoto, K. (2025). "Cultural Perception of Colors in Business Presentations". _Cross-Cultural Business Studies_, 28(2), 145-162.

</div>
</div>

---

<!-- _class: lead cyan-gradient -->
# テーマのカスタマイズ方法

セクションを飾るその他のテクニック

---

<!-- _class: purple smalltext -->
# CSS変数のカスタマイズ

テーマはCSS変数を使用しているため、必要に応じて簡単に変更できます。

```css
:root {
  /* プライマリーカラーの変更 */
  --primary-color: #491d8b;
  --secondary-color: #6929c4;
  --accent-color: #8a3ffc;
  
  /* フォントの変更 */
  --main-font: 'IBM Plex Sans', sans-serif;
  --code-font: 'IBM Plex Mono', monospace;
}
```

> 独自のカラーやフォントを設定することでブランドに合わせたテーマを作成できます。

---

<!-- _class: green primary -->
# 複合クラスの活用

クラスを組み合わせることで、さらに多彩な表現が可能です。

<div class="columns">
<div>

## 組み合わせ例
- `red primary` - 赤色の強調スライド
- `blue-gradient lead` - グラデーションのタイトル
- `dark-purple tinytext` - 小さいテキストの暗い紫テーマ

</div>
<div>

## ヘルパークラス
- `.center-text` - テキストを中央揃え
- `.full-width` - 要素を幅いっぱいに
- `.center-image` - 画像を中央揃え

</div>
</div>

---

<!-- _class: lead -->
# Thnaks.

## カラフルで印象的なプレゼンテーションを
---

<!-- _class: logo -->
logo /default

---

<!-- _class: logo cool-gray -->
logo /cool-gray/warm-gray

---

<!-- _class: logo dark-green -->
logo /dark-blue, dark-green, dark-purple

---

<!-- _class: logo-rebus -->
logo-rebus /default

---

<!-- _class: logo-rebus cool-gray -->
logo-rebus /cool-gray/warm-gray

---

<!-- _class: logo-rebus dark-green -->
logo-rebus /dark-blue, dark-green, dark-purple

---

<!-- _class: logo-rebus-v -->
logo-rebus-v /default

---

<!-- _class: logo-rebus-v cool-gray -->
logo-rebus-v cool-gray/warm-gray

---

<!-- _class: logo-rebus-v dark-green -->
logo-rebus-v /dark-blue, dark-green, dark-purple

