# psmt2-frontend

A library to parse and type-check a conservative extension of the SMT-LIB 2
standard with prenex polymorphism.

## Build and Install Instructions

The easiest way to install psmt2-frontend is to use OPAM:

    $ opam install psmt2-frontend

If you want to install psmt2-frontend from sources, use the following
instructions:

    $ autoconf (if configure is not present)
    $ ./configure
    $ make opam-deps (if you are using OPAM and some deps are missing)
    $ make

to compile and install `psmt2-frontend` on your system. You can
uninstall the library with `make uninstall`.

## TODO

- Dev is in early stage. This is a first prototype that needs reimplementation

- Needs some documentation.

- Some features of SMT-LIB are not yet supported (Floating point, Bit-vectors, etc)


## Licensing

The library is distributed under the terms of the Apache License version 2.0 (see LICENSE file).


