# C++ Boilerplate
[![Build Status](https://travis-ci.org/dpiet/cpp-boilerplate.svg?branch=master)](https://travis-ci.org/dpiet/cpp-boilerplate)
[![Coverage Status](https://coveralls.io/repos/github/dpiet/cpp-boilerplate/badge.svg?branch=master)](https://coveralls.io/github/dpiet/cpp-boilerplate?branch=master)
---

## Overview

Simple starter C++ project with:

- cmake
- googletest

Added valgrind outputs to the /results directory as well as callgrind output. 

## Installation

- Checkout the repo (and submodules)
```
$ git clone --recursive https://github.com/dpiet/cpp-boilerplate-valgrind.git
```
Create a build directory, run cmake, and make the project:
```
$ cd cpp-boilerplate-valgrind
$ mkdir build
$ cd build
$ cmake ..
$ make
```

## Run
To run the application, change directories back into the build directory and run the app:
```
$ cd cpp-boilerplate-valgrind/build
$ ./app/shell-app
```
To run the tests, from the build directory:
```
$ ./test/cpp-test
```
