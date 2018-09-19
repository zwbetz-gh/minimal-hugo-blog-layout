# Minimal hugo blog layout

## Overview

This layout has no CSS styling. It is merely a starting point for a minimal hugo blog. Read the [hugo docs](https://gohugo.io/documentation/) and add your own styling to make this look how you want. 

The home page is a list of posts by publish date, from newest to oldest. There is a basic nav with links to posts, about, and contact pages. 

Put your CSS, JS, and image files under `static/`. When the site is generated, i.e. when running the `hugo` command, everything under `static/` will be copied to the root of `public/`. 

## Run it

1. [Install hugo](https://gohugo.io/getting-started/installing/)
1. Open a command line and run:
    1. `git clone https://github.com/zwbetz-gh/minimal-hugo-blog-layout.git`
    1. `cd minimal-hugo-blog-layout`
    1. `hugo server`
1. Navigate to `http://localhost:1313/` in your browser

## Examples

Create a new post: `hugo new post/<post-title-here>.md`

Create a new page: `hugo new <page-title-here>.md` (then optionally update the nav in `layouts/_default/baseof.html`)

Use the `listimages` [shortcode](https://gohugo.io/content-management/shortcodes/) to list all images in a given directory: `{{< listimages path="/static/img/photo-dir" pathUrl="/img/photo-dir">}}`

## Acknowledgments

Thank you to all the contributors at [hugo](https://github.com/gohugoio/hugo/graphs/contributors), [hugo docs](https://github.com/gohugoio/hugoDocs/graphs/contributors), and the [hugo discussion forum](https://discourse.gohugo.io/).
