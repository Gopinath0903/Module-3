# Exp.No:3c
## LIST - SWAP THE VALUE

---

### AIM  
To write a python program to swap the value in the list with the next value if next value is divisible by 7.

---

### ALGORITHM


1. Read a list of numbers from the user.
2. Set `i = 0`.
3. Repeat while `i` is less than the second-last index of the list:
   - If the number at index `i` is divisible by 7:
     - Swap it with the number at index `i + 1`.
     - Increase `i` by 2.
   - Else:
     - Increase `i` by 1.
4. Print the updated list.



### PROGRAM
Reg no-212223070007
Name-Gopinath G

num = eval(input())
l=len(num)
i=0
while i<l:
    if num[i]%7==0:
        num[i],num[i+1]=num[i+1],num[i]
        i+=2
    else:
        i+=1
print(num)

### OUTPUT
![Screenshot 2025-04-30 225457](https://github.com/user-attachments/assets/6c1e83d0-5db1-4ea3-b094-36a28fa4ea63)


### RESULT
Thus the python program to swap the value in the list with the next value if next value is divisible by 7 was executed successfully
