# Exp.No: 3e

## SEB - STRING SLICING

---

### AIM

To write a Python function that accepts a string and forms a new string by reversing the characters from the **4th position to the 10th position** with **alternate characters**, and then prints the new string.

---

### ALGORITHM

1. Begin the program.
2. Accept a string as input.
3. Take a slice of the input string from index **2** to **10**.
4. Reverse the sliced substring.
5. Extract every second character from the reversed substring using slicing (`[::2]`).
6. Print the final processed string.
7. Terminate the program.

---

### PROGRAM

```python
#Reg.No: 212223060231
#Name: Royce Niran George A

input_str = input("Enter a string: ")
processed_str = input_str[2:10][::-1][::2]
print("Processed string:", processed_str)
```

---

### OUTPUT

![image](https://github.com/user-attachments/assets/884d0f07-fc75-427c-891b-48bbd35635cd)

---

### RESULT

Thus, the program that slices, reverses, and extracts alternate characters from a string was successfully written and executed.
