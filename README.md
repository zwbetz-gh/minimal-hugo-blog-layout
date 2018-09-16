# Minimal hugo blog layout

## Overview

This layout has no CSS styling. It is merely a starting point for a minimal hugo blog. Read the [hugo docs](https://gohugo.io/documentation/) and add your own styling to make this look how you want. 

The home page is a list of posts by publish date, from newest to oldest. There is a basic nav with links to posts, about, and contact pages. 

Put your CSS, JS, and image files under `static/`. When the site is generated, i.e. when running the `hugo` command, everything under `static/` will be copied to `public/`. 

## Local development environment setup

1. [Install hugo](https://gohugo.io/getting-started/installing/)
1. Open a command line and run:
    1. `git clone https://github.com/zwbetz-gh/minimal-hugo-blog-layout.git`
    1. `cd minimal-hugo-blog-layout`
    1. `hugo server`
1. Navigate to `http://localhost:1313/` in your browser

## Examples

Create new posts: `hugo new post/<your-post-title-here>.md`

Use the `listimages` [shortcode](https://gohugo.io/content-management/shortcodes/) to list all images in a given directory: `{{< listimages path="/static/img/photo-dir" pathUrl="/img/photo-dir">}}`
