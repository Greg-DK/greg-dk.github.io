---
layout: post
title: Effortlessly Host Your Blog - A Journey with Jekyll and Github Pages
categories: [Github, Portfolio, Jekyll, DNS, Domains]
---

Have you ever wanted to host your own blog with a custom domain but found the process long and didn't want to pay hosting fees? Don't worry; I've got the perfect solution that strikes a balance between simplicity and customisation. Let me introduce you to the powerful duo of Jekyll and Github Pages, making blog hosting a breeze.

## The Discovery of Jekyll and Github Pages

Searching for an affordable and user-friendly blog hosting option, I stumbled upon the dynamic combination of Jekyll and Github Pages. Already familiar with Github for hosting repositories and sharing content, Jekyll seemed like a natural fit. With minimal effort, you can have your own static site that serves as the perfect platform for your blog.

## Getting Started Made Easy

To embark on this journey, you'll need a Github account (if you don't have one, sign up [here](https://github.com/)). Next, explore a variety of Jekyll blog templates—I found a great selection on [this website](https://jekyllthemes.io/), offering free templates that won't disappoint.

Once you've selected your template, you can either fork the repository or use the provided template. Then, simply set up the `config.yaml` file to point to your Github repo, and you're good to go!

## Effortless Content Management

One of the best perks of using Jekyll is its user-friendly content management. Edit your blog posts directly in the browser on Github.com or use your favorite text editor like VSCode—the choice is yours. This seamless process allows you to focus on crafting compelling content without getting lost in technical complexities.

## Seamless Blog Updates

Whenever you make changes and sync them to your repository, Github works its magic and automatically rebuilds your Jekyll site. Your latest blog posts will appear like clockwork, ensuring your readers always have fresh content to enjoy.

## Custom Domain Setup

Want to give your blog a personal touch with a custom domain? Fear not, the process is straightforward:

1. Secure a custom domain through a reputable registrar like Google Domains, Namecheap, or GoDaddy.

2. Adjust the DNS settings with your domain registrar, or if you prefer Cloudflare, point your registrar to Cloudflare's Name Servers.

3. Set up the A records to point to Github's servers (Github provides guidance on this [here](https://docs.github.com/en/pages/configuring-a-custom-domain-for-your-github-pages-site/managing-a-custom-domain-for-your-github-pages-site)).

4. Enable the use of the apex domain by setting up the CNAME record making www an alias of your domain.

5. Configure your Github Pages settings to use your custom domain, and let Github handle the rest.

A Note on SSL

While adding SSL for extra security, I encountered a minor issue with redirect loops after enabling SSL via Cloudflare. The solution was simple—disabling some Cloudflare rules allowed my blog to remain accessible via secure https.

Conclusion

With Jekyll and Github Pages, hosting your own blog becomes as easy as pushing a markdown file to your Github repo. Say goodbye to complicated setups and costly alternatives—instead, embrace a user-friendly solution that lets you focus on sharing your ideas with the world. 