

- #### floating point number

```python
3.5 - 3.12 == 0.38 # False

a= 3.5 - 3.12
b= 0.38
#1)
abs(a - b)<=1e-10
#2)
import sys
abs(a - b) <= sys.float_info.epsilon
#3)
import math
math.isclose(a, b)
```

