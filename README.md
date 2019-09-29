## Trial run the C code from CS50

```shell
clang hello.cpp -o hello.out
./hello.out
```

```shell
gcc hello.cpp -o hello.out
./hello.out
```

```shell
make hello
./hello
```

[makefile - What is the difference between make and gcc? - Stack Overflow](https://stackoverflow.com/questions/768373/what-is-the-difference-between-make-and-gcc)

## Install libcs50 for local run

https://github.com/cs50/libcs50

### Troubleshooting

    Mac make install error: No such file or directory #142
    https://github.com/cs50/libcs50/issues/142

    macOS Mojave compiling issue #158
    https://github.com/cs50/libcs50/issues/158

```sh
gcc -lcs50-9.0.0 hello.c -o hello.out
```

