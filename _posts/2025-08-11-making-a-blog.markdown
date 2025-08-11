---
layout: post
title:  "Making a blog"
date:   2025-08-11 14:05:00 +0700
categories: update
---

Sorry for disappearing for so long -- I can't believe it's been a over year since my last post on YouTube. For those of you curious about what happened, I was mainly busy with my studies. On top of that, I felt quite lost about what I wanted to do or become, while it seemed like everyone around me had already figured that out.

I had been thinking about making a blog for months now, but it was only at the beginning of August that I started figuring out how to actually make it happen. My third year in university, although stressful, taught me a greate deal about web development. For the first time in my life, I began to understand the basics of website and web services, and I wanted to make something personal with that knowledge.  

Initially, I want the blog to be more dynamic, for exapmple, readers would be able to like and comment on my posts. But I soon realized it was a bit ambitious. I would have to manage my web server, maintain a remote database, implement user authentication, and so on. Although I had learned about these in school, they were mostly for short-lived and practice projects. In real deployment, there is a risk of high costs and, worse, potiential vurnerabilities due to my inexperience. So, for now, a static website made more sense -- all I wanted was to put some words on the Internet.

At first, I considered using Itch.io's dev-blog featurem, but it lacks customization I wanted, especially for templates and page routing. Then I asked ChatGPT for suggestions and its first recommendation was [GitHub Pages with Jekyll](https://jekyllrb.com/docs/github-pages/).

Following a [GitHub's tutorial](https://docs.github.com/en/pages/setting-up-a-github-pages-site-with-jekyll/creating-a-github-pages-site-with-jekyll?platform=mac), I quickly set up the repository of my blog. It turned out that all it required was a repository with a specific name and branch. Setting up Jekyll though, was a bit trickier. Since Jekyll is built with Ruby -- a language that I had heard of but knew nothing about -- I was unsure at first. Thankfully, [Jekyll's documentation](https://jekyllrb.com/docs/) was easy to follow and I was able to have the default blog site within a day.

When it came to customization, Jekyll has a community offering awesome pre-made themes. They come with a variation of layout, page routing and color pallete. They also serve different purpose too, etheir bussines advertisement, portpolio or documentation:  

![jekyll_theme]({{ site.url }}{{ site.baseurl }}//assets/images/free_jekyll_themes.png)

Moreover, Jeykyll allowed me to override the default `minima` theme through Sass's `.sccs` stylesheets. This was very helpful since tweaking existing files allowed me to gradually shape the look to my liking, rather than styling everything from scratch. However, I didn't want to just change a few details, like colors or fonts, and end up with the default theme but in a different skin. I later found out that layouts could also be overidden in the same way. But since I had no idea which layout I wanted, I decided to follow another blog as a reference.

It happened when I looked into the *Fruitiger Aero* asthetic to apply it to my site. I came across this [archive website](https://frutigeraeroarchive.org/) made by Daniele63. Not only was the site styled fully in this asthetic, but it also offered a great collection of themed assets, including wallpapers and icons. Just look how beautiful this website is:

![frutiger_aero_archive]({{ site.url }}{{ site.baseurl }}/assets/images/frutiger_aero_archive.png)

I don't intend to make my blog entirely in this asthetic, but its liveliness caughts my attention, especially compared to the flatness of many modern websites.

The author of this site also has his own blog. It seems fairly new, with only two posts so far, both from July this year. The later post describes how to make your own indie website, which I wished I had read it ealier. If you are new to web development or just want to set up your own blog, I recommend reading the post [here](https://frutigeraeroarchive.org/blog/posts/26_07_2025).

In the end, I borrowed his blog layout, noticeably with an image banner on the top, and the blog posts aligned to the left. Here's his blog index page for reference:

![frutiger_aero_archive_blog]({{ site.url }}{{ site.baseurl }}/assets/images/frutiger_aero_archive_blog.png)

I even reused his fancy gradient for the navigation bar. The cropped banner image on the top was from his main site -- specifically, a Windows Vista wallpaper numbered [Windows Vista 49](https://frutigeraeroarchive.org/images/wallpapers/windows_vista/windows_vista_49.jpg).

So that’s a quick look at the process of setting up this site. One more thing worth meantioning is that Github only allows free hosting for public repositories, so the source code this site is now on Github, specifically at [this repo](https://github.com/Teiple/teiple.github.io.git). I’ll keep working on it, as there’s still a lot I want to add — a dark theme, an RSS feed, and maybe other pages like a CV or portfolio.

As for the content, I can't promise it will be all about development. There are other topics that I'd like to explore, such as art or reviews, but it likely lean more towards development.

Thank you for reading my first blog post! Have wonderful day.