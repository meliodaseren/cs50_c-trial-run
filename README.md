## Trial run the C code from CS50

1. Use `clang`
```shell
clang hello.cpp -o hello.out
./hello.out
```

2. Use `gcc`
```shell
gcc hello.cpp -o hello.out
./hello.out
```

3. Use `make`
```shell
make hello
./hello
```

[makefile - What is the difference between make and gcc? - Stack Overflow](https://stackoverflow.com/questions/768373/what-is-the-difference-between-make-and-gcc)

## Install libcs50 for local run

https://github.com/cs50/libcs50

### Troubleshooting

1. [Mac make install error: No such file or directory #142](https://github.com/cs50/libcs50/issues/142)

2. [macOS Mojave compiling issue #158](https://github.com/cs50/libcs50/issues/158)

```shell
gcc -lcs50-9.0.0 hello.c -o hello.out
./hello.out
```

