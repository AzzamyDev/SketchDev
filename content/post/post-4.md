---
title: "Post 4"
description : "Ini Halaman ke empat"
date: 2020-12-22T02:50:15+07:00
tags:
---
The current set up has two TwitterCard/OpenGraph options depending on the params you specify in your post’s front matter. If you add the param twitter_img to a post, with the valid image path, then a summary card with large image will be shown. If you don’t provide twitter_img then a summary card with the site logo will be shown instead. For best scaling large image summary wants a 2:1 ratio image and regular summary wants 1:1. The post exampleSite/creating-a-new-theme.md has been tweaked to include these new params, so you can template and test off of that.

The summary description will use the one provided in a post’s front matter if it exists or use the generic site description from config.toml. You should also adjust the twitterAuthor and twitterSite params in config.toml to point to your account. You can check how your cards are rendering once your website is being publish with the TwitterCard Validator.