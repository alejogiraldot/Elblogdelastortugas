import numpy as np
import matplotlib.pyplot as plt

def sigmoid(a):
    return 1/(1+np.exp(-a))


x=np.linspace(-10,10,100)

plt.plot(x,sigmoid(x))
plt.show()