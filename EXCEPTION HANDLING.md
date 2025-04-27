# Exp.No:17  
## EXCEPTION HANDLING
### AIM  
To create a Python program by uses exception handling to inform the user if the values cannot add to string.
### ALGORITHM
1. Begins the Program.
2. Define a string variable a = "Hello World!".
3. Try to add an integer (e.g., 10) to the string a.
4. If a TypeError occurs:
      Set msg = "You can't add int to string".
      Print the message msg.
5. Terminate the Program
### PROGRAM

```
a="Hello World!"
try:
    a + 10
except TypeError:
    msg="You can't add int to string"
print(msg)
```
### OUTPUT
![Screenshot 2025-04-27 212621](https://github.com/user-attachments/assets/08efffcc-5662-4c6a-b716-03943a839469)
### RESULT
Thus the python program by using exception handling has been executed successfully.
