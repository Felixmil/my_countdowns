# My Countdowns

## Goal

Personnal page with all the countdowns I want to track.


## Repo Structure

### `_site.yaml` (required)

Website generation metadata. Options can be found here: https://bookdown.org/yihui/rmarkdown/rmarkdown-site.html#rmarkdown-site

### `index.Rmd` (required)

Website landing page. Here, it contains our countdowns

### `/docs` (generated)

Directory where the website is generated. Direct github pages toward this.


### `render_site.R` (optional)

helper script to refresh the website once modifications are made.

## Step by Step Guide

1. Clone this repo,
2. Add your countdowns in `index.Rmd`,
3. Run `render_site.Rmd`,
4. Push to a a new github repo,
5. In repo settings on Github, activate webpage with `/docs` as source folder. ([see instructions](https://docs.github.com/en/enterprise-server@2.21/github/working-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site))

