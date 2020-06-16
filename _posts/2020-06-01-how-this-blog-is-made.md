---
layout: post
title:  "How This Blog Is Made"
categories: blog, jekyll
---

So, I made a blog. I guess a good first post is explaining exactly how I went
about that. This isn't a Webdev blog, so we won't be getting into the weeds of exactly how everything is set up, but more of an overview of the technologies involved (and an excuse to write something).

[Github Pages](https://pages.github.com/) is a great service offered by Github
that allows you to easily deploy and host webpages directly from a Github Git
repository.

It's as easy as throwing a bunch of HTML files into the repository and Github
will automatically host them under the Github (or your own) domain.

So far, so good, but I'm an Electronics engineer and building a website
completely from scratch sounds like more effort than I'd like and makes it
really difficult to quickly generate content.

## Enter Jekyll

[Jekyll](https://jekyllrb.com/showcase/) is a static site generator, that will
ingest a number of [Markdown](https://en.wikipedia.org/wiki/Markdown) format
text files and generate HTML files with all the fancy styling and boilerplate
automatically in place. Once all that is out of the way, its easy to host the
files on a webserver and have a fully functioning website.

## Becoming Stylish

So far, so great; We've generated a bunch of HTML and now its time to view our
index page.

![Jekyll Minima
Theme](https://github.com/jekyll/minima/blob/master/screenshot.png)

Not bad, but not great. The default theme that comes with Jekyll is functional,
but a bit dull to look at if I'm honest.

Fortunately, Jekyll has great theming support and a number of amazing themes
exist out there that are *almost* plug and play with Github's flavour of
Jekyll.

After a few hours of Googling themes and agonising about *exactly* which theme
I liked best I finally settled on trying to get
[Hyde](https://hyde.getpoole.com/), developed by [Mark
Otto](https://twitter.com/mdo) (Thanks!) to work with my own setup.

I really liked this theme because it strikes me as very clean and
uncomplicated, but with bold enough elements to look interesting.

First things first, the README of the Hyde repository suggests that I fork the
project and then develop my site in place. However, this then makes my site
very closely coupled to the theme itself and if I every decide to change things
up a bit in the future then I want to make things as easy as possible for
myself.

*Write about Jekyll YAML, Github Remote-Theme plugin*

*Talk about cusomisations, FontAwesome Social links*
