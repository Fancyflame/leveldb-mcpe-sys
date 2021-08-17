# leveldb-mcpe-sys

Lowlevel bindings to the leveldb C library with zlib supported.

## Dependencies

* Your platforms C++ compiler (usually `gcc` or `clang` on Linux and Unix, Visual Studio Build environment on Windows)
* `cmake`

## Usage

If your project is using Cargo, drop the following lines in your Cargo.toml:

```
[dependencies]

leveldb-mcpe-sys = "*"
```

## Features

`levelbd-mcpe-sys` offers a `snappy` feature to build the snappy library.

## LICENSE

MIT

## BSD support

To build leveldb-mcpe-sys you need to install `gmake` (GNU Make)

## Annotation

This repository is forked from [skade/leveldb-sys](https://github.com/skade/leveldb-sys), and
*leveldb* was replaced by [pmmp/leveldb](https://github.com/pmmp/leveldb)
