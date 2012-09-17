---
layout: post
title: "Upgrading the Blog"
date: 2012-09-05 02:10
comments: true
categories:
---

### Because if it ain't fun, it won't get done

I created this blog to reflect on my journey to become a coder/designer. It is also a place for me to experiment with code and design. Although I've customized several Wordpress sites before, I decided I wanted to try something new and more lightweight.

I started out by simply hand coding the html for each post. Turns out that was way too much overhead, and posting felt like work instead of being fun. So it simply didn't get done. I needed to streamline my authoring flow. Enter [Octopress](http://octopress.org/docs/).
<!--More-->

Lucky for me, some really smart folks have come up with a much better way to blog. Octopress iss a framework for [Jekyll](http://jekyllrb.com/), which is a "blog aware static site generator" written in Ruby.

It makes it really quick and easy to post, but also keeps things close to the metal in terms of the authoring tools. Octopress is set up to run on github pages so all you have to do is write a post in [Markdown](http://daringfireball.net/projects/markdown/), generate the static html site, and deploy it. It looks a little something like this:

```
$ rake generate
```
(It comes with Solarized code highlighting!)
```
$ rake deploy
```

This pushes your latest changes to github, which then automatically deploys via [Github Pages](http://pages.github.com/).

So that means you also automatically get the added benefit of being on version control, so if you want to branch off with an experiment, manage to really screw something up, or want to collaborate with other authors, you have github to manage that process.

I'm looking forward to get to know Octopress better, and actually blogging while at it!