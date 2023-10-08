# matplotlib3.py
#Draw a line in a diagram from position (0,0) to position (6,250):
import numpy as np
import matplotlib.pyplot as plt
xpoints=np.array([0,6])
ypoints=np.array([6,250])

plt.plot(xpoints,ypoints)
plt.title("power")

plt.xlabel("X rajesh")
plt.ylabel("Y surya")
plt.show()
