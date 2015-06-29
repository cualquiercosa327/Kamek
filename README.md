# Kamek
a nice code injection engine for Wii games - (c) Treeki 2010-2015

### Introduction

Kamek is an engine for injecting custom code into Wii games - it's designed for
*New Super Mario Bros. Wii*, but it should work with many other games as well.

(This is a fully rebuilt version of the toolchain I developed from 2010 to 2013
 for the [*Newer Super Mario Bros. Wii* project][newer]. It cannot build Newer
 in its current form, but this may be possible later.)

More details will be provided later, I'm also working on a series of blog posts
about this project and its internals.

### Requirements

To build and run the Kamek linker:

- .NET Framework 4.5 *(Mono support for non-Windows OSes is a definite goal,
  may not be functional just yet)*

To compile code:

- Freescale ['CodeWarrior Special Edition'][cw] for MPC55xx/MPC56xx v2.10

Support for other compilers such as GCC and Clang is not planned.
(C++ code generated by these compilers uses a different ABI to
 CodeWarrior, so features like classes and virtual inheritance only work
 properly when CW is used.)



[cw]: http://www.freescale.com/webapp/sps/site/overview.jsp?code=CW_SPECIALEDITIONS
[newer]: https://github.com/Treeki/NewerSMBW

