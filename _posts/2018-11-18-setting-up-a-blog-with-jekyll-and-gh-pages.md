---
layout: post
title: Setting up a blog with Jekyll and GitHub Pages
---

For some time now, I wanted to start a blog, but I couldn't find a
solution that was as simple and lightweight as I would like. Although
Jekyll was already on my radar for some time, I was unable to find a
comfortable workflow for me. After trying to set up everything using
Travis CI builds, I gave up as it was just too much additional work.

The notion of writing posts in markdown was stuck in my head,
though. After a bunch of searching, I found out that GitHub supports
Jekyll websites out of the box. I got hooked and gave it a try, this
site is the result.

Jekyll allows you to start a static website that is built from a
bunch of simple components, like blog posts. Deployment using GitHub Pages is
hustle free and lets you focus all your attention on designing the website and
writing your blog. Content, layout, and styles are all nicely separated, which
gives you a lot of creative freedom without writing boilerplate code. Markdown
and Sass are supported out of the box. Being build with Ruby, Jekyll also gives
you access to a lot of useful gems. Only whitelisted ones are available on
GitHub, however.

Setting everything up for a painless creative experience is
surprisingly simple. I would recommend starting with [the step by step
guide](https://jekyllrb.com/docs/step-by-step/01-setup/) and trying
things out. To get your site ready to deploy, you will only need a few
files. All the required techniques are described in the tutorial.

After getting the hang of the basic, deployment is a piece of cake, simply push
your code to a repository GitHub and enable GitHub Pages in the repository
settings. Everything should work out of the box. This blog post by Jonathan
McGlone explains the process in great detail:
[http://jmcglone.com/guides/github-pages/](http://jmcglone.com/guides/github-pages/).

I will definitely try to go without installing any gems for as long as I can, as
I love to reinvent stuff in my free time. For me, the next step will be building
a sensible layout scheme and theming it up!
