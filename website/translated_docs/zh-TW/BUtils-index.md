---
id: BUtils-index
title: Overview
sidebar_label: Overview
---
Infrastructure of all Ball Chang's projects.

## Main Features

* Generate UUID (Based on random value).
* Cross-platform Timing system (Precision 1 us).
* Cross-platform Timer system (Minimum precision 1 ms).

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites

If you want to use BUtils in your platform, these requirements should be satisfied.

    C++ Standard: c++11
    Build tools: cmake make autoconf automake gcc
    

### Installation

    $ git clone https://gitlab.com/zhangbolily/BUtils.git BUtils
    $ cd BUtils
    $ git submodule update --init --recursive
    $ mkdir build
    $ cd build
    $ cmake ..
    $ make
    $ make install
    

##### Demonstration build video (click to veiw)

[![Build](https://asciinema.org/a/pxITpcCQsCXepW80eHSjB5byF.svg)](https://asciinema.org/a/pxITpcCQsCXepW80eHSjB5byF)

## Running the tests

    $ cd build
    $ rm -rf ./*
    $ cmake -DBUILD_TESTING=ON -DCODE_COVERAGE=ON -DCMAKE_BUILD_TYPE=Debug ..
    $ make tests
    $ bin/tests
    

## Versioning

For the versions available, see the [tags on this repository](https://gitlab.com/zhangbolily/BUtils/tags).

## Roadmap

* Performance improvement in the next version.
* More examples.
* Pass parameter into timer action.

## Authors

* **Ball Chang** - *Build the whole project*

## License

This project is licensed under the MIT License - see the <LICENSE.md> file for details

## Acknowledgments

* GitLab
* Travis-CI