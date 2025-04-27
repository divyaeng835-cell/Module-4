# Exp.No:20  
## SEB - ARITHMETIC CALCULATION USING CLASS

---

### AIM  
To write a Python program to perform addition and division operations using a class. The class should be named `calc`, and the function names should be `setvalues` (to set `a` and `b` values), `add`, and `mul`. The program should handle the following cases:  
- `choice 1` → Perform addition  
- `choice 2` → Perform multiplication  
- `choice 0` → Exit  
- For other choices, print 'Invalid choice'

---

### ALGORITHM

1. Begin the program.  
2. Create a class `calc`.  
3. Define the following methods inside the `calc` class:  
   - `__init__(self)`: Initializes `a` and `b` to zero.  
   - `setvalues(self, a, b)`: Sets the values of `a` and `b`.  
   - `add(self)`: Performs the addition operation.  
   - `mul(self)`: Performs the multiplication operation. If `b` is zero, returns an error message for multiplication by zero.  
4. Create a `main()` function.  
5. Take input from the user for the values of `a` and `b` using `setvalues(a, b)` method.  
6. Use a `while True` loop to repeatedly ask the user for a choice:  
   - If the choice is 1, call the `obj.add()` method and print the result.  
   - If the choice is 2, call the `obj.mul()` method and print the result. Handle multiplication by zero.  
   - If the choice is 0, print "Exiting!" and exit the loop.  
   - If the choice is not 1, 2, or 0, print "Invalid choice".  
7. Terminate the program.

---

### PROGRAM

```
class calc:
    def _init_(self,a,b):
        self.a=a
        self.b=b
    def add(self):
        return self.a+self.b
    def mul(self):
        return self.a*self.b
a=int(input())
b=int(input())
obj=calc(a,b)
obj.add()
obj.mul()
choice=1
while choice!=0:
    choice=int(input())
    if choice==1:
        print("Result: ",obj.add())
    elif choice==2:
        print("Result: ",obj.mul())
    elif choice==0:
        print("Exiting!")
    else:
        print("Invalid choice")
print()


```

### OUTPUT
![Screenshot 2025-04-27 213730](https://github.com/user-attachments/assets/d508486c-c741-4ced-b728-c5c8ba8c329f)
### RESULT
Thus the python program to perform addition and division operations using a class has been implemented and executed completely
