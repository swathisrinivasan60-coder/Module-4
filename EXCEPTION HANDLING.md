# Exp.No:17  
## EXCEPTION HANDLING

---

### AIM  
To create a Python program that prompts the user for a list of grades separated by commas, splits the string into individual grades, and uses exception handling to inform the user if the values they entered cannot be converted to integers.

---

### ALGORITHM

1. Begin the program.  
2. Read a string `input_str` from the user using `input()`.  
3. Split the input string using commas (`,`) to create a list of grades.  
4. Use a `try` block to attempt converting each item in the grades list to an integer and store the result in `l1`.  
5. If the conversion is successful, print the list `l1` containing the integer values.  
6. If an error occurs during conversion (for example, if the input is not a valid number), catch the exception and print an error message: `"The grades you entered were in an invalid format."` along with the original grades list.  
7. Terminate the program.

---

### PROGRAM

```
Reg.No
Name
Add Your Code Here
def digit():
try:
a=int(input())
if(a%2==0):
print("You entered even number")
else:
print("An odd number")
except:
print("Enter only number")
digit()
```

### OUTPUT
<img width="647" height="204" alt="image" src="https://github.com/user-attachments/assets/58e3c075-3e31-45aa-9c67-526d1843037e" />

### RESULT
Thus,the program for the solution of value error in exception handling and check whether the number is even or odd was implemented and executed successfully.
