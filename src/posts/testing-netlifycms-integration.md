---
layout: post.njk
tags: blog
title: Testing NetlifyCMS integration
description: Testing NetlifyCMS integration with Eleventy and `eleventy-img` plugin
date: 2022-01-27T12:56:48.593Z
image: https://mma.prnewswire.com/media/1099201/Netlify_Logo.jpg?p=facebook
image_alt: NetlifyCMS logo
---
Testing testing.

Updated the Unsplash image link and now it works. Though it is not processed through `eleventy-img` plugin.

![eagle](/assets/img/eagle.jpg "Photo of an eagle")

This image is from local library.

The below image is from local library, but using the `eleventy-img` plugin shortcode:

{% image "eagle.jpg", "Photo of an eagle" %}