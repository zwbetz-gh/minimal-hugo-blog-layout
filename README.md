# Minimal Hugo Blog Layout

This layout has no CSS styling. It is merely a starting point for a minimal hugo blog. Read the [hugo docs](https://gohugo.io/documentation/) and add your own styling to make this look how you want. 

Put your CSS, JS, and image files under `static/`. When the site is generated, i.e. when running the `hugo` command, everything under `static/` will be copied to `public/`. 

To see it in action:

1. [Install hugo](https://gohugo.io/getting-started/installing/)
1. `git clone git@github.com:zwbetz-gh/minimal-hugo-blog-layout.git`
1. `cd minimal-hugo-blog-layout`
1. `hugo server`

Create new posts:

```
hugo new post/<your-post-title-here>.md
```

There is a shortcode which will list all the images in a given directory. An example usage:

```
{{< listimages path="/static/img/photo-dir" pathUrl="/img/photo-dir">}}
```
