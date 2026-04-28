## collect analyzer dataset

```
collect uvlog2 -sv test.sv -debug all                    # use collect tool
valgrind --leak-check=full  ./uvsim >& memLeak.log    # use valgrind tool
valgrind --tool=massif  ./uvsim >& memMalloc.log   # use valgrind tool
```


## open GUI

```
analyzer test.1.er    # open collect tool result
```