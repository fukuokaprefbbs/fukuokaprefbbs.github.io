---
layout: page      # 専用レイアウト（戻りリンク・タイトル自動表示）
title: サンプルページ     # ページのタイトル
description: 新しいページの作成方法のサンプルです  # SEO用の説明
---

## 本文

- 本文をMarkdownで記載する
- Markdownの記法については [GitHub Flavored Markdown](https://docs.github.com/ja/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax) を参照

## URL

このページには以下のURLでアクセスできる。

- `https://fukuokaprefbbs.github.io/sample/`
  - ベースURL: `https://fukuokaprefbbs.github.io`
  - ページパス: `/sample/`
    - `_config.yml`の`permalink: "/:basename/"`設定により、ファイル名から拡張子を除いたパスが生成される
