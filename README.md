tpch-kit
========

TPC-H benchmark kit with some modifications/additions

Official TPC-H bechmark - [http://www.tpc.org/tpch](http://www.tpc.org/tpch)

## Modifications

The following modifications have been added on top of the official TPC-H kit:

* modify dbgen to not print trailing delimiter `1595284`
* add option for dbgen to output to stdout `fd512b4`
* add compile support for OS X `b623f4b`
* add define for PostgreSQL to support LIMIT N for qgen `6bcf4ef`
* adjust Makefile defaults `b78ed68`
