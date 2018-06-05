## References for implementation
- https://github.com/wangxinalex/SimpleScalar.git
- https://github.com/sdenel/How-to-install-SimpleScalar-on-Ubuntu

## Objective of the project
The objective of this project is to understand five stage pipeline, with hazards
detection and handling, and implement the same using simple scalar.This
be enhanced 

## Purpose of the project
We are using this implementation for our graduate course project work.

## Use case
This implementation can be enhanced in future to show a graphical pipeline
view, and be used in University for educational purposes.

## Implementation details
We have aggregated implementations from the above cited sources, and tailored
it to fit our project requirements.

## Running the simulator:
- git submodule update --init simplescalar (Checkout simplescalar submodule)
- cd simplescalar/build/
- git submodule update --init sim-pipe (Checkout sim-pipe submodule)
- cd simplesim-3.0
- make (This will build simple scalar)
- cd ../../../test (Once simple scalar is build go the test directory)
- sslittle-na-sstrix-gcc -s test.s -o test -nostdlib (Build test code)
- ../simplescalar/build/simplesim-3.0/sim-pipe test

