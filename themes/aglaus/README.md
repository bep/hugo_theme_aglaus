# Aglaus

Aglaus is a single-column theme for [Hugo](http://gohugo.io/).

**IMGIMGIMG**

## Features

* Google Analytics
* Gravatar Profile
* Disqus
* SNS Links(Facebook, Twitter, GitHub)
* Share Button
* Eye-catching Image
* Tagging
* Related Post

# Installation

Referred from [hugoThemes#Installing Themes](https://github.com/spf13/hugoThemes#installing-themes).

## Installing with other all themes

If you would like to install all of the available hugo themes, simply clone the entire repository from within your working directory.

    git clone --recursive https://github.com/spf13/hugoThemes.git themes

## Installing a single theme

    mkdir themes
    cd themes
    git clone https://github.com/dim0627/hugo_theme_aglaus aglaus
    
## Build with Aglaus

    hugo server -t aglaus

# Configuration

**config.yaml**

``` yaml
BaseUrl: "http://example.com"
LanguageCode: "en-us"
Title: "Site name."

Params:
  Author: "Your name."
  Birth: "Sun, Feb 26, 1989"
  DateForm: "Mon, Jan 2, 2006"
  GoogleAnalyticsUserID: "Your ID."
  GravatarHash: "Your Hash."
  Facebook: "Your ID."
  Twitter: "Your ID."
  Github: "Your ID."
  ShowRelatedPost: True
  Disqus: "Your Disqus."

Indexes:
  tag: "tags"

permalinks:
  post: /blog/:year/:month/:day/:title/

MetadataFormat: "yaml"
```

Example : [My config.yaml](https://github.com/dim0627/dim0627.github.io/blob/source/config.yaml)

**example post**

``` markdown
---
title: "Post title here" # Used in the url.
titleja: "Display title here" # Display in the post title. Use in such as multi-byte title.
eyecatch: "hugo.png" # Eye-cathinc image from [static/images/***]
date: 2014-09-17
comments: true
tags: [gitHub, octopress, jekyll]
---

Contents here
```

# Read more details

Please read this.

http://yet.unresolved.xyz/hugo_theme_aglaus/blog/2015/01/06/about-aglaus/

# Contact us

Please mail to `dim0627@gmail.com` or SNS.

[https://www.facebook.com/daisuke.tsuji.735](https://www.facebook.com/daisuke.tsuji.735)

[https://twitter.com/dim0627](https://twitter.com/dim0627)
