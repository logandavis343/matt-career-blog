---
title: 'This Blog, Netlify, and JAMstack'
date: 2020-02-15T20:30:00.000Z
summary: >-
  When I told a close friend and former co-worker that I intended to start a
  personal site and blog he recommended I check out Netlify's JAMstack
  templates. It introduced me to a new way to build sites and turned out to be
  just the right solution.
tags:
  - JAMstack
  - Netlify
  - Eleventy
  - Nunjucks
  - Liquid
---
The most important thing was to get something online quickly so that I could start recording my progress. Netlify has several [JAMstack templates](https://templates.netlify.com/tags/eleventy/) that made this very simple to do. I chose the eleventy + Netlify CMS option because I wanted the ability to post from my phone, and the very simple Netlify CMS allows me to do just that. The one click setup linked Netlify to my Github account and after configuring an account and changing a few settings I was ready to download the repo and start working.

Authentication for the Netlify CMS is handled using Git Gateway and Netlify Identity. These allow you to log in to the CMS using your Git account and manage users with simple account management in your Netlify control panel.

After cloning the repo and installing dependencies I ran the command to build the site and started looking to see how it worked so I could change the appearance. Eleventy provides a command which starts up a Browsersync web server and begins watching the current directory for any changes to template files which made it easy to see what those template files were for. There is ample documentation but it feels good to know I still have enough brain cells to get the gist of something like this through intuition and trial and error.

This setup would have been ideal for so many of the websites we sold at Zeekee and would have saved us an enormous amount of time on the support side. If a client wanted to have the ability to edit their website we resorted to installing the proprietary CMS we used exclusively for years or wordpress, both of which were overkill for that purpose. Our customer support employees generally only understood how to work with HTML and CSS and would get lost when trying to make simple changes to Wordpress sites. The default CMS has two collections, pages and posts, which can be edited with a rich text/markdown editor. Adding a new collection type is as simple as adding a few lines in the config.yml file. Overall it's a fast, clean, little static CMS that would make a great base for something more ambitious.

![Netlify CMS Editor](/static/img/cmspost.png "Netlify CMS Editor")

There seems to be considerable hype around the concept of the JAMstack, so I'll give it some more attention in later blog posts as I work on another project I have in mind. For now it's serving it's purpose as the foundation for this simple blog.
