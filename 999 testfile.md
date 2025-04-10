---
kernelspec:
  name: python3
  display_name: 'Python 3'
---

```{code-cell} python
import numpy as np
import matplotlib.pyplot as plt

x = np.linspace(0,10,5)
y = 2*x**2

plt.figure()
plt.plot(x,y,'k.')
plt.xlabel('x')
plt.ylabel('y')
plt.show()
```
