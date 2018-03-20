```python
from aide_design.play import *
h = [260,280,300,320]*u.cm
Q = [4.19,3.10,1.86,0.781]*u.mL / u.min

plt.scatter(h,Q)
plt.xlabel('Height of outflow tubing apex (cm)')
plt.ylabel('Flow rate through cell (mL/min)')
plt.title('Flow rate through flow cell vs. height of outflow tubing apex')
plt.minorticks_on()
plt.tight_layout()
plt.savefig('FlowRatePlot.png')
plt.show()
```
