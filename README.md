Template for GitHub pages
=========================

## Site structure

Uses the [Jekyll directory structure](https://jekyllrb.com/docs/structure/):

```sh
tree
├── README.md
├── .gitignore
├── _config.yml
├── _layouts
│   ├── default.html
│   └── post.html
├── _posts
│   ├── 2018-11-01-lorem-ipsum.md
│   └── 2018-11-04-Dextra-neque.md
├── _site
├── about.html
├── articles
│   └── index.html
├── assets
│   └── style.css
└── index.html
```

### `.gitignore`

Directory `_site` is excluded in `.gitignore`

### `_config.yml`

[Kramdown](https://kramdown.gettalong.org/) Markdown parser and use of `baseurl`

### `_layouts`

Default and post layout

### `assets` and `_posts`

Sample stylesheet and content

### `articles/index.html`

Articles index


