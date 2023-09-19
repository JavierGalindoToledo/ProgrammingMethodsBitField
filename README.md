# Programming Methods 2: Bitfield Based Sets

[![Build Status](https://travis-ci.org/UNN-ITMM-Software/mp2-lab1-set.svg)][travis]
[![Gitter](https://badges.gitter.im/Join%20Chat.svg)][gitter]

<!-- TODO
  -
-->
## Goals and objectives

The purpose of this work is to develop a data structure for storing sets using bit fields,
as well as mastering such software development tools as the version control system [Git][git]
and the framework for developing automated tests [Google Test][gtest].

Performing the work involves solving the following tasks:

  1. Implementation of the `TBitField` bit field class according to the given interface.
  2. Implementation of the `TSet` set class according to the given interface.
  3. Ensuring the functionality of the tests and example of use.
  4. Implementation of several simple tests based on Google Test.
  5. Publish source codes in a personal repository on GitHub.

## Tools used

  - Version control system [Git][git].
  - Framework for writing automated tests [Google Test][gtest].
  - Microsoft Visual Studio development environment.
  - Utility [CMake](http://www.cmake.org).

## General project structure

  - `docs` — instructions for performing laboratory work, useful documents.
  - `gtest` — Google Test library.
  - `include` — directory for placing header files.
  - `samples` — directory for placing demo applications.
  - `src` — directory with source codes (cpp files).
  - `test` — directory with unit tests and the main application,
     initializing the launch of tests.
  - `README.md` — information about the project that you are currently reading.
  - `.gitignore` — list of file extensions ignored by Git when adding files to the repository.
  -  `CMakeLists.txt` — is the root file for building a project using CMake.Can be used to generate a project in a development environment other than Microsoft Visual Studio.
  - `travis.yml` — configuration file for the automatic
       testing Travis-CI. Tests included in the template project
       regularly run on remote [infrastructure][travis].


<!-- LINKS -->

[git]:         https://git-scm.com/book/ru/v2
[gtest]:       https://github.com/google/googletest
[sieve]:       http://habrahabr.ru/post/91112
[travis]:      https://travis-ci.org/UNN-ITMM-Software/mp2-lab1-set
[git-guide]:   https://github.com/UNN-ITMM-Software/mp2-lab1-set/blob/master/docs/part1-git.md
[gtest-guide]: https://github.com/UNN-ITMM-Software/mp2-lab1-set/blob/master/docs/part2-google-test.md
[youtube-playlist]: https://www.youtube.com/playlist?list=PLSzOhsr5tmhrgV7u7CSzX4Ki1a9r0AKzV
[slides]:      https://github.com/UNN-ITMM-Software/mp2-lab1-set/tree/master/docs/slides
[upstream]:    https://github.com/UNN-ITMM-Software/mp2-lab1-set
[gitter]:      https://gitter.im/UNN-ITMM-Software/mp2-lab1-set
