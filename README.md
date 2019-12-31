# [FirstSite](https://davidhsmith.github.io/FirstSite)

## Github Pages
This is an experiment with setting up github based website.  You can bring up this web site using this link:

[FirstSite](https://davidhsmith.github.io/FirstSite)

Try it now by clicking on the link above!

Github Pages is really easy to set up and use, and it is free.  This handles static web sites only and the web pages are all inside of a git repository.  Of course, the repository can be edited on any PC and simply committed to github.  The root web page is created from README.md.  I created this file directly on [GitHub](https://GitHub.com) using their direct-edit tool for text files.  This works out to be usable, but a little awkward, so I will be investigating more powerful markdown editors.  Being able to create static web pages on a PC, then push them to [GitHub](http://github.com) certainly seems to be a possiblity for a journaling tool.  GitHub's recommendation seems to be a tool named [jekyll](https://jekyllrb.com)


## Image handling: USB C Hub for ASUS VivoBook
Here's a picture of the USB Hub with gigabit Ethernet that I bought off Amazon to use with my ASUS VivoBook.  The VivoBook doesn't have an Ethernet Port and limited USB.

![](51V7EBCMMUL._SL1000_.jpg)

Surprisingly that worked great on the image.  It is inserted and resized to fit between inside the Web page paragraph width.

As an aside, the adapter seems to work awsome - I got full 1-Gigabyte transfer speeds using iperf3.


## Jekyll static web page generator
Jekyll is a static web page generator developed and used by Github.  Seems like a reasonable way to go so I installed it on BBLinux (Ubuntu 18.04 box).  First you install Ruby, the use the Ruby package manager, gem, to install the Jekyll application.  This worked, at least to a level that I could run *jekyll new portfolio* to create a simple directory structure.  Then I ran *jekyll serve* to create and serve a minimalist web site.

Next step - how to install Jekyll on my windows 10 computer (VivoBook 14).

1. Install Ruby from rubyinstallers.org.
2. Install jekyll using the gem package manager.
