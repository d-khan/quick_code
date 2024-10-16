```python
from collections import OrderedDict
d = {"Harry":37.21,"Berry":37.21,"Tina":37.2}
d = OrderedDict(sorted(d.items()))
x = d.values()
x = list(x)
for k,v in d.items():
  if x[1] == v:
    print(k,v)
```
