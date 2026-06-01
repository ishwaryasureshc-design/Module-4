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
    def mech(self, r):
        area = math.pi * (r ** 2)
        print("Area of the circle:", area)

radius = float(input())
obj = cse()
obj.mech(radius)
```

## Output
<img width="1336" height="592" alt="Screenshot 2026-06-01 113012" src="https://github.com/user-attachments/assets/e922c85a-21f2-4fd8-9ad7-80e40cc65d71" />

## Result
The program takes the radius of a circle as input from the user, creates an object of class cse, and calls the method mech to calculate the area of the circle using the formula:
