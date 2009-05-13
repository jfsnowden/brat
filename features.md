---
title: Brat Features
layout: default
---
## Current Features

* Compiles to the [Neko VM](http://nekovm.org/) the way Python compiles to its bytecode
* Parser is in [Ruby](http://ruby-lang.org) using [TreeTop](http://treetop.rubyforge.org/)
* Typeless, and pretty much classless
* Everything is object, except functions
* And functions are closures, which can be attached to objects to make methods
* Objects use a prototyping system and are completely open (plus, you can clone or inherit, your choice)
* Tail calls are optimized to make infinite loops faster (and more inifinite)
* Interactive shell just like the big boys
* Built in hash tables and dynamic arrays
* Very flexible unary and binary operators
* Arbitrary precision numbers using [GMP](http://gmplib.org/)

## Current Limitations

* Only running on Linux at the moment
* Limited built-in objects and methods
* Programs limited to single file
* Mixins limited to squish-ins