markdown
========

Utility for previewing markdown markup from within markdown-mode in emacs

Requires `Markdown.pl` from
[Daring Fireball](http://daringfireball.net/projects/markdown/) or a similar
utility that renders html from a formatted Markdown text file.

This utility is MIT Licensed.

# Installation #

1. Place the lib files in an appropriate directory (/usr/lib, /usr/lib64,
   ~/lib, etc)
2. Place the bin files in an appropriate directory (~/bin, /usr/bin, etc.)
    ensure that the bin/markdown file is availabel in the $PATH environment variable.
3. Adjust the configuration parameters within the /bin/markdown script
   (documentation is inline)

# Usage #

    markdown file-to-render

An HTML document will be rendered to STDIO


## With emacs markdown-mode ##

[markdown-mode.el](http://jblevins.org/projects/markdown-mode/) is available
from jblevins.org.

While editing a markdown document, use the keys `C-c C-c p` or `M-x
markdown-preview` to render the document and preview it within your browser.
