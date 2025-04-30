# Exp.No:3d  
## TUPLES - CONVERT IT INTO A TUPLE AND REMOVE

---

### AIM  
To write a python function that  a string, convert it into a tuple and remove the 3rd element of the tuple.

---

### ALGORITHM


1. Convert the input string `a` into a tuple `t`.
2. Print the original tuple `t`.
3. Convert the tuple `t` into a list `l`.
4. Remove the character at index 2 from the list and store it in `r`.
5. Convert the modified list `l` back into a tuple `t1`.
6. Print the new tuple `t1`.
7. Print the removed character `r`.


### PROGRAM
Reg no-212223070007
Name-Gopinath G

def strtotuple(a):
    t=tuple(a)
    print(t)
    l=list(t)
    r=l.pop(2)
    t1=tuple(l)
    print(t1)
    print("Character Removed:",r)

### OUTPUT

![image](https://github.com/user-attachments/assets/3715aedf-2847-4535-9add-5f92d2ca89bf)


### RESULT
Thus the python function that  a string, convert it into a tuple and remove the 3rd element of the tuple was executed successfully
