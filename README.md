# Minimal Hugo Blog Layout

## Live Demo

<https://cranky-torvalds-a3e301.netlify.com/>

## Overview

This layout has no CSS styling. It is merely a starting point for a minimal hugo blog. Read the [hugo docs](https://gohugo.io/documentation/) and add your own styling to make this look how you want. 

The home page is a list of posts by publish date, from newest to oldest. There is a basic nav with links to posts, about, and contact pages. 

Put your CSS, JS, and image files under `static/`. When the site is generated, i.e. when running the `hugo` command, everything under `static/` will be copied to the root of `public/`. 

## Layout

The main files:

* `layouts/index.html` - The home page template
* `layouts/_default/single.html` - The template for pages and posts. For posts, it inserts the published date and last updated date
* `layouts/_default/baseof.html` - The base template that the above templates inherit from

## Run it Locally

1. [Install hugo](https://gohugo.io/getting-started/installing/)
1. Open a command line and run:
    1. `git clone https://github.com/zwbetz-gh/minimal-hugo-blog-layout.git`
    1. `cd minimal-hugo-blog-layout`
    1. `hugo server`
1. Navigate to `http://localhost:1313/` in your browser

## Examples

* Create a new post: `hugo new post/some-post.md`
* Create a new page: `hugo new some-page.md` (then optionally update the menu nav in `config.toml`)

## Acknowledgments

Thank you to all the contributors at [hugo](https://github.com/gohugoio/hugo/graphs/contributors), [hugo docs](https://github.com/gohugoio/hugoDocs/graphs/contributors), and the [hugo discussion forum](https://discourse.gohugo.io/).
