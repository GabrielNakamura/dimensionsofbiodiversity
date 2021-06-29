---
title: Publications
description: |
  This is a list containing my publications.
author: "Gabriel Nakamura"
show_post_thumbnail: true
show_author_byline: true
show_post_date: true
# for listing page layout
layout: list # list, list-sidebar, list-grid

# for list-sidebar layout
sidebar: 
  title: Some peer-reviewed thoughts
  description: |
    Here you will find a full list of publications in which I produced through my research
    life. You can click in each post to read the abstract and in Read more button if you 
    want to access the full text.
    
    Check out the _index.md file in the /blog folder 
    to edit this content. 
  author: "Gabriel Nakamura"
  text_link_label: ""
  text_link_url: ""
  show_sidebar_adunit: false # show ad container

# set up common front matter for all pages inside blog/
cascade:
  layout: single-series
  author: "Gabriel Nakamura"
  show_author_byline: true
  show_post_date: true
  show_disqus_comments: false # see disqusShortname in site config
  # for single-sidebar layout
  sidebar:
    text_link_label: View recent posts
    text_link_url: ""
    show_sidebar_adunit: true # show ad container
  text_series_label: "In this series" 
  text_contents_label: "On this page" 
---

** No content below YAML for the blog _index. This file provides front matter for the listing page layout and sidebar content. It is also a branch bundle, and all settings under `cascade` provide front matter for all pages inside blog/. You may still override any of these by changing them in a page's front matter.**
