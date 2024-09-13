---
layout: post
title:  "Website is up again in a new coat!"
description: "After some research for alternative to my custom React page, I finished its refactoring to Jekyll!"
date:   2024-09-13
categories: jekyll update
tags: [update]
---

After half a year of occasional research and refactoring attempts, I've finally decided for a technology and finished refactoring to Jekyll.

## Why Jekyll?
Why on earth would I chose this Ruby based, static website generator instead of my custom React one?
Well, this breaks down to many reasons and I want to break this down specifically in a single dedicated post, but I'll put here basic ideas.

### 1. Maintainability
I need my website easily maintainable with minimal bugs out of the box. The last thing I want to do after getting home from work is to fix bugs in CSS or React. Jekyll helps me by having this in mind, since the very beginning, so I can spend time doing some fun silly projects, instead of debugging CSS.

### 2. Similarity to my solution
I used on-demand generation from custom textfile page serialization in my old website (not the best solution, I know 🤔). Jekyll does this somewhat similarly with out of MD/HTML/Whatever static compilation, so I need no database, just CI/CD from my repo right onto a server.

### 3. Simplicity
The holy grail of programming and software development is in my eyes simplicity. Doing things efficiently and simply is often not easy (nor possible sometimes). Jekyll offers me great simplicity with this default theme, I don't have to care about any advanced features, that I do not personally pursue to have. I just maintain my posts in markdown and the rest is done automatically.