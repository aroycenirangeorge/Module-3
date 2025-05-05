# Exp.No: 3b

## REGEX - PATTERN MATCHING USING REGEX

---

### AIM

To write a Python program that matches a string containing an `'a'` followed by **two to three `'b'` characters** using regular expressions.

---

### ALGORITHM

1. Begin the program.
2. Accept a string `str1` from the user.
3. Define the regular expression pattern as `r"ab{2,3}"`.
4. Use the `re.match()` function to check if the string `str1` matches the pattern.
5. If a match is found, print `"Found a match!"`.
6. If no match is found, print `"Not matched!"`.
7. Terminate the program.

---

### PROGRAM

```python
#Reg.No: 212223060231
#Name: Royce Niran George A

import re

str1 = input("Enter a string: ")

pattern = r"ab{2,3}"

if re.match(pattern, str1):
    print("Found a match!")
else:
    print("Not matched!")
```

---

### OUTPUT

![image](https://github.com/user-attachments/assets/6ef28209-1df1-447c-92de-1ff6a527ffed)


---

### RESULT

Thus, the program using regular expressions to match a pattern of `'a'` followed by two to three `'b'` characters was written and executed successfully.
