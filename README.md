slime-volleyball.el
===================

This is Emacs Slime Volleyball.

Requirements
------------

* A fairly recent version of GNU Emacs
  
  I tested on GNU Emacs 24.3.50.1 (i686-pc-linux-gnu)

* A graphical Emacs session

* EMMS for sound support (optional, disabled by default)

Installation
------------

Add the following to your initialization file:

    (add-to-list 'load-path "/path/to/slime-volleyball")
    (require 'slime-volleyball)

Running
-------

First make sure the Emacs frame is fairly large; for example, press F11 to make
the frame fullscreen.  Then:

    M-x slime-volleyball

Have fun!
