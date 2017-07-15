# Lab :: Hello World :: Kotlin Native Application

[![License](https://img.shields.io/github/license/odaceo/lab-hello-world-kotlin-native.svg)](LICENSE)
[![Build Status](https://travis-ci.org/odaceo/lab-hello-world-kotlin-native.svg)](https://travis-ci.org/odaceo/lab-hello-world-kotlin-native)

## Description

A simple Kotlin Native application on Linux.

## Prerequisites

[Vagrant](https://www.vagrantup.com/downloads.html) must be installed on your 
computer to mount the workbench for this project.

Open a Terminal and run the following commands:

```shell
vagrant up
vagrant ssh
cd /vagrant
```

## Compiling the application

The compile command makes a dynamically linked executable.

``` shell
gradle build
```

## Running the application

To launch the application use the following command:

``` shell
./build/konan/bin/HelloWorldLinux.kexe Odaceo
```

## Reporting Issues

Issues can be reported at [https://github.com/odaceo/lab-hello-world-kotlin-native/issues](https://github.com/odaceo/lab-hello-world-kotlin-native/issues)

## Source code

The source code is available at [https://github.com/odaceo/lab-hello-world-kotlin-native](https://github.com/odaceo/lab-hello-world-kotlin-native)

## License

All the source code is distributed under [ASL 2.0](LICENSE).

## Copyright

© 2017 [Odaceo](http://odaceo.ch). All rights reserved.
