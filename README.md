# The Junk-Venture Book

Junkware book. More info at [Junkware.io](http://junkware.io).


Written with [Booktype](http://booktype.org) and [Etherpad](http://pad.comptoir.net) during a book sprint on November 2014.

Workshop in [One Space, Shanghai, China](http://one-magazine.net/one/)


Raw archives and drafts are available at :

* http://junkware.booktype.pro/the-junk-venture-book
* http://pad.comptoir.net/p/LS58
* http://pad.comptoir.net/p/junkware
* http://pad.comptoir.net/p/junkware-paper
* http://pad.comptoir.net/p/JunkBook
* http://pad.comptoir.net/p/junkware-booksprint


## Compile ODT to Latex from Booktype

    w2l -config ./scripts/w2l-config.xml ./doc/thejunkventurebook-en-2015.02.10-14.36.45.odt thejunkventurebook.tex

## Compile with Latex

    sudo apt-get install texlive-latex-base texlive-latex-extra texlive-lang-chinese latex-cjk-common
    latexmk thejunkventurebook.tex
