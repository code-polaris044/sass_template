このリモートリポジトリは、sass(scss記法)のテンプレートです。<br>
This remote repository is a template for sass.

CSSの命名規則及びファイル構造は、[BEM](https://en.bem.info/)、[FLOCSS](https://github.com/hiloki/flocss)、[SMACSS](http://smacss.com/ja)にユーティリティファーストを
混ぜたかたちになります。<br>
(CSS naming conventions and file structures are available at [BEM](https://en.bem.info/), [FLOCSS](https://github.com/hiloki/flocss), and [SMACSS](http://smacss.com/ja) Utilities First is mixed in.)

・[sass](https://sass-lang.com/guide)

## tree
<pre>

├── README.md
├── dist
│   ├── css
│   │   ├── style.css
│   │   └── style.css.map
│   ├── font
│   │   ├── murecho-v10-latin-100.woff
│   │   ├── murecho-v10-latin-100.woff2
│   │   ├── murecho-v10-latin-200.woff
│   │   ├── murecho-v10-latin-200.woff2
│   │   ├── murecho-v10-latin-300.woff
│   │   ├── murecho-v10-latin-300.woff2
│   │   ├── murecho-v10-latin-500.woff
│   │   ├── murecho-v10-latin-500.woff2
│   │   ├── murecho-v10-latin-600.woff
│   │   ├── murecho-v10-latin-600.woff2
│   │   ├── murecho-v10-latin-700.woff
│   │   ├── murecho-v10-latin-700.woff2
│   │   ├── murecho-v10-latin-800.woff
│   │   ├── murecho-v10-latin-800.woff2
│   │   ├── murecho-v10-latin-900.woff
│   │   ├── murecho-v10-latin-900.woff2
│   │   ├── murecho-v10-latin-regular.woff
│   │   ├── murecho-v10-latin-regular.woff2
│   │   ├── noto-sans-jp-v42-latin_japanese-100.woff
│   │   ├── noto-sans-jp-v42-latin_japanese-100.woff2
│   │   ├── noto-sans-jp-v42-latin_japanese-300.woff
│   │   ├── noto-sans-jp-v42-latin_japanese-300.woff2
│   │   ├── noto-sans-jp-v42-latin_japanese-500.woff
│   │   ├── noto-sans-jp-v42-latin_japanese-500.woff2
│   │   ├── noto-sans-jp-v42-latin_japanese-700.woff
│   │   ├── noto-sans-jp-v42-latin_japanese-700.woff2
│   │   ├── noto-sans-jp-v42-latin_japanese-900.woff
│   │   ├── noto-sans-jp-v42-latin_japanese-900.woff2
│   │   ├── noto-sans-jp-v42-latin_japanese-regular.woff
│   │   ├── noto-sans-jp-v42-latin_japanese-regular.woff2
│   │   ├── noto-serif-jp-v21-latin_japanese-200.woff
│   │   ├── noto-serif-jp-v21-latin_japanese-200.woff2
│   │   ├── noto-serif-jp-v21-latin_japanese-300.woff
│   │   ├── noto-serif-jp-v21-latin_japanese-300.woff2
│   │   ├── noto-serif-jp-v21-latin_japanese-500.woff
│   │   ├── noto-serif-jp-v21-latin_japanese-500.woff2
│   │   ├── noto-serif-jp-v21-latin_japanese-600.woff
│   │   ├── noto-serif-jp-v21-latin_japanese-600.woff2
│   │   ├── noto-serif-jp-v21-latin_japanese-700.woff
│   │   ├── noto-serif-jp-v21-latin_japanese-700.woff2
│   │   ├── noto-serif-jp-v21-latin_japanese-900.woff
│   │   ├── noto-serif-jp-v21-latin_japanese-900.woff2
│   │   ├── noto-serif-jp-v21-latin_japanese-regular.woff
│   │   ├── noto-serif-jp-v21-latin_japanese-regular.woff2
│   │   ├── roboto-v30-latin-100.woff
│   │   ├── roboto-v30-latin-100.woff2
│   │   ├── roboto-v30-latin-100italic.woff
│   │   ├── roboto-v30-latin-100italic.woff2
│   │   ├── roboto-v30-latin-300.woff
│   │   ├── roboto-v30-latin-300.woff2
│   │   ├── roboto-v30-latin-300italic.woff
│   │   ├── roboto-v30-latin-300italic.woff2
│   │   ├── roboto-v30-latin-500.woff
│   │   ├── roboto-v30-latin-500.woff2
│   │   ├── roboto-v30-latin-500italic.woff
│   │   ├── roboto-v30-latin-500italic.woff2
│   │   ├── roboto-v30-latin-700.woff
│   │   ├── roboto-v30-latin-700.woff2
│   │   ├── roboto-v30-latin-700italic.woff
│   │   ├── roboto-v30-latin-700italic.woff2
│   │   ├── roboto-v30-latin-900.woff
│   │   ├── roboto-v30-latin-900.woff2
│   │   ├── roboto-v30-latin-900italic.woff
│   │   ├── roboto-v30-latin-900italic.woff2
│   │   ├── roboto-v30-latin-ext_latin-100.woff
│   │   ├── roboto-v30-latin-ext_latin-100.woff2
│   │   ├── roboto-v30-latin-ext_latin-100italic.woff
│   │   ├── roboto-v30-latin-ext_latin-100italic.woff2
│   │   ├── roboto-v30-latin-ext_latin-300.woff
│   │   ├── roboto-v30-latin-ext_latin-300.woff2
│   │   ├── roboto-v30-latin-ext_latin-300italic.woff
│   │   ├── roboto-v30-latin-ext_latin-300italic.woff2
│   │   ├── roboto-v30-latin-ext_latin-500.woff
│   │   ├── roboto-v30-latin-ext_latin-500.woff2
│   │   ├── roboto-v30-latin-ext_latin-500italic.woff
│   │   ├── roboto-v30-latin-ext_latin-500italic.woff2
│   │   ├── roboto-v30-latin-ext_latin-700.woff
│   │   ├── roboto-v30-latin-ext_latin-700.woff2
│   │   ├── roboto-v30-latin-ext_latin-700italic.woff
│   │   ├── roboto-v30-latin-ext_latin-700italic.woff2
│   │   ├── roboto-v30-latin-ext_latin-900.woff
│   │   ├── roboto-v30-latin-ext_latin-900.woff2
│   │   ├── roboto-v30-latin-ext_latin-900italic.woff
│   │   ├── roboto-v30-latin-ext_latin-900italic.woff2
│   │   ├── roboto-v30-latin-ext_latin-italic.woff
│   │   ├── roboto-v30-latin-ext_latin-italic.woff2
│   │   ├── roboto-v30-latin-ext_latin-regular.woff
│   │   ├── roboto-v30-latin-ext_latin-regular.woff2
│   │   ├── roboto-v30-latin-italic.woff
│   │   ├── roboto-v30-latin-italic.woff2
│   │   ├── roboto-v30-latin-regular.woff
│   │   └── roboto-v30-latin-regular.woff2
│   ├── img
│   │   └── vincent-chen-I_uFHRMccaw-unsplash.jpg
│   └── js
│       └── main.js
├── index.html
├── package-lock.json
├── package.json
├── postcss.config.js
└── src
    ├── img
    ├── js
    │   └── index.js
    └── sass
        ├── bases
        ├── components
        ├── layouts
        ├── projects
        ├── style.scss
        └── utilities
</pre>
