This repository contains a Roman Numeral utility library implemented in "C". It performs
addition and subtraction of roman numbers. See src/romanNumLib.h for the supported public
functions. This software was written with the intent of demonstrating the Test Driven 
Development (TDD) process.

The src/ directory contains the library source files romanNumLib.c and .h

The test/ directory contains unit tests for the library. The tests are written using the
"check" unit test framework. The Makefile in this directory builds the unit test
executable. Run "./romanNumLib_test" to execute the unit tests.

The root directory contain an app invoked with roman.exe. Running it with no parameters gives
its usage. It is simpley provided to illustrate library usage.

NOTES:

1) Initially tests were written around the addition operation. Once addition was complete,
the subtraction operations were implemented. Consequently, a large "jump" in functionality
was achieved by the simple operation of copying the addition function and swapping the
'+' with a '-'. Several subtraction tests were included to verify the robustness of this
approach, but no code changes were required.

