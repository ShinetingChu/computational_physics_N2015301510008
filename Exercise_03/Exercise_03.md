```
import numpy as np
import matplotlib.pyplot as pl

#The initial values
u=[0]
a=10
b=1
t=[0]
dt=0.05

for i in range (1,int(10/dt)):
    u.append(u[i-1]+(a-b*u[i-1])*dt)
    t.append(t[i-1]+dt)
    
pl.plot(t,u)
pl.xlim(0,11)
pl.ylim(0,11)
pl.show()
```
