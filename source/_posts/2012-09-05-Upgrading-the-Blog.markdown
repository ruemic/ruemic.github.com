---
layout: post
title: "Upgrading the Blog"
date: 2012-09-05 02:10
comments: true
categories:
---

### Because if it ain't fun, it won't get done

I decided to start a blog earlier this year to journal my adventures in becoming a better coder/designer. I wanted my blog to be an example of my front end skills.

Althought I've customized several Wordpress sites before, I wanted to hand roll my own blogging system so I would have to figure things out for myself.

 So I started out by simply hand coding the html for each post. It quickly become apparent that this was just way to much overhead to use. Posting felt like work instead of being fun, so it simply didn't get done.

Lucky for me, some really smart folks have come up with a much better way to blog. [Octopress](http://octopress.org/docs/). It's a framework for [Jekyll](http://jekyllrb.com/), a "blog aware static site generator" written in Ruby.

<!--More-->

It makes it really quick and easy to post, but also keeps things close to the metal in terms of the authoring tools. Octopress is set up to run on github page so all you have to do is write a post in [Markdown](http://daringfireball.net/projects/markdown/), generate the static html site, and deploy it. It looks a little something like this:

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