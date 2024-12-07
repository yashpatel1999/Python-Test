
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
