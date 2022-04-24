# Welcome to my personal build of slock


This project exists solely to host my personal patched version of [slock][1] and make it
easily accessible for all my devices and gain familiarity with working with github. Below
is included the original readme from the [suckless slock project][2].

[1]: https://tools.suckless.org/slock/ "slock homepage"
[2]: https://git.suckless.org/slock "slock sourcecode"

### Patch applied
> - [Foreground and background][3] 

[3]: https://tools.suckless.org/slock/patches/foreground-and-background/ "Foreground-background"

slock - simple screen locker
============================
simple screen locker utility for X.


Requirements
------------
In order to build slock you need the Xlib header files.


Installation
------------
Edit config.mk to match your local setup (slock is installed into
the /usr/local namespace by default).

Afterwards enter the following command to build and install slock
(if necessary as root):

    make clean install


Running slock
-------------
Simply invoke the 'slock' command. To get out of it, enter your password.
