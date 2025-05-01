# Exp.No:3e
## SEB - FIND SEQUENCES

---

### AIM  
To write a Python program to find sequences of lowercase letters joined with a underscore.

---

### ALGORITHM


1. Read a string from the user.
2. Define a pattern that:
   - Starts with one or more lowercase letters
   - Followed by an underscore (`_`)
3. Use the pattern to search the string.
4. If the pattern is found at the beginning:
   - Print `"Found a match!"`
5. Else:
   - Print `"Not matched!"`


### PROGRAM
Reg no-212223070007
Name-Gopinath G
~~~
import re
s=input()
x=re.search(r'^[a-z]+_',s)
if x:
    print("Found a match!")
else:
    print("Not matched!")
~~~
### OUTPUT
![image](https://github.com/user-attachments/assets/1bdc9b30-08d5-4b0f-9d40-b5ad6b297a47)


### RESULT
Thus the Python program to find sequences of lowercase letters joined with a underscore was executed successfully
