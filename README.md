# Cup Hugo Theme

An accessibility-friendly Hugo theme, adapted from the [Cupper Hugo Theme](https://github.com/zwbetz-gh/cupper-hugo-theme) which was ported from the [original Cupper](https://github.com/ThePacielloGroup/cupper) project.

## Table of contents

- [Demo](#demo)
- [Minimum Hugo version](#minimum-hugo-version)
- [Installation](#installation)
- [Updating](#updating)
- [Run example site](#run-example-site)
- [Configuration](#configuration)
- [Logo](#logo)
- [Favicons](#favicons)
- [Shortcodes](#shortcodes)
- [Syntax highlighting](#syntax-highlighting)
- [Disable toc for a blog post](#disable-toc-for-a-blog-post)
- [Getting help](#getting-help)
- [Credits](#credits)

## Demo

[![Netlify
Status](https://api.netlify.com/api/v1/badges/2eb4e000-526b-4b74-867f-a14a48ef34d1/deploy-status)](https://app.netlify.com/sites/hugo-cup-theme/deploys)

See a live demo of this theme at: [https://hugo-cup-theme.netlify.com](https://hugo-cup-theme.netlify.com)

## Minimum Hugo version

Hugo version `0.58.3` or higher is required. View the [Hugo releases](https://github.com/gohugoio/hugo/releases) and download the binary for your OS.

## Installation

From the root of your site:

```
git submodule add https://github.com/kmuncie/hugo-cup-theme.git themes/hugo-cup-theme
```

## Updating

From the root of your site:

```
git submodule update --remote --merge
```

## Run example site

From the root of `themes/hugo-cup-theme/exampleSite`:

```
hugo server --themesDir ../..
```

## Configuration

Copy the `config.toml` or `config.yaml` from the [`exampleSite`](https://github.com/zwbetz-gh/cupper-hugo-theme/tree/master/exampleSite), then edit as desired.

## Logo

Place your SVG logo at `static/images/logo.svg`. If you don't provide a logo, then the default theme logo will be used.

## Favicons

Upload your image to [RealFaviconGenerator](https://realfavicongenerator.net/) then copy-paste the generated favicon files under `static`.

## Shortcodes

See the [full list of supported shortcodes](https://cupper-hugo-theme.netlify.com/cupper-shortcodes/).

## Syntax highlighting

Syntax highlighting is provided by [Prism](https://prismjs.com/). See this [markdown code fences example](https://cupper-hugo-theme.netlify.com/cupper-shortcodes/#syntax-highlighting).


## Disable toc for a blog post

Blog posts that have two or more subheadings (`<h2>`s) automatically get a table of contents. To disable this set `toc` to `false`. For example:

```
---
title: "My page with a few headings"
toc: false
---
```

## Getting help

If you run into an issue that isn't answered by this documentation or the [`exampleSite`](https://github.com/kmuncie/hugo-cup-theme/tree/master/exampleSite), then visit the [Hugo forum](https://discourse.gohugo.io/). The folks there are helpful and friendly. **Before** asking your question, be sure to read the [requesting help guidelines](https://discourse.gohugo.io/t/requesting-help/9132).

## Credits

Thank you to [Zachary Betz](https://zwbetz.com/) for the basis of this adpatation, as well as [Heydon Pickering](http://www.heydonworks.com) and [The Paciello Group](https://www.paciellogroup.com/) for creating the original Cupper project.

Logo is a beautiful illustration from [Open Doodles](https://www.opendoodles.com/).
