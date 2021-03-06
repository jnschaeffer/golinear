## Introduction

golinear is a package for training and using linear classifiers in the Go
programming language (golang).

**Note:** This package is still new, its API may change, and not all
of liblinear's functionality may be available yet.

## Installation

To use this package, you need the
[liblinear](http://www.csie.ntu.edu.tw/~cjlin/liblinear/) library. On Mac
OS X, you can install this library with
[Homebrew](http://mxcl.github.com/homebrew/):

    brew install liblinear

Ubuntu and Debian provide packages for *liblinear* that can be installed
with APT:

    apt-get install liblinear-dev

This package can be installed with the <tt>go</tt> command:

    go get github.com/danieldk/golinear

The package documentation is available at: http://go.pkgdoc.org/github.com/danieldk/golinear

## Plans

1. Stabilize the API.
2. Port classification to Go.
3. Port training to Go.

We will take a pragmatic approach to porting code to Go: if the performance penalty is minor,
ported code will flow to the main branch. Otherwise, we will keep it around until the performance
is good enough.

## Examples

Examples for using golinear can be found at:

https://github.com/danieldk/golinear-examples
