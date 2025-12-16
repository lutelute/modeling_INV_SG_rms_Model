# modeling_INV_SG_rms_Model

## 概要

このプロジェクトは、物理モデルから状態空間表現への導出を行うためのモデリングツールです。

## ファイル構成

- `index.html` - 物理モデルから状態空間表現への導出を説明するHTMLドキュメント（最新版）
- `docs/versions/` - 過去のバージョン
  - `physical_modeling_derivation.html` - 初期版
  - `physical_modeling_v2.html` - v2.0
  - `physical_modeling_v2_1.html` - v2.1  
  - `physical_modeling_v2_2.html` - v2.2
  - `physical_modeling_v2_3.html` - v2.3
  - `physical_modeling_v2_4.html` - v2.4（最新）
- `docs/inverter_models_comparison.html` - インバータモデル比較（GFL/GFM/SGモデル）
- `docs/interactive_stability_analysis.html` - インタラクティブ安定性解析ツール

## 使用方法

### オンライン閲覧（GitHub Pages）

- **メインコンテンツ**: https://lutelute.github.io/modeling_INV_SG_rms_Model/
- **インバータモデル比較**: https://lutelute.github.io/modeling_INV_SG_rms_Model/docs/inverter_models_comparison.html
- **🎯 安定性解析ツール**: https://lutelute.github.io/modeling_INV_SG_rms_Model/docs/interactive_stability_analysis.html

### 教育・学習リソース

1. **物理モデリング基礎** - メインページで物理モデルから状態空間表現への導出過程を学習
2. **モデル比較研究** - インバータモデル比較ページでGFL/GFM/SGモデルの違いを理解
3. **🔧 インタラクティブ安定性解析** - パラメータを調整してリアルタイムで安定性を評価
   - 同期発電機（SG）モデル
   - Grid-Following（GFL）インバータ
   - Grid-Forming（GFM）インバータ
   - 固有値プロット（s平面）
   - ステップ応答解析

または、ローカルでHTMLファイルをWebブラウザで開いて、物理モデルの数式展開と状態空間表現への変換過程を確認できます。

## 特徴

- 日本語による詳細な数式解説
- KaTeX によるLaTeX数式レンダリング
- レスポンシブデザインに対応
- 教育・学習目的での使用に最適化

## 環境要件

- モダンなWebブラウザ
- インターネット接続（KaTeXライブラリ読み込みのため）

## ライセンス

このプロジェクトは教育・研究目的での使用を想定しています。