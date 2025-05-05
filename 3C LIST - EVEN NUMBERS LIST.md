# Exp.No: 3c

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

   * For each number `i`, check if it is even using `i % 2 == 0`.
   * If it is even, append `i` to the list `l`.
5. Print the final list `l` containing all the even numbers.
6. Terminate the program.

---

### PROGRAM

```python
#Reg.No: 212223060231
#Name: Royce Niran George A

a = int(input("Enter a number: "))
l = []

for i in range(1, a):
    if i % 2 == 0:
        l.append(i)

print("Even numbers list:", l)
```

---

### OUTPUT

![image](https://github.com/user-attachments/assets/a94ca31f-e3e2-4dbd-83ef-c9dff1674175)

---

### RESULT

Hence, the Python program to create a list of even numbers up to **N** was written and executed successfully.

