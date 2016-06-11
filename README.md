Laptop
======
[![Build Status](https://travis-ci.org/monfresh/laptop.svg)](https://travis-ci.org/monfresh/laptop)

Laptop is a script to set up an OS X computer for web development.

Forked from https://github.com/monfresh/laptop

This version includes Brew Packages & Brew Cask Install specific to my Setup

Install
-------

Begin by opening the Terminal application on your Mac. The easiest way to open
an application in OS X is to search for it via [Spotlight]. The default
keyboard shortcut for invoking Spotlight is `command-Space`. Once Spotlight
is up, just start typing the first few letters of the app you are looking for,
and once it appears, press `return` to launch it.

In your Terminal window, copy and paste each of these two commands one at a
time, then press `return` after each one to download and execute the
script, respectively:

```sh
curl --remote-name https://raw.githubusercontent.com/LaurentPerche/Install-laptop/master/mac
bash mac 2>&1 | tee ~/laptop.log && source ~/.rvm/scripts/rvm
```
