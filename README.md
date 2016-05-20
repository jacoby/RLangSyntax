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

# BUILD:

Assuming you've pulled this into ~/dev/RLangSyntax and your Komodo install is in
~/opt/Komodo, you can build this yourself with the following command:

    cd ~/dev/RLangSyntax
    ~/opt/Komodo/lib/sdk/bin/koext build --unjarred

# DOWNLOAD:

Newest XPI is in https://github.com/jacoby/RLangSyntax/releases

Thanks to the Komodo developers, who are giving me a practical short course in
developing on GitHub today.

# USAGE:

This tool does not set your editor to associate RLangSyntax with R files,
so you'll have to go into the File Association to set that. For individual
files, go to View > View As Language > R.
