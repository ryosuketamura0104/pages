# pages

pitty / 関連アプリの公開ドキュメント (プライバシーポリシー等) を GitHub Pages でホスティングするためのリポジトリ。

## URL

- ランディング: <https://ryosuketamura0104.github.io/pages/>
- pitty プライバシーポリシー: <https://ryosuketamura0104.github.io/pages/pitty/privacy-policy>

## ディレクトリ構成

```
.
├── _config.yml          # Jekyll (jekyll-theme-minimal) 設定
├── index.md             # ランディング
└── pitty/
    └── privacy-policy.md
```

## アプリを追加するとき

1. `pitty/` と同じ階層に `<app-name>/` ディレクトリを作る
2. 中に `privacy-policy.md` 等の Markdown を配置
3. `index.md` にリンクを追記
4. push すると GitHub Pages が自動でビルドして公開
