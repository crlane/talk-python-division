##  Pathological Examples

```python
>>> -1/2
-1
>>> 1/-2
-1
>>> divmod(-1,2)
(-1, 1)
>>> divmod(1,-2)
(-1, -1)
>>> def satisfies_math(a,b):
        q,r = divmod(a,b)
        assert a == q * b + r
>>> satisfies_math(-1, 2)
>>> satisfies_math(1, -2)
>>> satisfies_math(-1, -2)
```
