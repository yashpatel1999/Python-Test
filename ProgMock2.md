
## PART-A
---

**1**: Which of the following binary representations equals the decimal number **45** when interpreted as an unsigned binary number?  

**A)** `101101`  
**B)** `101110`  
**C)** `100111`  
**D)** `111000`  


**2**  
Which of the following represents the correct order of the memory hierarchy, arranged from the fastest to the slowest in terms of access speed?  

**Options:**  
A) Registers, Cache, Main Memory, Secondary Storage  
B) Main Memory, Cache, Registers, Secondary Storage  
C) Cache, Registers, Secondary Storage, Main Memory  
D) Secondary Storage, Main Memory, Cache, Registers  


**3**  
Which of the following is **NOT** a part of the Central Processing Unit (CPU)?  

**Options:**  
A) Arithmetic Logic Unit (ALU)  
B) Control Unit (CU)  
C) Registers  
D) Graphics Processing Unit (GPU)  

Let’s take it up a notch! Here's a trickier version with a mix of formatting concepts:

---

**4**  
What will be the output of the following Python code snippet?  

```python
value = 42.678
negative_value = -123.456
formatted_string = f"{value:08.1f} | {negative_value:=+010.2f} | {value:.3e}"
print(formatted_string)
```

**Options:**  
A) `000042.7 | -00123.46 | 4.268e+01`  
B) `000042.7 | -000123.46 | 4.268e+01`  
C) `000042.7 | +00123.46 | 42.678e+00`  
D) `0042.68 | -00123.456 | 4.268e+01`  

---

**5**  
What will be the output of the following code snippet?


```python
my_list = [1, 2, 3, 4, 5, 6, 7, 8]
print(my_list[::2][::-2][1:4][::-1])
```

**Options:**  
A) `[3]`  
B) `[7, 5, 3]`  
C) `[7, 3]`  
D) `[8, 6, 4]`  


**6:**  
Given the following list, what will be the output?

```python
my_list = [1, 2, 3, 4, 5, 6, 7, 8]
print(my_list[-1:-(len(my_list)+1):-2])
```

**Options:**  
A) `[8, 6, 4, 2]`  
B) `[8, 6, 4, 3]`  
C) `[7, 5, 3, 1]`  
D) `[8, 6, 4, 3, 2]`  

### **7**  
Which of the following statements is **incorrect** about how Python handles code execution in relation to **Abstraction**, **Iteration**, **Alternation**, **Compiler**, and **Interpreter**?

**Options:**  
A) Python’s use of **iteration** in loops is not directly influenced by the **interpreter** but rather by the structure of the code itself.  
B) **Abstraction** is a concept that hides the internal workings of classes and functions, allowing Python to interpret code without revealing implementation details.  
C) The **compiler** compiles Python code into machine code before execution, allowing direct execution of the code without the need for an interpreter.  
D) **Alternation** in Python is handled through constructs like `if`, `else`, and `elif`, and it helps control the flow of execution based on conditions.

### **8**
What will be the output of the following code?

```python
my_list = [1, 2, 3, 4, 5]
my_list = [x * 2 if x % 2 == 0 else x for x in my_list]
my_list[2:4] = [7, 8, 9]
my_list.append(sum(my_list))
print(my_list)
```

**Options:**  
A) `[1, 4, 7, 8, 9, 5, 34]`  
B) `[1, 4, 7, 8, 9, 5, 32]`  
C) `[1, 4, 7, 8, 9, 5, 35]`  
D) `[1, 4, 7, 8, 9, 5, 31]`


### **9**
What will be the output of the following code?

```python
my_dict = {'a': 5, 'b': 10, 'c': 15}
my_dict['a'], my_dict['b'], my_dict['c'] = my_dict['b'], my_dict['c'], my_dict['a'] + my_dict['b']
my_dict['d'] = my_dict['a'] * 2
del my_dict['b']
print(my_dict)
```

**Options:**  
A) `{'a': 10, 'c': 15, 'd': 30}`  
B) `{'a': 10, 'c': 25, 'd': 20}`  
C) `{'a': 10, 'c': 25, 'd': 20, 'b': 10}`  
D) `{'a': 10, 'c': 25, 'd': 20, 'b': 5}`  

### **10**
What will be the output of the following code?

```python
my_list = [1, 2, 3, 4, 5]
my_list[::2] = [9, 8, 7]
my_list[1:4] = [10, 11, 12]
my_list.remove(11)
print(my_list)
```

**Options:**  
A) `[9, 10, 11, 12, 5]`  
B) `[9, 10, 12, 12, 5]`  
C) `[9, 8, 10, 11, 12, 5]`  
D) `[9, 10, 12, 12, 5]`



### **11**
What will be the output of the following code?

```python
my_dict = {'a': 3, 'b': 7, 'c': 5}
for key in my_dict:
    my_dict[key] = my_dict[key] + 2 if key != 'b' else my_dict[key] * 2
my_dict['d'] = my_dict['c'] + my_dict['a']
del my_dict['a']
print(my_dict)
```

**Options:**  
A) `{'b': 14, 'c': 7, 'd': 10}`  
B) `{'b': 14, 'c': 7, 'd': 13}`  
C) `{'b': 14, 'c': 5, 'd': 10}`  
D) `{'b': 14, 'c': 7, 'd': 9}`  



### **12**
What will be the output of the following code?

```python
my_list = [5, 10, 15, 20, 25]
my_dict = {x: x**2 for x in my_list}
my_dict[30] = 900
my_dict[15] = my_dict[15] + 50
my_dict.pop(10, None)
my_dict.popitem()
print(my_dict)
```

**Options:**  
A) `{5: 25, 15: 165, 20: 400, 25: 625, 30: 900}`  
B) `{5: 25, 15: 165, 20: 400, 25: 625}`  
C) `{5: 25, 15: 215, 20: 400, 25: 625}`  
D) `{5: 25, 15: 165, 20: 400, 25: 625, 30: 900, 10: 100}`


### **13**
What will be the output of the following code?

```python
s = "abcdefg"
result = s[::2].upper().replace('A', 'Z')
print(result)
```

**Options:**  
A) `"ACDFG"`  
B) `"ZCDFG"`  
C) `"ACDFZ"`  
D) `"ZCDFZ"`


### **14**
What will be the output of the following code?

```python
s = "Hello, World!"
result = s.split(',')[1].strip().lower()
print(result)
```

**Options:**  
A) `" world!"`  
B) `"world!"`  
C) `"world"`  
D) `"world"` (same as option C but different in output)


### **15**  
What will be the result of the following code?

```python
import math
result = math.cos(45) ** 2 + math.sin(45) ** 2 + math.tan(45) ** 2
print(result)
```

**Options:**  
A) `1`  
B) `2`  
C) `2.167`  
D) `4.34`

### **16**  
What will be the result of the following expression, considering operator precedence (PEDMAS)?

```python
result = 8 * (3 + 5 ** 2 / (2 * 2) - 4) // 5 + 7 % 4
print(result)
```

**Options:**  
A) `21`  
B) `20`  
C) `19`  
D) `17`


### **17**  
What will be the result of the following expression, considering operator precedence (PEDMAS)?

```python
result = 10 * (4 ** 3 - 8 * (2 + 1) // 3) + (15 % 4) * 3 - 6 / 2
print(result)
```

**Options:**  
A) `970`  
B) `960`  
C) `965`  
D) `980`



### **18**  
What will be the output of the following code?

```python
import turtle
t = turtle.Turtle()
t.forward(100)
t.right(90)
t.forward(100)
t.left(90)
t.forward(100)
t.hideturtle()
```

**Options:**  
A) A rectangle with sides 100 and 100  
B) A square of side 100  
C) A right triangle  
D) A right-angle zig-zag pattern


### **19**  
What will be the output of the following code?

```python
import random
result = random.choice([1, 2, 3]) + random.randint(10, 20) * random.random()
print(result)
```

**Options:**  
A) A random integer between 11 and 23  
B) A random float between 11 and 23  
C) A random float between 10 and 40  
D) A random float between 10 and 30

### **20**  
What will be the output of the following code?

```python
with open("data.txt", "w") as f:
    f.write("Hello, World!\n")
    f.write("Python is awesome.\n")
with open("data.txt", "r") as f:
    lines = f.readlines()
    print(len(lines))
```

**Options:**  
A) `1`  
B) `2`  
C) `3`  
D) `4`

## PART - B

---

Here are the advanced nested loop questions without options:

---

### **Question 1**  
What will be the output of the following code?

```python
i = 0
for x in range(4):
    while i < 12:
        if i % 2 == 0 and i % 3 == 0:
            print(i, end=' ')
        i += 2
        if i == 8:
            break
```

---

### **Question 2**  
What will be the output of the following code?

```python
i = 0
for x in range(5):
    while i < 8:
        if i == 4:
            i += 2
            continue
        print(i, end=' ')
        i += 1
```

---

### **Question 3**  
What will be the output of the following code?

```python
i = 0
for x in range(6):
    while i < 18:
        if i % 5 == 0 or i % 7 == 0:
            print(i, end=' ')
        elif i % 3 == 0:
            print(i * 2, end=' ')
        i += 1
        if i == 14:
            break
```

---

### **Question 4**  
What will be the output of the following code?

```python
n = 6
for i in range(n):
    for j in range(n - i):
        if (i + j) % 2 == 0:
            print("*", end=" ")
        else:
            print(" ", end=" ")
    print()
```

---

### **Question 5**  
What will be the output of the following code?

```python
i = 0
for x in range(6):
    while i < 10:
        if i == 2:
            i += 2
            continue
        if i == 8:
            break
        print(i, end=' ')
        i += 1
```

---

### **Question 6**  
What will be the output of the following code?

```python
i = 0
for x in range(3):
    while i < 9:
        if i == 5:
            i += 1
            continue
        if i == 7:
            break
        print(i, end=' ')
        i += 1
```

---


### **Question 7**

What will be the output of the following code?

```python
my_list = [10, 20, 30, 40]
for i in range(len(my_list)):
    if my_list[i] % 20 == 0:
        my_list.append(my_list[i] // 10)
my_list.reverse()
while len(my_list) > 3:
    my_list.pop()
print(my_list)
```

---

### **Question 8**

What will be the output of the following code?

```python
lst1 = [5, 10, 15]
lst2 = [20, 25]
i = 0
while i < len(lst1):
    lst1.extend(lst2)
    i += 1
    if i == 2:
        lst2 = [30, 35]
print(lst1)
```

---

---

### **Question 9**

What will be the output of the following code?

```python
my_dict = {'a': [1, 2], 'b': [3, 4], 'c': [5, 6]}
for key, value in my_dict.items():
    if len(value) == 2:
        value.pop()
        my_dict[key] = value
my_dict['d'] = [7, 8]
my_dict.clear()
while 'a' not in my_dict:
    my_dict['a'] = [9, 10]
print(my_dict)
```

---

### **Question 10**

What will be the output of the following code?

```python
my_dict = {'x': [1, 2], 'y': [3, 4]}
keys = ['x', 'y', 'z']
i = 0
while i < len(keys):
    if keys[i] in my_dict:
        my_dict[keys[i]].append(i)
    else:
        my_dict[keys[i]] = [i]
    i += 1
    if i == 2:
        my_dict.update({'z': [6, 7]})
print(my_dict)
```


### **Question 11**

What will be the output of the following code?

```python
lst = [1, 2, 3, 4, 5, 6]
for i in range(len(lst)):
    if i % 2 == 0:
        lst[i] *= 2
    elif lst[i] % 2 == 0:
        lst[i] += 3
    else:
        lst[i] -= 1
print(lst)
```

---

### **Question 12**

What will be the output of the following code?

```python
my_dict = {'x': 5, 'y': 10, 'z': 15}
for key in my_dict:
    my_dict[key] = my_dict[key] * 2 if key != 'y' else my_dict[key] - 2
    if key == 'z':
        my_dict[key] += my_dict['y']
print(my_dict)
```

---

### **Question 13**

What will be the output of the following code?

```python
s = "hello"
lst = [1, 2, 3, 4, 5]
result = ""
for i in range(len(s)):
    result += s[i].upper() if i % 2 == 0 else s[i]
    if i < len(lst):
        result += str(lst[i] * 2)
print(result)
```

---

### **Question 14**

What will be the output of the following code?

```python
lst = [3, 7, 9, 5]
for i in range(len(lst)):
    if lst[i] % 2 == 1:
        lst[i] += 3
    for j in range(i, len(lst)):
        lst[j] *= 2
print(lst)
```

---

### **Question 15**

What will be the output of the following code?

```python
lst = [2, 4, 6, 8]
for i in range(len(lst)):
    for j in range(i, len(lst)):
        lst[i] += lst[j] if i != j else 0
    if lst[i] % 2 == 0:
        lst[i] = lst[i] // 2
    else:
        lst[i] = lst[i] * 2
print(lst)
```


## PART - C

---

### **Question 1**

Write a Python program that performs the following tasks:

1. **Convert a decimal number to binary:**
   - Given a decimal number, convert it into its binary representation (without using Python's built-in `bin()` function).

2. **Calculate the Chi-square statistic:**
   - Given two lists: one representing the **observed frequencies** and the other representing the **expected frequencies**, calculate the **Chi-square statistic** using the formula:

    ![image](https://github.com/user-attachments/assets/4840a1d0-bdf5-4550-9e14-8dd4ca510c7a)

     Where:
     - \( O_i \) is the observed frequency for the \(i\)-th event.
     - \( E_i \) is the expected frequency for the \(i\)-th event.

### **Example:**

1. For the **binary conversion**, given the number `42`, the program should output `101010`.
2. For the **Chi-square calculation**, given:
   - Observed frequencies: `[20, 30, 50]`
   - Expected frequencies: `[25, 25, 50]`
   
   The program should output the calculated Chi-square statistic.

### **Expected Output:**

- For the binary conversion (input: `42`):  
  Output: `101010`
  
- For the Chi-square calculation (input: `observed=[20, 30, 50]`, `expected=[25, 25, 50]`):  
  Output: `1.0`

---

### **Guidelines:**

- Use a loop to manually convert the decimal number to binary.
- Use a loop to calculate the Chi-square statistic by iterating through both the **observed** and **expected** lists.

Sure! Here’s the **programming question** based on Fibonacci, factorial, and matrix:

---

### **Question 2**

In the magical kingdom of **Algebraia**, there are three mystical puzzles that the wizard must solve to unlock the secrets of the universe. Your task is to help the wizard solve these puzzles by writing a Python program.

#### **Puzzle 1: Fibonacci Series and Matrix Combination**

The Fibonacci sequence holds a significant role in Algebraia. For this puzzle, you are given a number **n**, and your task is to calculate the **n-th Fibonacci number** and then **square it**.

**Task:**
- Write a function that calculates the **n-th Fibonacci number** and returns its square.

#### **Puzzle 2: Factorial Calculation**

The second puzzle is about calculating the **factorial** of a number. The wizard gives you a number **m**, and you need to calculate its factorial. This factorial will be used in the final matrix puzzle.

**Task:**
- Write a function to calculate the **factorial** of a given number **m**.

#### **Puzzle 3: Matrix Transformation**

In the final puzzle, you are provided with a **2x2 matrix**. Using the results of Puzzle 1 (the squared Fibonacci number) and Puzzle 2 (the factorial), you need to transform the matrix by:
1. Multiplying each element of the matrix by the squared Fibonacci number.
2. Adding the factorial result to each element of the matrix.

**Task:**
- Write a function that takes a **2x2 matrix**, multiplies each element by the squared Fibonacci number, and adds the factorial value to each element of the matrix.
- Return the transformed matrix.

### **Input:**
- A number **n** (n ≥ 1) for the Fibonacci series.
- A number **m** (m ≥ 1) for the factorial.
- A **2x2 matrix** represented as a list of lists.

### **Output:**
- The transformed **2x2 matrix**.

---

**Example:**

For **n = 6** and **m = 4**, the Fibonacci number is **8**, its square is **64**, and the factorial of 4 is **24**. If the matrix is:

```
A = [[1, 2],
     [3, 4]]
```

Then the transformed matrix should be:

```
[[64 + 24, 128 + 24],
 [192 + 24, 256 + 24]]
```


### **Question 3**

In the ancient library of **Mathematica**, there is a scroll containing the most powerful formulas for calculating values in both **trigonometry** and **calculus**. The wizard has given you the following two challenges to solve:

#### **Challenge 1: Trigonometric Transformation**

The wizard wants to calculate the value of a trigonometric expression involving both **sine** and **cosine**. Given an angle **θ** in degrees, you need to calculate and return the result of the following expression:

![image](https://github.com/user-attachments/assets/60e965af-73ce-408e-b939-1ee7685869cc)


This formula is a fundamental identity in trigonometry known as the **Pythagorean Identity**.

**Task:**
- Write a function that accepts an angle **θ** (in degrees), converts it to radians, and then computes the result of the trigonometric identity **sin²(θ) + cos²(θ)**.

#### **Challenge 2: Calculus Integration (Manual Integration)**

The second challenge involves integrating a function. The wizard has given you a simple function to integrate: 

![image](https://github.com/user-attachments/assets/8457b84b-e8ed-4b1a-8013-48d9358a1c0c)


You need to compute the **definite integral** of this function between **a** and **b**, where **a** and **b** are the limits of integration provided by the wizard. The result of the integration will help the wizard understand the total area under the curve of the function between these two limits.

**Task:**
- Write a function that computes the definite integral of the function \( f(x) = x^2 + 3x + 2 \) manually using the **trapezoidal rule** for numerical integration. You should divide the interval [a, b] into smaller segments and approximate the area under the curve by calculating the sum of the areas of trapezoids.

### **Input:**
1. A floating-point number **θ** (angle in degrees) for the trigonometric calculation.
2. Two floating-point numbers **a** and **b** for the limits of integration.

### **Output:**
1. The result of the trigonometric identity **sin²(θ) + cos²(θ)**.
2. The value of the definite integral for the function \( f(x) = x^2 + 3x + 2 \) between **a** and **b** using the trapezoidal rule.

---

### **Example:**

#### **Example 1:**

**Input:**
```
θ = 45
```

**Output:**
```
Trigonometric Identity Result: 1.0
```

#### **Example 2:**

**Input:**
```
a = 0
b = 2
```

**Output:**
```
Definite Integral Result: 10.666666666666666
```

---

### **Program Requirements:**
1. Use the `math` module for trigonometric calculations.
2. Use the **trapezoidal rule** for the numerical integration to calculate the area under the curve.

---

### **Hints:**
- For the trigonometric calculation, you’ll need to convert **θ** from degrees to radians

![image](https://github.com/user-attachments/assets/61acdea9-8c74-41ed-a57c-656435d658c8)

- For the integration, the trapezoidal rule is calculated by approximating the integral as the sum of the areas of trapezoids:

  ![image](https://github.com/user-attachments/assets/634ada41-1484-477b-b658-440076595874)

  where \( x_i \) are the points between **a** and **b**.




