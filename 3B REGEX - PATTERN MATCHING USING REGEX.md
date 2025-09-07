# Exp.No:3b  
## REGEX - PATTERN MATCHING USING REGEX

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
```
s=input()
state=True
for word in s[1:]:
    if word!='b':
        state=False
        break
if s[0]=='a' and (state==True or s[1]=='\0'):
    print("Found a match!")
else:
    print("Not matched!")
```
### OUTPUT

<img width="830" height="372" alt="image" src="https://github.com/user-attachments/assets/022e919c-8bb7-4169-afab-e307f324eba9" />

### RESULT

Thus, the python code is written and executed successfully.
