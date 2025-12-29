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

class Circle:
    def __init__(self, radius):
        self.radius = radius

    def area(self):
        return math.pi * (self.radius ** 2)
radius = float(input())

circle = Circle(radius)

print(f"Area of circle: {circle.area():.2f}")
```

Add code here

## Output
<img width="617" height="208" alt="image" src="https://github.com/user-attachments/assets/486a269a-995f-4d54-9065-f55a2b2a9212" />



## Result
Thus, the program has been successfully executed.
