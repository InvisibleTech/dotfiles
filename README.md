# dotfiles
A collection of configs to keep on hand and share when useful.

## SBCL Config File
Supports loading QuickLisp and enabling linedit in the REPL.  Turns out
you cannot just do the QuickLisp install of linedit, at least on
OSX.

Got idea from these instructions:
 https://www.cs.dartmouth.edu/~sergey/cs59/lisp/sbcl-quicklisp-install-log.txt

But it depended upon linedit being in QuickLisp repos.  So simply follow
the instructions at that link to deal with the missing signature to verify
the QuickLisp install.  However, to get QuickLisp and read about it:

https://www.quicklisp.org/beta

To install linedit as a local project not found in QuickLisp repos, follow
directions for loading a local project here:

https://www.quicklisp.org/beta/faq.html

For linedit itself: https://github.com/sharplispers/linedit

These steps as well as the content I added to .sbclrc get you a usable REPL.
