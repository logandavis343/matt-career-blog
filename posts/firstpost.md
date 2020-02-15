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

After cloning the repo and installing dependencies I ran the command to build the site and started looking to see how it worked so I could change the appearance. Eleventy provides a command which starts up a Browsersync web server and begins watching the current directory for any changes to template files which made it easy to see what those template files were for. There is ample documentation but it feels good to know I still have enough brain cells to get the gist of something like this through intuition and trial and error.

This setup would have been ideal for so many of the websites we sold at Zeekee and would have saved us an enormous amount of time on the support side. If a client wanted to have the ability to edit their website we resorted to installing the proprietary CMS we used exclusively for years or wordpress, both of which were overkill for that purpose. Our customer support employees generally only understood how to work with HTML and CSS and would get lost when trying to make simple changes to Wordpress sites. 

Using Netlify introduced me to some things I have never touched before: Static site generators, javascript templating engines, and the JAMstack. I'll be posting later about my experience building a JAMstack site completely from scratch.

It's very, very exciting to be working on something that will actually bring me closer to my goal rather than just sitting around thinking about it.
