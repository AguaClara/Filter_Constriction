## Velocity through unit cell or constriction
### 3/1/2018

$$\Delta p = \rho g \Delta h $$
$$\Delta p = \frac{128L}{\pi} \frac{\mu Q}{D^4}$$
$$\Delta h = \frac{128L}{\rho g\pi} \frac{\mu Q}{D^4}$$

```python
from aide_design.play import *
import math as m
from scipy import constants
V_filter = 1.85*u.mm/u.s
A_filter = (0.5*u.mm)**2
Q_filter = V_filter*A_filter
Q_filter.to(u.ul/u.min)
Q_sand = 555*u.ul/u.min
L = 275*u.cm
(L*2.75).to(u.m)
3*L.to(u.m)
g = constants.g*u.m/(u.s)**2
rho = 1*u.g/(u.cm)**3
mu = 8.90*(10**(-4))*u.Pa *u.s
D =  0.042*u.inch
deltah = (128*L*mu*Q_sand)/(rho*g*m.pi*D**4)
deltah.to(u.cm)

```

$\Delta h = 0.36cm$
