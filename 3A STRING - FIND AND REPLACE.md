# Exp.No:3a
## STRING -CONVERT

---

### AIM  
To write a  python function "convert" to accept a string and converts the uppercase character into lowercase character, lowercase character into uppercase  character and also replace the numbers with "*" using if..elif statements.
---

### ALGORITHM


1. Start with an empty string `b`.
2. For each character `i` in the string `a`:
   - If `i` is an uppercase letter, add its lowercase form to `b`.
   - Else if `i` is a lowercase letter, add its uppercase form to `b`.
   - Else, add `*` to `b`.
3. Print or return the new string `b`.


### PROGRAM
```
Reg  no-212223070007
Name-Gopinath G

def convert(a):
    b=""
    for i in a:
        if i.isupper():
            b+=i.lower()
        elif i.islower():
            b+=i.upper()
        elif i.islower()==False or i.isupper()==False:
            b+="*"
    print(b)

```

### OUTPUT
![Screenshot 2025-04-30 224014](https://github.com/user-attachments/assets/25203fb8-3fad-44c0-a2b4-26008966e212)


### RESULT
Thus the python function "convert" to accept a string and converts the uppercase character into lowercase character, lowercase character into uppercase  character and also replace the numbers with "*" using if..elif statements was executed successfully
