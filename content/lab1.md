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

Posts, such as this [welcome post](|filename|first.md), are listed in reverse chronological order on the blog section of the site.  Pages, such as the course [Information](|filename|pages/information.md) page, are presented statically and not ordered by date.

We can use Github to browse the directory structure of our website's content.  Content goes in the [content/](https://github.com/sbenthall/i290m-ocpp-site/tree/master/content) directory.  Blog posts go right there. Pages go into the [pages/](https://github.com/sbenthall/i290m-ocpp-site/tree/master/content/pages) subdirectory.

***For this lab, you need to update the [Class Roster](|filename|pages/roster.md) page with some information about yourself: your name, your status as a student (program, year),  the project you are going to try to contribute to (with a link), and why you took the course.***


## Git

We have the site content and history backed up by a Git repository.
You may have heard of Git and/or Github already.
Git is a version control system (VCS).
We will talk about VCS in more detail in the next lecture.
For now, it's time to get some hands on experience.

***If you have not worked much with *Git* in the command line (as opposed to Github the on-line social forge, which is different), go through [this web-based tutorial](http://try.github.io) now.***

That tutorial simulates what you would do running Git on your local machine, using your **command line**.  (You do use your command line, don't you?)

It is totally worth it to learn how to use Git locally.  Maybe you will have to for your participation in an outside project.  For our purposes, we will lean heavily on GitHub, a service that provides a lot of web-based functionality on top of hosted Git repositories.

## GitHub

[GitHub](https://github.com/) provides a web application layer over hosted Git repositories.  It is largely responsible for the wide adoption of Git throughout the open source world.  There are other services like it, such as [BitBucket](https://bitbucket.org/), a similar service for [Mercurial](http://mercurial.selenic.com/) repositories.

***If you haven't already done so, sign up for GitHub and get a username now.***

Git is a *distributed* version control system.
This is significantly different from undistributed version control systems (like [Subversion](http://subversion.apache.org/)) in important ways that we will discuss in the next lecture.
One big difference is the Git, especially with the help of Github, enables friendly [forking](http://en.wikipedia.org/wiki/Fork_%28software_development%29).

***Go through this GitHub [tutorial](https://help.github.com/articles/fork-a-repo) about how to fork a repo now.  Then read through this [documentation about pull requests](https://help.github.com/articles/using-pull-requests).***

Turns out, GitHub makes it very simple to edit files through their web interface, even providing syntax highlighting while editing Markdown.

***Now:***

1. Familiarize yourself with [Markdown](http://daringfireball.net/projects/markdown/syntax) syntax.
2. Fork the course website [repository](https://github.com/sbenthall/i290M-ocpp-site).
3. Modify the roster.md file in your fork on the repository through the GitHub interface.  Add yourself to a list, in alphabetical order by last name, with your name, status as a student, external project and reason for taking the course.  For example:
> Gnaeus Pompeius, 2nd year Masters student, I School. I am contributing to the [OpenCog](http://opencog.org/) project. I am interested in open collaboration and peer production because Caesar has illegitimately seized power and the Republic must rise again.
4. Make a pull request with your change.

You're almost done with the lab!

Now comes the fun part: it may be that many of you have been trying to edit the same file at the same time.
Since commits are made as [diffs](http://en.wikipedia.org/wiki/Diff), sometimes somebody else's change will invalidate or *conflict* with your own.

***If this happens, we won't be able to accept your pull request.
You will need to *merge* the changes from the remote repository into your own, and make a new pull request.***

Please stick around in lab until we get your pull request accepted.
We may need to coordinate as a class to make sure we don't keep overriding each others commits.

When you've completed this lab, you will officially be a [contributor](https://github.com/sbenthall/i290m-ocpp-site/graphs/contributors) to the course project.
GitHub provides some nice visualizations so you can see your level of participation relative to others.
    