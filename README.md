# tomorrow-docker

[![](http://www.wtfpl.net/wp-content/uploads/2012/12/wtfpl-badge-2.png)](http://www.wtfpl.net/)
[![](https://img.shields.io/docker/stars/mrkloan/tomorrow.svg)](https://hub.docker.com/r/mrkloan/tomorrow/)
[![](https://img.shields.io/docker/pulls/mrkloan/tomorrow.svg)](https://hub.docker.com/r/mrkloan/tomorrow/)
[![](https://img.shields.io/docker/automated/mrkloan/tomorrow.svg)](https://hub.docker.com/r/mrkloan/tomorrow/builds/)
[![](https://img.shields.io/docker/build/mrkloan/tomorrow.svg)](https://hub.docker.com/r/mrkloan/tomorrow/builds/)

Docker image containing all the required libraries and runtime dependencies for the `Tomorrow` project.

## How to

```bash 
$ docker pull mrkloan/tomorrow
$ docker run --name tomorrow -v .:/src -it mrkloan/tomorrow bash
```

## Features

High-level features:

* [Rust](https://www.rust-lang.org/): Nightly toolchain (including `rustup` and `cargo`);
* [kcov](https://github.com/SimonKagstrom/kcov): Code coverage tool for compiler programs;
* [Bazel](https://bazel.build/): A multi-language build system;
* [TensorFlow](https://www.tensorflow.org/): Open-source Machine Learning library.

Low-level dependencies:

* git
* python
* python3
* gcc, g++, make, pkg-config
* curl, wget
* OpenSSL
* OpenJDK 8