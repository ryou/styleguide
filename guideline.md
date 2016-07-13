# コーディングガイドライン

HTML/CSS,Javascriptを書くに当たって、全体に関わってくるガイドラインをまとめたもの。

## ディレクトリ構造

```
html
├── common
│   ├── css
│   │   ├── base.css
│   │   └── common.css
│   ├── images
│   └── js
│       ├── common.js
│       └── lib
├── css
│   └── index.css
├── images
├── index.html
├── js
│   └── index.js
└── xxx
    ├── css
    │   └── index.css
    ├── images
    ├── index.html
    └── js
        └── index.js
```

共通して使用するファイルは「html/common」ディレクトリに配置。

各ページで使用するファイルは各階層に配置すること。

また、各階層のcss,jsファイルは対応するhtmlと同じ名前をつけること。（例えば、about.htmlに対するcss,jsはabout.css,about.jsとする。）
