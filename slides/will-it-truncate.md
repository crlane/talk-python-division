##   Will It Truncate?

* Normal division depends on `type` of operands
* result matches `type` with greatest precision
* if two `int` operands, it truncates

```python
>>> 1/2 # truncating int division
0
>>> 1/2.0 # normal float division
0.5
```
