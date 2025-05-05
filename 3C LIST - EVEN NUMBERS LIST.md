# Exp.No:3c
## LIST - EVEN NUMBERS LIST

---

### AIM  
To write a Python function that accepts a number **N** and creates a list containing all even numbers up to **N**.

---

### ALGORITHM

1. Begin the program.  
2. Accept an integer `a` from the user.  
3. Create an empty list `l`.  
4. Use a `for` loop to iterate through numbers from `1` to `a - 1`:  
   - For each number `i`, check if it is even using `i % 2 == 0`.  
   - If it is even, append `i` to the list `l`.  
5. Print the final list `l` containing all the even numbers.  
6. Terminate the program.

---

### PROGRAM

def createlist(n):
    l=[]
    for i in range(12,n):
        if i%2==0:
            l.append(i)
    print("List =",l)
    c=sum(l)
    print("Sum of the list",c)

### OUTPUT
![image](https://github.com/user-attachments/assets/91284079-749c-437b-babe-3bbde5cb9d63)

### RESULT
Thus the output was verified
