# Data Types

## Meghan Wolfarth

## Program Output

### What is the output from running the following commands?

Use a fenced code block to provide the output for this command.

- `python demonstrate-variable-limitations.py`
```
The value of a feasible number is 115792089237316195423570985008687907853269984665640564039457584007913129639936

The value of another feasible number is 179769313486231590772930519078902473361797697894230657273430081157732675805500963132708477322407536021120113879871393357658789768814416622492847430639474124377767893424865485276302219601246094119453082952085005768838150682342462881473913110540827237163350510684586298239947245938479716304835356329624224137216
```

Use a fenced code block to provide the output for this command.

- `python compare-variables.py`
```
1.0 is not the same as 1.1
1.0 is the same as 1.0
.33333 + .33333 + .33333 is not equal to 1
.33333333333 + .33333333333 + .3333333333 is not equal to 1
The value of 1/3 is 0.3333333333333333
0.3333333333333333 + 0.3333333333333333 + 0.3333333333333333 is equal to 1
1/3 + 1/3 + 1/3 is equal 1
```

## Program Questions

### Why is it not feasible to perform the computation `2**2**100`?

The number is too large for the program to calculate, so it is unable to provide an answer. The program is able to calculate `2**2**10` because that number is quite a bit smaller than `2**2**100`.

### What is the value of `1/3` according to the Python language? Why?

The value of 1/3 is 0.3333333333333333. Python divides 1 by 3 and gets a repeating decimal, which it stops after a certain point because it cannot get a perfectly accurate answer. The answer that Python gives is accurate enough that Python can say that it is equal to 1/3.

### Why is the value of `.33333 + .33333 + .33333 == 1` equal to `False`?

The value is false because Python does not think that the resulting value is close enough to 1 for it to be considered equal to 1. If you use the same answer that Python gives for 1/3 and add it 3 times, Python says True because it believes that answer is close enough to 1 to be considered equal to 1. 
