---
layout: default
title: GNU Build System
---

GNU Build Sytem
=================

*   [Overview](#overview)
*   [Sample](#sample)

**Notice:** This guide is written with Markdown.

* * *

<h2 id="overview">Overview</h2>

From Wikipedia:

The GNU build system, also known as the Autotools, is a suite of programming tools designed to assist in making source code packages portable to many Unix-like systems.

It can be difficult to make a software program portable: the C compiler differs from system to system; certain library functions are missing on some systems; header files may have different names. One way to handle this is to write conditional code, with code blocks selected by means of preprocessor directives (#ifdef); but because of the wide variety of build environments this approach quickly becomes unmanageable. Autotools is designed to address this problem more manageably.

<h2 id="sample">Sample</h2>

* Working tree
    * source in src/
    * documentation in doc/
    * man page in man/
    * scripts in scripts/
    * examples in examples/

* Cleaning up

Move away every possible Makefile you have in the package.

* Installing auto

* Generating configure.ac
    $ autoscan
