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
```python
class Circle:

    def __init__(self, radius):
        self.radius = radius

    def area(self):
        return 3.14 * self.radius * self.radius


r = float(input("Enter radius: "))

c = Circle(r)

print("Area of Circle =", c.area())

```



## Output
<img width="266" height="70" alt="WhatsApp Image 2026-05-29 at 8 26 25 PM" src="https://github.com/user-attachments/assets/a3f345a7-5199-4b3a-bb2e-563fcc60b6e8" />

## Result
By using python the code was executed successfully.
