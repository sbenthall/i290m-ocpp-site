Title: Lab 4 - Build Pelican site locally
Date: 2013-09-30 21:30
Category: lab
Slug: lab4
Author: Seb



This guide takes you through the steps you need to build and test the course website locally.  From now on, you will be expected to test your commits by publishing the site locally before submitting pull requests.

Our site is made with Pelican, a Python static-site generator.

If you are familiar with Python development, you are probably familiar with [virtualenv](http://www.virtualenv.org/en/latest/), a tool for creating isolated Python environments.  In this guide we will use virtualenv.  Please install it now, or proceed without it at your own risk.

1. Make a directory to work in, and go into it

    mkdir i290m-test

    cd i290m

2. Make a virtualenv there.  This will create a Python environment where you can install things without interacting with the Python packages you have installed globally on your machine

    virtualenv venv

3. Activate the virtualenv.  This will change the Python instance you are using, and make it so any libraries you install are installed to the local instance

    source venv/bin/activate

4. Clone the course site.  Use the URL of your own fork if you are intending to push changes back upstream.

    git clone https://github.com/sbenthall/i290m-ocpp-site.git

5. Install [Pelican](http://docs.getpelican.com/en/3.2/) and Markdown

    pip install pelican

    pip install Markdown

6. Clone the site theme and make sure Pelican knows about it

    git clone https://github.com/sbenthall/dissertron-theme.git
    
    pelican-themes -i dissertron-theme/

7. Go into the site directory, publish the content to HTML, and serve the files locally

    cd i290m-ocpp-site/

    make publish

    make serve

8. Explore the website, which should be at [localhost:8000](http://localhost:8000/)

9. You can use Ctrl-D to interrupt the server and regain control of your terminal.  Or you can open another terminal to make changes to content and run `make publish`.  You should immediately be able to see the changes by refreshing your browser.


###Troubleshooting:

You may encounter this error:

    No distributions matching the version for pytz (from pelican)

In that case, try using this command instead to install Pelican:

    easy_install pelican

**On some operating systems, `make` does not work.** If you have trouble with the `make` command, try using Fabric, a more portable Python build tool.  Instructions for using Fabric with Pelican are [here](http://docs.getpelican.com/en/3.3.0/getting_started.html#fabric).
