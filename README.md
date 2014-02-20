travis-avr-gcc
--------------

I wanted to get AVR-GCC running on Travis-CI. So I did.

This repository contains:

* A sample AVR codebase (`demo.c` / `iocompat.h`), lifted from [AVR Libc](http://www.nongnu.org/avr-libc/user-manual/group__demo__project.html)
* A `Makefile`, lifted from [mfile](http://www.sax.de/~joerg/mfile/)
* A `.travis.yml` to make it go
