# Exp.No:3b  
## REGEX - PATTERN MATCHING USING REGEX

---

### AIM  
To write a Write a Python program that matches a string that has an 'a' followed by anything, ending in 'b'.
---

### ALGORITHM

1. Read a string from the user.
2. Define a pattern that:
   - Starts with `'a'`
   - Has any number of characters in between
   - Ends with `'b'`
3. Use the pattern to check if the string matches.
4. If it matches:
   - Print `"Found a match!"`
5. Else:
   - Print `"Not matched!"`

### PROGRAM
---

Reg no-212223070007
Name-Gopinath G

import re
pat=r'a.*b$'
if(re.search(pat,input())):
    print("Found a match!")
else:
    print("Not matched!")
    
---

### OUTPUT

![Screenshot 2025-04-30 224746](https://github.com/user-attachments/assets/0b23565e-2668-4331-a8f3-8cc0be338e68)


### RESULT
Thus the Python program that matches a string that has an 'a' followed by anything, ending in 'b was executed successfully
