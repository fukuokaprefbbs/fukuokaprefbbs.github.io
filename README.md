# fukuokaprefbbs.github.io

## リポジトリ構造

```
fukuokaprefbbs.github.io/
├── .github/                 # GitHubのWorkflow設定
├── _data/                   # ホームページ情報・活動内容・連絡先などの設定データ
├── _includes/               # セクション別に分割したHTMLパーツ
├── _layouts/                # レイアウトテンプレート
├── _pages/                  # 個別ページ
├── assets/                  # 素材ファイル
├── .gitignore               # Git管理対象外ファイルの設定
├── Gemfile                  # Ruby依存関係
├── README.md                # 本ファイル
├── _config.yml              # Jekyll設定
└── index.html               # トップページ
```

## 動作確認方法

```bash
git clone https://github.com/fukuokaprefbbs/fukuokaprefbbs.github.io.git
cd fukuokaprefbbs.github.io
bundle install
bundle exec jekyll build
bundle exec jekyll serve --livereload
```

ブラウザで `http://localhost:4000` を開いてホームページを確認できる。

## 個別ページの追加方法

### ページファイルの作成
- `_pages/` ディレクトリにMarkdownファイル（`.md`）を作成する。
- 詳細なサンプルは `_pages/sample-page.md` を参照。


