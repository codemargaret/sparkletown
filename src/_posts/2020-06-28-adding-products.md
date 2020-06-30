---
layout: post
title:  "Adding Products"
date:   2020-06-27 11:38:04 -0700
author: margaret
categories: updates
image: "/images/benji.jpg"
---

What is the best way to add products to a Bridgetown site?

Perhaps products should work like posts. I tried copying the code for the Articles page and replacing 'posts' with 'products,' but the page still rendered posts, so for now I'm just going to put a single product on the home page.  

SnipCart usually works by adding attributes to static HTML. There are several ways you can do this, beautifully oulined [here](https://stackoverflow.com/questions/40688633/how-can-i-add-a-button-in-a-md-file-with-jekyll). I went with option 3, plain HTML, and used the public test API key. The button and cart work great. The only issue is that the button styles aren't coming through. I'm curious to see if that holds true after deploy.