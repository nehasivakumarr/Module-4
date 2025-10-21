# Classes and Objects in Python: Calculate the Area of a Circle

## 🎯 Aim
To write a Python program that calculates the **area of a circle** based on the radius provided by the user. This program uses a class named `cse` and a method `mech` to perform the calculation.

## 🧠 Algorithm
1. **Get user input**: Take the radius of the circle as input from the user.
2. **Define the class**: Create a class named `cse`.
3. **Define the method**: Inside the class, define the method `mech` to calculate the area of the circle using the formula:  
   Area = pi *r^2 
4. **Execute the program**: Create an object of the class and call the method with the radius value.

## 🧾 Program
```
import math
class cse:
    def mech(self,r):
        a=(math.pi*pow(r,2))
        print(f"Area of circle: {a:.2f}")
r=float(input())
n=cse()
n.mech(r)
```

## Output
<img width="606" height="185" alt="image" src="https://github.com/user-attachments/assets/d0230a53-2ffc-4b8b-998c-b061970869a0" />


## Result
Thus, the Python program that calculates the **area of a circle** based on the radius provided by the user. This program uses a class named `cse` and a method `mech` to perform the calculation has been executed successfully.
