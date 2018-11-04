# Template for GitHub pages

+ [Description](#description)
+ [How to use](#how-to-use)
+ [Site structure](#site-structure)
+ [Changelog](#changelog)

## Description

Template for a [Jekyll]((https://jekyllrb.com) static site that is blog aware. Put markdown files in `_articles` and push to GitHub. Jekyll will automatically render the templates and markdown files to html. 

---

## How to use

1. Edit `_config.yml` to reflect your info
2. Edit `index.html` and `about.html
3. Delete the sample posts and add your articles in the directory `_posts`. The post title must have the format: `YYYY-MM-DD-article-title.md`. Edit the `title` and `date` [front-matter tags](https://jekyllrb.com/docs/front-matter/) accordingly on the post.
4. Push your repo to GitHub
5. To preview the site locally:
  + Make sure you have [ruby](https://www.ruby-lang.org/en/documentation/installation/) installed
  + Install Jekyll: `gem install jekyll` ([more info on Jekyll installation](https://jekyllrb.com/docs/installation/))
  + Create a directory `_site` (see [Site structure](#site-structure))
  + [Build and serve the site](https://jekyllrb.com/docs/step-by-step/01-setup/#build) with the command: `jekyll serve`, then you can preview your site at [http://localhost:4000](http://localhost:4000)

---

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

---

## Changelog

2018-11-04: First version
