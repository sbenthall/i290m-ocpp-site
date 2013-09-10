Title: Lab 1 - Github, Pull Requests, and the Course Website
Date: 2013-08-09 19:20
Category: lab
Slug: lab1
Author: Seb
Summary: Our first lab will be an introduction to: Pelican, the technoogy behind our course website; Github, the currently ascendent open source "forge"; and pull requests, the way you will be handing in assignments for class.

Welcome to the first Lab of **i290M - Open Collaboration and Peer Production**.

This course website is an open collaborative project.
It is powered by a number of tools that are in wide use
in open source development.
In order to acquaint you with these tools, your coursework
will be handed in using these tools.

This lab is designed to introduce you to some of the basic
logic and workflow of these tools.
If you find that you already know this material, try finding somebody who is still learning and lend a hand.
Or, dig deeper into the documentation of the tools than we are able to cover here and try something new.

If you don't understand what's going on, ask for help and read the doucmentation provided here and linked to.
If you don't complete the tasks of that lab, that's ok.
One great thing about open collaboration is that often all the material you need to learn more is out there on-line.

## Pelican

The first thing you should know is that our course website is powered by [Pelican](http://docs.getpelican.com/en/3.2/).

Pelican is a [static-site generator](http://www.mickgardner.com/2012/12/an-introduction-to-static-site.html).
What this means is that it is a program for generating static [HTML](http://www.w3schools.com/html/) files from content files and formatting templates.  This makes for fast, secure, and comparatively idiot-proof websites.  It also allows us to back up the entire site easily in a [version control system](http://en.wikipedia.org/wiki/Revision_control) like [Git](http://git-scm.com/).

The most popular static-site generator is probably [Jekyll](http://jekyllrb.com/).  Jekyll is a Ruby framework.  Because the I School appears to have a preference for the Python programming language, we looked for a good Python static site generator.

After looking carefully at alternatives (especially [Hyde](http://ringce.com/hyde)), I [settled](http://digifesto.com/2013/08/05/reinventing-wheels-with-dissertron/) on Pelican for our class.  

We encourage you to look carefully at the Pelican [documentation](http://docs.getpelican.com/en/3.2/) to understand what's going on.  

### Under the hood

The most important thing to know about Pelican sites is that all content is written in [Markdown](http://daringfireball.net/projects/markdown/).  Markdown is a lightweight text syntax that processes directly into HTML.  It is a very popular format that is inspired by, among other things, Wikipedia syntax.

Writing content in Markdown makes it easier to separate site *content* from site 'design and layout'.  You can think of this as a continuation in the trend in web site best practices that pushed design to CSS and away from HTML years ago. (Ancient history now.)  Only now, like in a modern [content management system](http://en.wikipedia.org/wiki/Content_management_system) (CMS - like [Wordpress](http://wordpress.org/) or [Drupal](https://drupal.org/)) or web application framework (like [Django](https://www.djangoproject.com/) or [Ruby on Rails](http://rubyonrails.org/)), site *layout* is controlled by templates.  Pelican uses [Jinja2](http://jinja.pocoo.org/), a popular Python templating engine that is similar to what is used in Django.

For turning in course materials, you are required only to create and edit files in Markdown and put them in the right place in our course site repository.  But you are welcome to do much more.  One way to do that is to contribute to [Disserton](https://github.com/sbenthall/dissertron-theme), a [Pelican theme](http://docs.getpelican.com/en/3.2/themes.html#templates-and-variables) designed for open access academic publishing.

### Writing content

Please see the documentation on [writing content in Pelican](http://docs.getpelican.com/en/3.2/getting_started.html#writing-content-using-pelican).

Undertand that Pelican content can be either *blog posts* or *pages*.  This distinction should be [familiar](http://en.support.wordpress.com/post-vs-page/) to Wordpress users.  

Posts, such as this [welcome post](|filename|first.md),  are listed in revers chronological order on the blog section of the site.  Pages, such as the course [Information](|filename|pages/information.md) page,  are presented statically and not ordered by date.  