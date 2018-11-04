# Skeleton for GitHub pages

+ [Description](#description)
+ [How to use](#how-to-use)
+ [Site structure](#site-structure)
+ [Changelog](#changelog)

## Description

Skeleton for a GitHub pages site that makes use of [Jekyll](https://jekyllrb.com) blog capabilities and templating. Put markdown files in `_articles` and push to GitHub. Jekyll will automatically render the templates and markdown files to html. 

---

## How to use

1. Edit `_config.yml` to reflect your info
2. Edit `index.html` and `about.html
3. Delete the sample posts and add your articles in the directory `_posts`. The post title must have the format: `YYYY-MM-DD-article-title.md`. Edit the `title` and `date` [front-matter tags](https://jekyllrb.com/docs/front-matter/) accordingly on the post.
4. Edit `assets/style.css` as necessary.
5. Push your repo to GitHub
6. To preview the site locally:
  + Make sure you have [ruby](https://www.ruby-lang.org/en/documentation/installation/) installed
  + Install Jekyll: `gem install jekyll` ([more info on Jekyll installation](https://jekyllrb.com/docs/installation/))
  + Create a directory `_site` (see [Site structure](#site-structure))
  + [Build and serve the site](https://jekyllrb.com/docs/step-by-step/01-setup/#build) with the command: `jekyll serve`, then you can preview your site at [http://localhost:4000](http://localhost:4000)

---

## Site structure

Uses the [Jekyll directory structure](https://jekyllrb.com/docs/structure/):

```sh
tree
├── .gitignore
├── README.md
├── _config.yml
├── _includes
│   ├── footer.html
│   └── head.html
├── _layouts
│   ├── default.html
│   └── post.html
├── _posts
│   ├── 2018-11-01-lorem-ipsum.md
│   └── 2018-11-04-Dextra-neque.md
├── about.html
├── articles
│   └── index.html
├── assets
│   └── style.css
└── index.html

```

### `.gitignore`

Directory `_site` is excluded in `.gitignore`, as well as any tarballs or swap/backup files

### `_config.yml`

[Kramdown](https://kramdown.gettalong.org/) Markdown parser, use of `baseurl`, use of Twitter and GitHub links on footer.

### `_layouts`

Default and post layout

### `_includes`

Includes `head.html` (everything between the `<head></head>` tags in html) and `footer.html` - change as necessary

### `assets` and `_posts`

Sample stylesheet and content

### `articles/index.html`

Articles index

---

## Changelog

2018-11-04: First version
