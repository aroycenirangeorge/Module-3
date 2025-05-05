# Exp.No: 3d

## TUPLES - A TUPLE WITH MULTIPLES OF 5

---

### AIM

To write a Python program to create a tuple containing all multiples of 5 up to a given number **N**.

---

### ALGORITHM

1. Begin the program.
2. Accept an integer `N` from the user.
3. Use a generator expression inside the `tuple()` function to create a tuple `multiples_of_5` with values starting from `5` up to `N - 1`, stepping by `5`.
4. Return the tuple `multiples_of_5`.
5. Print the resulting tuple.
6. Terminate the program.

---

### PROGRAM

```python
#Reg.No: 212223060231
#Name: Royce Niran George A

N = int(input("Enter a number: "))

multiples_of_5 = tuple(i for i in range(5, N, 5))

print("Multiples of 5 up to", N, ":", multiples_of_5)
```

---

### OUTPUT

![image](https://github.com/user-attachments/assets/e1d3a457-020e-44e5-ad0d-000e8e78b025)

---

### RESULT

Thus, the program to create a tuple with multiples of 5 up to **N** was written and executed successfully.
