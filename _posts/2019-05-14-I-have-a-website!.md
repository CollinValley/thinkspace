---
layout: post
title: "I have a personal website!"
comments: true
description: "This post serves as my first attempt to add some content to my humble static site."
keywords: "over-engineer website jekyll rust nginx"
---

## But why though

To keep it succient, because everyone else is doing it. I've been working at Cisco Meraki for almost two years
at this point, and I figured that as a professional software developer, I at least need to have some crude site
up that I can point my relatives at, that way they know to ask me for tech support.
I've also gone and put it together because I've been spending too much time reading Hacker News,
and all the best posts on there come from someone's personal blog.  I don't have such lofty ambitions for this site,
but you never know.

## What stuff is it made from

I'm planning on doing a more in-depth post later, but to run down all the tech involved in this site.

* NGINX: To handle incoming requests as a reverse proxy, and to deal with
* Digital Ocean Droplet: Where everything is being run
* Rocket: A rust web framework that serves this site
* Jekyll: Static website generator
* Thinkspace: Jeykll theme for this site
* Docker: To contain and manage rocket.

I'm planning on continuing to expand this list in the future, I also am going to switching some of the above tech
out for more enterprisy things, just for my own enjoyment rather than any sense of practicality.

--Collin