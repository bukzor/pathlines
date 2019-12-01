# Pathlines

A "dead simple" set of utilities for dealing with advanced problems in path
handling. In particular, path normalization and calculation of relative paths
with respect to  some arbitrary base, without requirements on path existance.

## Intent

The intent is to use this as a dependency of autotools-based projects at
configuration time in order to make those projects "relocatable" -- a user can
move the installation without breaking it. This requires fine handling of
relative paths, and previously there was no sufficiently capable and portable
solution (that I know of).

## Minimum requirements

* sed
* bash
* coreutils

## Supported platforms

* linux
* macos (with or without homebrew)
* windoze (with cygwin or the new "posix for windows" stuff)
