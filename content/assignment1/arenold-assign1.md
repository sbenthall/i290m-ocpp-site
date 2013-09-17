Title: Starting to Contribute to IPython - Pulling the Thread and Watching to Code Unravel
Date: 2013-09-16 18:20
Tags: IPython
Slug: arenold-assign1
Author: AJ Renold

## Evaluating IPython and the Project's Communications Channels

[IPython](www.ipython.org) is a significant Open Source project which strives to "provide 
a rich architecture for interactive computing" including many features, such as the increasingly
well known IPython Notebook. IPython 1.0 was released in August 2013 after the project was started
about twelve years ago.

The IPython community uses multiple communication channels to coordinate work on the project. At 
first glance, the most active channels include:

* [IPython.org](IPython.org) - The main landing page and source of information
* Developers Email List - ipython-dev@scipy.org - [Archives](http://mail.scipy.org/pipermail/ipython-dev/)
* Github - Version Control, Wiki Pages, and Issues - [IPython GitHub](https://github.com/ipython/ipython)

Other communication channels include:

* Hipchat - Messaging client on IPython.org - similar to IRC
* Stack Overflow - For "How To" Question and answer
* Reddit - For open IPython discussion

## Finding an Entry Point to Contribute

IPython uses a [system of tagging](https://github.com/ipython/ipython/wiki/Dev%3A-GitHub-workflow) 
to organize GitHub Issues and I used the issues as a starting point to learn about the current
development needs of the project and potential points of contribution. Issues tagged 'docs' or
'quickfix' are pointed out as easy beginner issues and I also browsed a few more bugs tagged
as low priority. This approach led me to finding [Issue 3653](https://github.com/ipython/ipython/issues/3653)
which was marked as a front end bug in the html notebook. One of the GitHub users that I
recognized as a major IPython contributor replied to the issue stating that it was already
supported in one part of IPython, but not making it onto the front end notebook. I decided
that this was an issue that I would investigate and create a solution for in order to
introduce myself to the community.

## Getting the Development Environment Set Up

After a quick review of the front end JavaScript for this feature on GitHub's web viewer,
I started to set up a development environment for IPython where I could play around with
the code relating to the feature in Issue 3653. I spent a few hours attempting to 
launch IPython inside of a virtual environment (venv) but was slightly confused between
launching the development version of IPython, which I cloned from my GitHub fork of IPython 
and my system installation of IPython.

## Pull the Thread and Watching the Code Unravel

After struggling for a few hours, I decided to take to the IPython developer mailing list
to introduce myself, this issue I am interested in working on, and ask for help on starting
a clean development environment. [My first message](http://mail.scipy.org/pipermail/ipython-dev/2013-September/012330.html)
Received a positive response which was much more than I expected. Not only did the
community welcome my willingness to contribute, but I received pointed help on setting up
the development environment AND was referred to additional information on Issue 3653. 
Apparently, I stumbled upon a portion of the IPython core that is proposed for a major
refactor [IPEP 11](https://github.com/ipython/ipython/wiki/IPEP-11%3A-Tab-Completion-System-Refactor)
and this felt a little bit like pulling a small thread (the initial bug) and discovering
a deeper motion in the project that seems to require more knowledge and expertise of the 
core library.

## Judging the Response: IPython is a Healthy Community!

The strong response that my request for help and offer to contribute suggests that IPython
is an active and healthy community which will welcome and benefit from my contribution. 
I believe that signalling this is an important part of attracting contributors to join, 
as volunteers are likely to be less motivated by a cold reception. I believe this also
creates strong goodwill to motivate potential contributors and even users to share about
the project, increasing the likelihood that new contributors or users will discover the 
project. Personally, the welcome response has motivated me even more to contribute!
