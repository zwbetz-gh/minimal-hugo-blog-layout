# Minimal Hugo Blog Layout

[![Netlify Status](https://api.netlify.com/api/v1/badges/86628f35-ead8-4f4d-99ef-673e3ab08b6f/deploy-status)](https://app.netlify.com/sites/minimal-hugo-blog-layout/deploys)

## Live Demo

<https://minimal-hugo-blog-layout.netlify.com/>

## Overview

This layout has bare minimum CSS styling - it's merely a starting point for a hugo blog. Read the [hugo docs](https://gohugo.io/documentation/) and add your own styling to make this look how you want. 

The home page is a list of posts by publish date, from newest to oldest. There is a basic nav with links to posts, about, contact, and RSS. 

Put your CSS, JS, and image files under `static/`. When the site is generated, i.e. when running the `hugo` command, everything under `static/` will be copied to the root of `public/`. 

## Layout

The main files:

* `layouts/index.html` - Home page template
* `layouts/post/single.html` - Single post template
* `layouts/_default/single.html` - Single page template
* `layouts/_default/baseof.html` - Base template that the above templates inherit from

## Run it Locally

1. [Install hugo](https://gohugo.io/getting-started/installing/)
1. Open a command line and run:
    1. `git clone https://github.com/zwbetz-gh/minimal-hugo-blog-layout.git`
    1. `cd minimal-hugo-blog-layout`
    1. `hugo server`
1. Navigate to `http://localhost:1313/` in your browser

## Examples

* Create a new post: `hugo new post/some-post.md`
* Create a new page: `hugo new some-page.md` - then optionally update the menu nav in `config.toml`

## Acknowledgments

Thank you to all the contributors at [hugo](https://github.com/gohugoio/hugo/graphs/contributors), [hugo docs](https://github.com/gohugoio/hugoDocs/graphs/contributors), and the [hugo discussion forum](https://discourse.gohugo.io/).

Site design is based off the [better mother loving website](http://bettermotherfuckingwebsite.com/). 
