<!-- 🌷 honoka-lab / hello-web README.md -->

<p align="center">
  <img src="https://raw.githubusercontent.com/honoka-lab/hello-web/main/cover.png" alt="資産推移グラフ" width="80%">
</p>

<h1 align="center">🌷 資産推移グラフ（2017〜2025）</h1>
<p align="center">
  <b>家族の成長とともに歩む「資産の記録」</b><br>
  <a href="https://honoka-lab.github.io/hello-web/" target="_blank">
    <img src="https://img.shields.io/badge/Webページを見る-ffb6c1?style=for-the-badge&logo=githubpages&logoColor=white">
  </a>
</p>

---

## 📊 プロジェクト概要

このサイトは、2017年から2025年までの資産推移を可視化したWebグラフです。  
エクセルで管理していた家計データをWeb化し、  
棒グラフで資産額・折れ線で月ごとの増減を表示しています。

💡 **目的**  
家族で「数字で歩みを見る」楽しさを共有すること。

---

## 💻 構成

| ファイル | 内容 |
|-----------|------|
| `index.html` | グラフ本体（Chart.jsを使用） |
| `README.md` | このページ（プロジェクト紹介） |
| `assetData` | JavaScript内で定義した月次資産データ |

---

## 🎨 グラフの特徴
- **棒グラフ**：資産額（万円）  
- **折れ線グラフ**：前月からの増減額  
- **カラー**：やさしいピンク×ミントグリーンで家族向けデザイン  
- **拡張性**：`assetData`に1行追加するだけで自動更新  

---

## 🚀 公開ページ
👉 [https://honoka-lab.github.io/hello-web/](https://honoka-lab.github.io/hello-web/)

---

## 🛠 更新手順
1. `index.html` の `assetData` に新しい月のデータを追記  
2. 変更を **Commit**（保存）  
3. 数分後にWebページが自動で更新されます ✅

---

## 💡 今後のアイデア
- 年ごとの集計／平均増加率の自動計算  
- テーマ切り替え（春・夏・秋・冬）  
- 家族イベントとのタイムライン連携  

---

<p align="right">
  📅 最終更新日：2025年11月2日  
  <br>👩‍💻 作成者：<b>honoka-lab</b>
</p>
