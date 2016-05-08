# TSS-COMS20805

[![Build Status](https://travis-ci.com/sammhicks/TSS-COMS20805.svg?token=dbgXCzPBz3EpuBEbnqMF&branch=master)](https://travis-ci.com/sammhicks/TSS-COMS20805)
[![Codacy Badge](https://api.codacy.com/project/badge/grade/90ae6f82c1e34063a3810125d65571ea)](https://www.codacy.com)

The tss Occam Toolchain allows you to compile and assemble Occam 2.1 for the Transputer/OpenTransputer. It also includes a simulator for testing those programs.
 
## Project status

### Compiler

* Handles most of the Occam 2.1 language
* No type checking
* Incomplete IO support

### Assembler

* Fully supports Transputer assembly
* Supports OpenTransputer channel configuration
* Produces binaries that run on the simulator
* Does not yet produce binaries that run directly on the Transputer or OpenTransputer hardware

### Simulator

* Supports most of the Transputer features
* Limited debugging support
* Supports multiple-Transputer execution and communication

## Acknowledgements

This project relies on a number of excellent libraries.

* [ANTLR](http://www.antlr.org/) (BSD)
* [JUnit](http://www.junit.org/) (Eclipse Public License 1.0)
* [antlr-denter](https://github.com/yshavit/antlr-denter) (MIT)
* [gson](https://github.com/google/gson) (Apache 2.0)
* [AssertJ](http://joel-costigliola.github.io/assertj/) (Apache 2.0)
* [FindBugs](http://findbugs.sourceforge.net/) (LGPL)
* [jopt-simple](https://pholser.github.io/jopt-simple/) (MIT)
* [snakeyaml](https://bitbucket.org/asomov/snakeyaml) (Apache 2.0)

### Other

* Maven
* pegdown-doclet
* javafx-maven-plugin