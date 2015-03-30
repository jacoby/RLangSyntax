Default release of KomodoEdit features language syntax highlighting for a
large number of languages, but not for R. There existed SciViews-K
(http://www.sciviews.org/SciViews-K/), but it stopped working with
KomodoEdit somewhere around four major releases ago.

The Komodo twitter account (https://twitter.com/komodoide/) pointed me to
a community post (http://community.activestate.com/node/9671) where someone
with my problem found the .udl files (the main part) and made his own dang
Syntax. Great for him, sure, but what does that get me?

So, I followed in his steps, figured out how to build and install the thing.
Plus one step more: I put it on GitHub!

The UDL I forked from the abandoned SciViews code is MPL 1.1/GPL 2.0/LGPL 2.1,
so I suppose this has to be the same.

BUILD:

Assuming you've pulled this into ~/dev/RLangSyntax and your Komodo install is in
~/opt/Komodo, you can build this yourself with the following command:

    cd ~/dev/RLangSyntax
    ~/opt/Komodo/lib/sdk/bin/koext build --unjarred

DOWNLOAD:

The point to GitHub is to get the code, but if you just want the xpi, I have it on my Dropbox. [RLangSyntax XPI](https://www.dropbox.com/s/lw53t7dqh9agv92/rlangsyntax-0.1.1-ko.xpi?dl=0).

TODO: 
creating a project GitHub.io page
adding more pizzazz to highlighting.


