# Description
PoC minimalistic docker container build from scratch

# Compile binary
Compile binary in static mode

```shell
gcc -static -o hello hello.c
```

# Build image

```shell
 docker build -t hello .
```

# Run container

```shell
 docker run hello
```