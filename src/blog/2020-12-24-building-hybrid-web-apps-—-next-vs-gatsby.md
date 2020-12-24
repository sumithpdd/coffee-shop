---
templateKey: blog-post.template
title: Building Hybrid web apps — Next vs. Gatsby
date: 2020-12-24T10:55:04.165Z
---
If you are looking to build a hybrid web app where you need both — rendering the page UI using SSR and handling data to the CSR, Next.JS trumps over Gatsby.

![Next.js vs Gatsby.js - building hybrid web apps](https://cdn.sanity.io/images/ay6gmb6r/production/3512b12058e2546561e7b32cecaf6e7ecc73cdf3-700x442.png?w=729&fm=webp&fit=max&auto=format "Next.js vs Gatsby.js - building hybrid web apps")

Inside a single web application, you have both SSR for visitors and CSR for users who are logged in, and this type of app is best built using Next. Most of the pages today need to be optimized for Search Engines, and since the content is usually dynamic in these kinds of pages, Next.Js is the better option.