# College-lab
from math import sqrt
import numpy as np
import matpotlib.pyplot as plt
a=int(input('enter a: '))
b=int(input('enter b: '))
c=int(input('enter c: '))
d=(b**2)-(4*a*c)
if d<0:
  print('roots are imaginary')
elif d==0:
  root1=(-b+sqrt(d))/(2*a)
  print('the one real root is',root1)
else:
  root1=(-b+sqrt(d))/(2*a)
  root2=(-b-sqrt(d))/(2*a)
  print('the two distinct real roots are ',root1,root2)
x=np.linspace(-3,10,400)
y=a*x**2+b*x+c
#plotting
plt.plot(x,y,label='quadratic equation')
plt.xlabel('x')
plt.ylabel('y')
plt.title('quadratic equation')
plt.legend()
plt.scatter([root1,root2],[0,0]color='red',label='roots')
plt.grid(True)
plt.show()
