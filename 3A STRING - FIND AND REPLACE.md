# Exp.No: 3a

## STRING - FIND AND REPLACE

---

### AIM

To write a Python function to accept a string, identify a word to be replaced, and replace it with a new word provided by the user.

---

### ALGORITHM

1. Begin the program.
2. Input the original string `str1` and the word to be replaced `replace_str`.
3. Ask the user to input the new replacement word `str2`.
4. Use the `replace()` method in Python to replace all occurrences of `replace_str` in `str1` with `str2`.
5. Store the modified string in `str3`.
6. Display the original string (`str1`) and the modified string (`str3`).
7. Terminate the program.

---

### PROGRAM

```python
#Reg.No: 212223060231
#Name: Royce Niran George A

str1 = input("Enter the original string: ")
replace_str = input("Enter the word to be replaced: ")
str2 = input("Enter the new word: ")

str3 = str1.replace(replace_str, str2)

print("\nOriginal String:", str1)
print("Modified String:", str3)
```

---

### OUTPUT

![image](https://github.com/user-attachments/assets/afaf88da-7694-48e5-b9ad-d343a00db3b8)

### RESULT

Hence, the Python program to find and replace a word in a string was written and executed successfully.
