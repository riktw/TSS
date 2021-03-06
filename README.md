# TSS-COMS20805

[![Build Status](https://travis-ci.org/TransputerSystems/TSS.svg?branch=master)](https://travis-ci.org/TransputerSystems/TSS)
[![Codacy Badge](https://api.codacy.com/project/badge/Grade/2d1f5e7218a84a42bd07c20d3a7a9718)](https://www.codacy.com/app/github_63/TSS?utm_source=github.com&amp;utm_medium=referral&amp;utm_content=TransputerSystems/TSS&amp;utm_campaign=Badge_Grade)

The tss Occam Toolchain allows you to compile and assemble Occam 2.1 for the Transputer/OpenTransputer. It also includes a simulator for testing those programs.

## [User documentation](doc/user)
 
## Project status

### Compiler

* Handles most of the Occam 2.1 language
* No type checking
* Does not support external channels (a.k.a. links) but does support soft channels and IO Ports

### Assembler

* Fully supports Transputer assembly
* Supports OpenTransputer channel configuration
* Produces binaries that run in the simulator
* Produces binaries that run directly on OpenTransputer hardware

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

## Other tools

You can install our [language-occam](https://atom.io/packages/language-occam) package for occam syntax highlighting in Atom.


### Added info (RtW)
I have zero experience with Java or Maven, try the changed I made at your own risk...
Build with: 
mvn clean install
A small fix in the pom.xml fixed the simulator executable.
In every folder, in the target folder the "somethingsomethng-with-dependencies.jar" seems to be the executable, run with java -jar
