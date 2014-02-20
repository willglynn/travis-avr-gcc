travis-avr-gcc
--------------

I wanted to get AVR-GCC running on Travis-CI. So I did.

[![Build Status](https://travis-ci.org/willglynn/travis-avr-gcc.png?branch=master)](https://travis-ci.org/willglynn/travis-avr-gcc)

This repository contains:

* A sample AVR codebase (`demo.c` / `iocompat.h`), lifted from [AVR Libc](http://www.nongnu.org/avr-libc/user-manual/group__demo__project.html)
* A `Makefile`, lifted from [mfile](http://www.sax.de/~joerg/mfile/)
* A `.travis.yml` to make it dance

Travis-CI checks that it builds, which is better than nothing. Suggestions of where to go from here:

1. Use `travis-artifacts` to [export build artifacts](http://blog.travis-ci.com/2012-12-18-travis-artifacts/).
2. Unit test the hardware-agnostic parts of your app using standard tools.
