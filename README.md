# Python-Assigmemt-4 

1)Write a python to find area of circle using math function
a)import math
r=float(input('enter radius'))
area=math.pi*r*r
print('area of circle os %.2f'%area)
Output:
enter radius 3
area of circle is 28.27
2)Write a python program to find area of regular polygon
a) from math import tan,pi
s=int(input('enter the number of sides of polygon'))
l=float(input('enter the length'))
a=s*(l**2)/(4*tan(pi/s))
print('area of polygon is %.2f'%a)
Output:
enter the number of sides of polygon 4
enter the length 3
area of polygon is 9.00
3)Write a program to generate random numbers between 1 and 1000
a)import random
print(random.randint(1,1000))
Output:
417
4)Write a python program by using math module to find
● Sin 60
● cos(pi)
● Tan90
● 5^8
● Square root 400
● Floor and ceiling value of 3.56
a)import math
print('sin(60)',math.sin(60))
print('cos(pi)',math.cos(math.pi))
print('tan(90)',math.tan(90))
print('5^8',5^8)
print('square root 400',math.sqrt(400))
print('floor and ceiling value of 3.56 is',math.floor(3.56),math.ceil(3.56))
Output:
sin(60) -0.3048106211022167
cos(pi) -1.0
tan(90) -1.995200412208242
5^8 13
Square root 400 20.0
floor and ceiling value of 3.56 is 3 4
