# Coinsence blog

- [Installation](#Installation)
	- [Requirements](#Requirements)
	- [Running](#Running)
- [Usage](#Usage)
	- [Posting](#Posting)
	- [Configuration](#Configuration)
- [Deployment](#Deployment)

This the official repo for the coinsence blog, it will be hosted on blog.coinsence.org .
This blog is built with [Jekyll](https://jekyllrb.com/) and [Mediumish](https://github.com/wowthemesnet/mediumish-theme-jekyll) template for Jekyll.

## Installation
Jekyll is a Ruby Gem that can be installed on most systems.

### Requirements
Requirements are as described on the Jekyll installation docs:  [https://jekyllrb.com/docs/installation/#requirements](https://jekyllrb.com/docs/installation/#requirements)

-   Git
-   Ruby
-   RubyGems
-   GCC and Make

You can follow installation guide as prescribed in offical docs:  [https://jekyllrb.com/docs/installation/#guides](https://jekyllrb.com/docs/installation/#guides)

### Running

After making sure all the requirements are set, then you should be able to run your Jekyll site:

1.  `git clone https://github.com/Coinsence/coinsence.github.io.git`
2.  `cd coinsence.github.io`
3.  `bundle`
4.  `jekyll serve --watch`  or  `bundle exec jekyll serve`
5.  Some YAML post settings:
    -   post image -  `image: assets/images/mypic.jpg`
    -   external post image -  `image: "https://externalwebsite.com/image4.jpg"`
    -   page comments -  `comments:true`
    -   meta description (optional) -  `description: "this is my meta description"`

## Usage

### Posting

You can start adding your  **.md**  files in  **_posts**  folder.

#### _Some YAML post settings_

-   post image -  `image: assets/images/mypic.jpg`
-   external post image -  `image: "https://externalwebsite.com/image4.jpg"`
-   page comments -  `comments:true`
-   meta description (optional) -  `description: "this is my meta description"`

#### _YAML Post Example_

```
---
layout: post
title:  "We all wait for summer"
author: john
categories: [ Jekyll, tutorial ]
image: assets/images/5.jpg
description: "Something about this post here"
rating: 4.5
---

POST CONTENT HERE...

```

### Configuration

You can start configuring the site by modifying the  `_config.yml`  file.

#### _Authors_

You can add authors in the  **authors**  section on the aftermentioned file above. An example below:

```
sal:
    name: Sal
    display_name: Sal
    gravatar: e56154546cf4be74e393c62d1ae9f9d4
    email: wowthemesnet@gmail.com
    web: https://www.wowthemes.net
    twitter: https://twitter.com/wowthemesnet
    description: "Author of Mediumish, a Bootstrap Medium styled template available for WordPress, HTML, Ghost and Jekyll. You are currently previewing Jekyll template demo."

```

## Deployment

As Github already supports running Jekyll templates directly without compiling, you can push your modified code and/or newely added posts/pages, and github will take care of the rest! You can learn more about that  [here](https://help.github.com/en/articles/using-jekyll-as-a-static-site-generator-with-github-pages).

So just commit, push and profit!  😎  ✌️