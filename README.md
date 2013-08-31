bzdocs
======

Test repo for Bugzilla docs conversion to RST and Sphinx, to put up on
ReadTheDocs.

This is very quick-and-dirty.

makebzdocs does the hackery to convert the Docbook docs to RST. Warning:
hardcoded paths; don't expect to just run them from where they are. It's
just included here to show my working.

db2rst.py is the script I found which actually does the conversion, although
I've had to enhance it quite a bit, and I'm sure there's more that can be done.

Also in the repo are the resulting RSTs, and some generated HTML using Sphinx.

If we decide this is the way to go, I'm sure we'll do this all again, but
properly this time.

Gerv
2013-08-31
