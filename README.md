# About

This repository is based on top of [exalted/jekyll-scaffold-for-gh-pages](https://github.com/exalted/jekyll-scaffold-for-gh-pages) which is a bare scaffold for [Jekyll](http://jekyllrb.com), ready to be published on [GitHub Pages](https://pages.github.com).


# Info

Known to be working and scaffolded with `bundle exec jekyll --version # jekyll 2.4.0`.


# Getting Started

```
git clone https://github.com/exalted/bourbon-scaffold-for-jekyll.git --origin scaffold my-awesome-website
cd my-awesome-website/
git remote add origin <url of your new GitHub repository>
script/bootstrap
```


# Preview Locally

```
bin/serve
```


# Publish on GitHub Pages

```
bin/publish
```

:warning: Don't forget to at least configure properly `baseurl` in `_config.yml` before publishing using GitHub Pages ([read more](http://jekyllrb.com/docs/github-pages/#project-page-url-structure).)

Learn more about [GitHub Pages Features](https://help.github.com/categories/github-pages-features/).
