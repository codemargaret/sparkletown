---
layout: post
title:  "Adding Products with SnipCart"
date:   2020-06-27 11:38:04 -0700
author: margaret
categories: updates
image: "/images/benji.jpg"
---

How can I use [SnipCart](https://snipcart.com/) to add products to a Bridgetown site?

My first thought was that perhaps products should work like posts. I tried copying the code for the Articles page and replacing 'posts' with 'products,' but the page still rendered posts. For now I'm going to table this issue and just put a single product on the home page.

SnipCart generally works by adding attributes to static HTML. Bridgetown content is written in markdown, so I needed to add an HTML button to a markdown file. There are several ways you can do this, beautifully outlined [here](https://stackoverflow.com/questions/40688633/how-can-i-add-a-button-in-a-md-file-with-jekyll). I went with option 3, plain HTML, and used the public test API key, and that was that. The button and cart work great. The only issue I've noticed so far is that the button styles aren't coming through. I'm curious to see if that still holds true after deploy.

Spoiler alert: it did.