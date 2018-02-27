### User Specific Compiler in ` make ` command
```sh
CC=/usr/bin/gcc-7 ./configure
make CC=/usr/bin/gcc-7
```
### Faster Build
* Test PC Core
```sh
nproc
```
* Start Parallel Build
```sh
make -j8
```
* -j8 means Job 8 for 8 core
