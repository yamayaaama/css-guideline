# css-guideline

## 概要 (overview)
このリポジトリは、プロジェクトでのCSSの一貫性を維持するためのスタイルガイドです。
命名規則、カスタムプロパティ、レイアウト方針などを記載しております。
CSSのスタイルを一元化し、再利用しやすい形で管理することを目的としています。


## 目次 (Table of Contents)
- [概要(overview)](#概要-overview)
- [スタイルガイド (Style Guide)](#スタイルガイド-style-guide)
- [命名規則 (Naming Conventions)](#命名規則-naming-conventions)
- [共通クラス(Common Classes)](#共通クラス-common-classes)
- [レイアウトガイドライン(Layout Guidelines)](#レイアウトガイドライン-layout-guidelines)
- [コード例 (Code Examples)](#コード例-code-examples)
- [更新履歴 (Changelog)](#更新履歴-changelog)
- [参考文献 (References)](#参考文献-references)

## スタイルガイド (Style Guide)
ここでは、CSSのカラーコードやタイポグラフィ、レスポンシブ設定、カスタムプロパティの命名規則について説明しています。

### 1. カラーコード (Color Palette)
カスタムプロパティ（CSS変数）として以下を設定します。


```css
:root {
  --primary-color: #6C90C3; /* メインのテーマカラープロパティ */
  --secondary-color: #274272; /* 補助カラー */
}