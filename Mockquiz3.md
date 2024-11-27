Here are the questions based on your updated requirements:

---

### Question 1: Decimal to Hexadecimal Conversion
**Instructions**: Convert the given decimal number into hexadecimal. 

**Decimal Number**: 254

Write the Python code to convert this decimal number to hexadecimal and explain the result.

```python
number = 254
# Convert number to hexadecimal
hexadecimal = hex(number)

print("Hexadecimal:", hexadecimal)
```

---

### Question 2: Code with String Slices and Nested Loops (Output)
**Instructions**: Given the following Python code, write the output.

```python
text = "PythonProgramming"
for i in range(0, len(text), 3):
    print(text[i:i+3])

for i in range(len(text)-1, -1, -3):
    print(text[i-2:i+1])
```

**Expected Output**:
Explain how the string slices work and how the two `for` loops are interacting to produce the output.

---

### Question 3: Python Code with Dictionary and Logic (Find the Output)
**Instructions**: Given the following Python code, write the output. The program uses a dictionary and basic logic.

```python
students_scores = {
    "Alice": 85,
    "Bob": 92,
    "Charlie": 78
}

# Add a score for a new student
students_scores["David"] = 88

# Update Bob's score to 95
students_scores["Bob"] = 95

# Calculate the average score
average_score = sum(students_scores.values()) / len(students_scores)

# Print average score
print(f"Average score: {average_score:.2f}")

# Print updated dictionary
print(students_scores)
```

What will be the output of the code? Explain how the dictionary is updated and how the average score is calculated.

---

### Question 4: Partial Binary Search Code (Complete the Code)
**Instructions**: Complete the following binary search code. Fill in the missing parts to complete the binary search algorithm.

```python
def binary_search(arr, target):
    low = 0
    high = len(arr) - 1
    while low <= high:
        mid = (low + high) // 2
        # Complete the condition to check if the mid element is the target
        if arr[mid] == target:
            return mid
        # Modify the else-if conditions to correctly narrow down the search
        elif arr[mid] < target:
            low = mid + 1
        else:
            high = mid - 1
    return -1

arr = [10, 20, 30, 40, 50, 60, 70, 80, 90]
target = 40
result = binary_search(arr, target)
print(f"Target found at index: {result}")
```

What will the program output? Explain the binary search steps.

---

### Question 5: String Formatting
**Instructions**: Write Python code using string formatting techniques for the following scenarios.

1. **Format a float to 2 decimal places:**

```python
price = 123.456
print(f"Price: {price:.2f}")
```

**What will be the output?**

---

