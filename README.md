# timestone_optimized_btree

This repository provide the header file of btree to which timestone is applied.

It is provided under the terms of Apache 2.0 License

## How to use

- fetch the Timestone from github and build
```
#> git clone https://github.com/cosmoss-vt/timestone
#> cd timestone
#/timestone> make
```
- Clone this repository in the '/unittest'
```
#/timestone> cd unittest
#/timestone/unittest> git clone <this repo> 
```
- Build and run
```
#/timestone> cd lib/
#/timestone/lib> CONF=gtest make
#/timestone/lib> cd ../unittest/
#/timestone/unittest> make
#/timestone/unittest> sudo ./ut-ts --gtest_filter=cpp.btree_concurrent
```
