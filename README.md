# Welcome to the Nonlinear Estimation Toolbox

## Installation

To install the Nonlinear Estimation Toolbox, recursively add the Matlab/Toolbox folder to your MATLAB Path.

## Documentation

For more information, see the [documentation](https://nonlinearestimation.bitbucket.io).

## Changes in this fork

Eigen is updated to version 3.3.7

the compileMex function has the added option of adding a debug flag to the compiler. Usage: compileMex("file.cpp", bool debug) where debug being true compiles with the debug flag -g, and it being false compiles without it.
