##  Forcing It

```python
>>> float(1)/2 # force float division by "casting" one operand
0.5
>>> from __future__ import division
>>> 1/2 # now does float division
0.5
>>> 1//2 # forces truncating division
0
>>> 1.0//2.0 # even with floats!
0.0
```
