# 113.1_Algorithm_PA3Judge

## How to compile

```
gcc judge.c -o judge
```
Place your `judge` executable in your PA3 directory.

## How to use
Please `make` to create `./bin/cb/` before you run.

### Run test (public and random private testcase)
```
./judge -c <UUW/UW/DW/ALL>
```

### Run specific public testcase
```
./judge -t <0-8 except 5,6>
```

### Run random weighted directed graph testcase
```
./judge -s <seed>
```
