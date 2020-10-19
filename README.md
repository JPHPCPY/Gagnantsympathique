# Gagnantsympathique
import matplotlib.pyplot as plt
V=[0,1,2,3,4,5,6,7,8,9,10,11,12,13,13.25,13.50,13.75,14,14.25,14.50,15,16,17,18,19,20]
pH=[2.7,3.1,3.4,3.6,3.7,3.9,4.0,4.1,4.2,4.4,4.5,4.7,4.9,5.2,5.3,5.5,5.8,7.8,9.6,10,10.4,10.6,10.9,11,11.2,11.3]

plt.scatter(V,pH)
plt.plot(V,pH,"rx-",label="pH")
plt.xlabel("V (mL)")
plt.ylabel("pH")
plt.legend()
plt.title("pH=f(V)")
plt.grid()
plt.show()
