---
title: "Website Refresh"
date: 2017-12-15T11:52:42-05:00
categories:
- tech
- website
tags:
- tech
- website
keywords:
- tech
- website
autoThumbnailImage: false
thumbnailImagePosition: "left"
thumbnailImage: http://res.cloudinary.com/hunt2fish/image/upload/v1513344634/Hunt2Fish_podcast_khgz7a.png 
coverImage: http://res.cloudinary.com/hunt2fish/image/upload/v1513344634/Hunt2Fish_podcast_khgz7a.png 
metaAlignment: center
draft: false 
---
A few words about the technical side of things...

<!--more-->

### The Problem

When setting up the site back in 2016, we weren't sure if this would ever go anywhere. For ease of use and convenience I set us up with a shared hosting provider and used the Wordpress platform. Wordpress has never been my favorite for a number of reasons, but it allowed us to get our content up and out easily for those without a technical background. Well, we have grown tremendously which has put a load on the server and the bloated software platform we were using. Add to that the slowness and unreliability of the shared server, we ran out of memory and were unable to load the page or access the admin area of Wordpress. We had podcast episodes ready to go and this put us in a bind.

### The Solution

Our content is now hosted through a number of different services: 

* Podcasts are on [Podbean](http://hunt2fish.podbean.com/) 
* Images are on [Cloudinary](https://cloudinary.com/) 
* The website is on [netlify](https://www.netlify.com/) 
* The source code is in [GitHub](https://github.com/gforster/Hunt2Fish) 
* I'm using the [Hugo](https://gohugo.io/) static site engine because I've really been enjoying working in [Go](https://golang.org/) lately.
* Content is written in Markdown. So, no gui, but it is rather straightforward if anyone less technical wishes to contribute.

### What does all of this mean? 

* Our site is faster
* Our site is more reliable
* Our podcasts episodes will get to you faster and better
* We can focus our time on other areas, like creating good content
* We have great version control in case anything goes wrong
* We can easily switch any of the micro-service providers listed above if they have any issue
* It should all be transparent for our listeners and readers!

If you have any questions, please let us know. I still have some improvements to make, but overall we are up and running smoothly!

thanks!

~gabe
