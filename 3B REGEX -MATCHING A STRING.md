# Exp.No:3b  
## REGEX - MATCHING A STRING USING REGEX

---

### AIM  
To write a Python program that matches a string containing an `'a'` followed by **two to three `'b'` characters** using regular expressions.

---

### ALGORITHM

1. Begin the program.  
2. Accept a string `str1` from the user.  
3. Define the regular expression pattern as `r"[a]+b{2,3}"`.  
4. Use the `re.match()` function to check if the string `str1` matches the pattern.  
5. If a match is found, print `"Found a match!"`.  
6. If no match is found, print `"Not matched!"`.  
7. Terminate the program.

---

### PROGRAM

import re

s=input()

p=re.compile(r'^a*b*$')

if p.match(s):

print("Found a match!")

else:

print("Not matched!")

### OUTPUT
![image](https://github.com/user-attachments/assets/10ee7117-0a7c-4253-a928-38feca96f280)

### RESULT
Thus the code for matching a string is executed successfully
