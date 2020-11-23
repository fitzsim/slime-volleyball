As of 2020-11-22, Emacs Slime Volleyball is maintained in
[GNU ELPA](https://elpa.gnu.org/).  To clone it, run the following commands:

    git clone https://git.savannah.gnu.org/git/emacs/elpa.git
    cd elpa/packages
    git worktree add slime-volleyball externals/slime-volleyball
    cd slime-volleyball

To report a bug, send an email to bug-gnu-emacs@@gnu.org with
"slime-volleyball" somewhere in the subject line.

slime-volleyball.el
===================

This is Emacs Slime Volleyball.

![Emacs Slime Volleyball screenshot](emacs-slime-volleyball.png?raw=true)

Requirements
------------

* A fairly recent version of GNU Emacs, compiled with librsvg support

  I tested on GNU Emacs 24.3.50.1 (i686-pc-linux-gnu)

* A graphical Emacs session

* EMMS for sound support (optional, disabled by default)

* Fast graphics and CPU

Installation
------------

Add the following to your initialization file:

    (add-to-list 'load-path "/path/to/slime-volleyball")
    (require 'slime-volleyball)

Running
-------

First make sure the Emacs frame is fairly large; for example, press F11 to make
it fullscreen.  Then:

    M-x slime-volleyball

Have fun!
