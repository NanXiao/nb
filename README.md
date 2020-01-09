# nb

nb, abbreviation for "Nan's Benchmark", is a shell script which can benchmark program's performance. By default, the program is executed `10` times:  

```
$ ./nb program
Average running time of 10 times:
real: 2.481 seconds
user: 1.999 seconds
sys: 0.486 seconds
```

The running times can be changed through `-c` option:  

```
$ ./nb -c 5 program
Average running time of 5 times:
real: 2.47 seconds
user: 1.998 seconds
sys: 0.476 seconds
```
