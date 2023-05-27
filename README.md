# The Ion Programming Language

This is a fork of the original Ion compiler from Per Vognsen's ambitious [Bitwise](https://github.com/pervognsen/bitwise) project that has unfortunately been discontinued.

The original intention of Ion compiler was to emit machine code for a Risc-V target, but Per was bootstrapping via it a C code generation backend. The part I found interesting is that unlike other compile-to-c languages the output is very idiomatic, and the language itself purposely maintains close to C semantics while still managing to smooth off many of the rough edges.

My intention is to maintain Ion as a compile-to-c language which I intend to use for my own projects. Over time I hope to add more tests, documentation and bug fixes.