---
layout: blog
author: Christian Wittrup
title: Complete redesign from ground up
date: 2020-09-11T12:24:52.911Z
description: It may seem a bit off that my third post, ever, on this site is one
  where I announce the introduction of a new design and setup. Nevertheless this
  is the reality.
tags:
  - css
  - hugo
  - grid
  - design
  - responsive
---
It may seem a bit off that my third post, ever, on this site is one where I announce the introduction of a new design and setup. Nevertheless this is the reality.

The setup is actually pretty much untouched and resembles what I wrote about in [my very first post.](https://www.wittrup.xyz/posts/2020-07-03-first-ever-post-everything-has-changed/)

The site is still build using hugo, it is still hosted on netlify and I still utilize Github as the repository.



## The real change is in the design of the page

Previously I used a predefined theme called [noteworthy](http://wittrup.link/noteworthy), which OK and served it's purpose but wasn't made for me, with my specific requirements in mind.

Obviously my requirements are somewhat limited with a page and setup like this, but I still missed some flexibility in terms of the design. More than flexibility in the design, i lacked the understanding of how everything was constructed. 

The new theme has been designed and build by me, which of course means that I now have a full understanding of how everything has been setup, which hugo features I'm using, how the CSS has been structured and how hugo builds each page. 

Building the CSS from scratch has allowed me to utilize responsive technologies such as [CSS grid](https://www.wittrup.link/completeguidetogrid) (thank you css-tricks for the great overview of how this works), which means that the site should be functioning and optimized for all devices. Also by using variables for my colors I'm able to adjust the color scheme of the site in the blink of an eye. 

There are definitely still areas of hugo I need to get more confident with. Specifcally I really need to have an additional look at the "tags"-page. This page is currently one big mess with no real structure. Once I have time to dig into the list and taxonomy functionality in hugo this is something I will fix.

I still play with the idea of making the design available to the wider hugo community, but until I feel like this is fixed I will wait a bit.