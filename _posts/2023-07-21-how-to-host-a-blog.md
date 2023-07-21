---
layout: post
title: Using Jekyll and Github Pages to host your blog
categories: [Github, Portfolio, Jekyll]
---

Hosting a blog, particularly with a custom domain, can be an expensive and irritating process. This has led to the use of websites like Medium to host small blogs. I was looking for a solution where I can host a blog with my own domain, not pay more than my domain registration, and have a static site to tinker with and post to. 

This led to my discovery of Jekyll and Github Pages. I was already using Github to host my repositories and had used Github Pages to post things from The Odin Project. Using Jekyll is a simple process and allows a static site to host a reasonably fully featured blog for very little effort.

1. Ensure you've got a Github account - sign up [here](https://github.com/) if you don't
2. Find a template for your Jekyll blog, I used [this](https://jekyllthemes.io/) website to do that, and just chose a free template
3. Fork the repository, or use a template if they provide one. 
4. Setup the config.yaml file to point at your github repo
5. That's it your blog should be hosted. 

You can then either edit the markdown files directly in the browser at Github.com, or use an editor like VSCode etc. 

Once you sync changes to your repository Github automatically rebuilds the Jekyll site and your posts appear.