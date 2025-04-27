# Exp.No:19  
## CLASS AND OBJECTS - AREA OF CIRCLE
### AIM  
To write a Python program to take the radius from the user and find the area of a circle using the class name `pen` and function name `stationary`.
### ALGORITHM
1. Begins the program.
2. Define a class named pen.
3. Inside the class, define the constructor _init_(self, a):
        Store the given radius a into self.a.
4. Define another function dis(self) inside the class:
Calculate the area of the circle using the formula:
       Area = 3.141592 × radius × radius.
       Print the area rounded to 2 decimal places.
5. Take input from the user for the radius and convert it to an integer.
6. Create an object of the class pen using the input radius.
7. Call the dis() function using the created object to display the area.
8. Terminate the program.
### PROGRAM
```
class pen:
    def _init_(self, a):
        self.a = a

    def stationary(self):
        print("Area of circle: {:.2f}".format(3.141592 * self.a * self.a))

# Take radius input from user
a = int(input())

# Create an object of class 'pen'
obj = pen(a)

# Call the function 'stationary' to display the area
obj.stationary()

```

### OUTPUT
![Screenshot 2025-04-27 210544](https://github.com/user-attachments/assets/a5aa00ca-face-487f-bd5e-2ce91731d04e)

### RESULT
Thus the python program for finding the area of the circle has been implemented and executed successfully.



