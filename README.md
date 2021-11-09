# timestone_optimized_btree

This repository provide the algorithm of btree to which timestone is applied.

It is provided under the terms of Apache 2.0 License

## How to use

- fetch the Timestone from github and build
```
#> git clone https://github.com/cosmoss-vt/timestone
#> cd timestone
#/timestone> make
```
- Clone this repository and check the btree header file; 'btree.hpp'
```
#> git clone <this repo> 
```
- Put the header file in your application, and include it before using it with timestone.
```
#include "btree.hpp"
#include "timestone.h"
```

- You can handle Btree structure through following APIs
```
create_node()
create_leaf()
get_leaf()
insert()
insert_into_leaf()
split_insert_leaf()
insert_into_parent()
split_insert_into_node()
get_left_index()
insert_into_new_root()
lookup()
```
