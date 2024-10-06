# Mock Test 2
## Part-A
---


1. **What is the result of the binary addition `1011 + 1101`?**

    a) `11000`  
    b) `10110`  
    c) `11001`  
    d) `10101`
    

2. **Which of the following Python code snippets will convert a binary string `1101` to its decimal equivalent and subtract 5 from it?**

    ```python
    a = "1101"
    # Subtract 5
    ```
    
    a) `print(bin(int(a, 2) - 5))`  
    b) `print(int(a, 10) - 5)`  
    c) `print(oct(int(a, 2)) - 5)`  
    d) `print(hex(int(a, 2)) - 5)`
    
---

3. **What will be the output of the following Python code snippet?**
    ```python
    s = "openai"
    print(s[::-1] + s[:3] + s[3:])
    ```

    a) `ianepoopenai`  
    b) `iaepnoneai`  
    c) `ianepopenai`  
    d) `openaiopenai`

4. **What will the output of the following code be?**
    ```python
    def modify_string(s):
        return s.replace('p', 'q').capitalize()

    s = "python"
    print(modify_string(s))
    ```

    a) `Python`  
    b) `Qython`  
    c) `Qython`  
    d) `python`

5. **Which of the following code snippets correctly concatenates a string by doubling the first three characters?**

    ```python
    s = "string"
    ```
    
    a) `print(s[:3] + s[:3] + s)`  
    b) `print(s[:3] * 2)`  
    c) `print(s[3:] + s[:3])`  
    d) `print(2 * s[:3] + s[3:])`


---

6. **What will be the output of the following code?**
    ```python
    def func(a=[]):
        a.append(len(a))
        return a

    print(func())
    print(func())
    print(func([1]))
    ```
    
    a) `[0] [0, 1] [1, 1]`  
    b) `[0] [0] [1, 1]`  
    c) `[0] [0, 1] [1]`  
    d) `[0] [1] [1, 1]`


7. **What will be the result of the following code execution?**
    ```python
    def func(x):
        return x * [x]

    result = func(3)
    print(result)
    ```

    a) `[3, 3, 3]`  
    b) `[[3], [3], [3]]`  
    c) `[9]`  
    d) `[3]`

8. **What will the following code output?**
    ```python
    x = 3
    y = 4
    z = eval('x * y + y')
    print(z)
    ```

    a) `7`  
    b) `16`  
    c) `12`  
    d) `Error`

---

9. **What is the result of the following Python code?**
    ```python
    a = [1, 2, 3]
    b = a.copy()
    b.append(4)
    print(a, b)
    ```

    a) `[1, 2, 3] [1, 2, 3, 4]`  
    b) `[1, 2, 3, 4] [1, 2, 3, 4]`  
    c) `[1, 2, 3] [4]`  
    d) `[1, 2, 3, 3] [1, 2, 3, 4]`


10. **What is the output of the following code?**
    ```python
    x = [[1, 2], [3, 4]]
    print(x[1][1])
    ```

    a) `3`  
    b) `4`  
    c) `1`  
    d) `2`


11. **What will be printed by this code?**
    ```python
    list1 = [10, 20, 30, 40]
    list2 = list1[::-1]
    print(list2)
    ```

    a) `[40, 30, 20, 10]`  
    b) `[30, 20, 10]`  
    c) `[10, 20, 30]`  
    d) `[40, 20, 10]`


---


12. **Which of the following code snippets correctly sorts a list in descending order?**

    ```python
    my_list = [3, 1, 4, 1, 5]
    ```

    a) `my_list.sort(reverse=True)`  
    b) `my_list.sorted(reverse=True)`  
    c) `my_list.sort(key=reverse)`  
    d) `my_list.sorted(key=reverse)`


13. **What will be the output of the following Python code?**
    ```python
    list1 = [1, 2, 3, 4]
    list1.pop(2)
    print(list1)
    ```

    a) `[1, 2, 4]`  
    b) `[1, 3, 4]`  
    c) `[1, 2, 3, 4]`  
    d) `[1, 2, 4, 4]`


---

14. **What will be printed by the following code that uses nested `for` and `while` loops?**
    ```python
    i = 0
    while i < 5:
        i += 1
        for j in range(2, i):
            print(j, end=" ")
    ```
    
    a) `2 3 4`  
    b) `2 3 2 4 2 3 4`  
    c) `2 3 4 2 3`  
    d) `3 4 2 3`

15. **Given the following code, which of the following is correct?**
    ```python
    def func(a, b):
        return a if a > b else b

    result = func(*[2, 5])
    print(result)
    ```

    a) `2`  
    b) `5`  
    c) `Error`  
    d) `None`


---
## Part - B


   
1. **Code 1:**
    ```python
    i = 1
    while i < 4:
        for j in range(i):
            print(i * j)
        i += 1
    ```

2. **Code 2:**
    ```python
    word = "Python"
    i = 0
    while i < len(word):
        for j in range(i, len(word)):
            print(word[j])
        i += 2
    ```


3. **Code 3:**
    ```python
    i = 0
    while i < 3:
        for j in range(3, 6):
            if j > 4:
                print(i, j, ">", 4)
            else:
                print(i, j, "<=", 4)
        i += 1
    ```

4. **Code 4:**
    ```python
    x = 0
    while x < 4:
        for y in range(x, 3):
            if y == x:
                print("Equal", x, y)
            else:
                print("Not equal", x, y)
        x += 1
    ```

5. **Code 5:**
    ```python
    def modify_list(lst):
        for i in range(len(lst)):
            lst[i] *= 2
        return lst

    my_list = [1, 2, 3]
    print(modify_list(my_list))
    ```

6. **Code 6:**
 ```python
def complex_logic(lst):
    result = []
    for i in range(len(lst)):
        if lst[i] % 2 == 0:
            while lst[i] > 0:
                lst[i] -= 1
                result.append(lst[i])
        else:
            for j in range(lst[i]):
                if j % 2 == 1:
                    result.append(j)
    return result

numbers = [4, 5, 3]
print(complex_logic(numbers))
```
## Part - C


---

### Problem 1: The Magical Garden

**Story:**

Once upon a time in a magical garden, there was a grid of flowers, where each flower had a unique color represented by a number. The garden was organized in a 2D matrix, with each cell representing a flower. 

One sunny day, a little girl named Lily decided to pick flowers. She could only pick flowers in a straight line — either horizontally or vertically. To make it more exciting, she wanted to collect flowers that are arranged in a particular pattern. 

Lily found a magical spellbook that contained the following rule: "You can pick flowers if they are all the same color, and you need to find the longest straight line of flowers of the same color." 

### Your Task:

1. **Input:** 
   - Create a 2D matrix representing the garden, where each cell contains a number that corresponds to the color of the flower. 
   - For example, the garden could look like this:
     ```
     [
       [1, 2, 2, 3],
       [4, 2, 2, 3],
       [1, 1, 1, 1],
       [2, 2, 3, 4]
     ]
     ```

2. **Output:** 
   - Write a function that takes this matrix as input and returns the length of the longest line of flowers that are the same color (horizontally or vertically).

3. **Example:**
   - For the given garden, the longest line of flowers with the same color is 4 (the line of `1`s in the third row).

### Hints:
- You may want to loop through each row and column of the matrix to count the longest sequence of same-colored flowers.
- Consider using variables to keep track of the current flower color and the count of consecutive flowers.

---

### Expected Function Signature:

```python
def longest_flower_line(garden: List[List[int]]) -> int:
    pass
```

### Example Test Case:

```python
garden = [
    [1, 2, 2, 3],
    [4, 2, 2, 3],
    [1, 1, 1, 1],
    [2, 2, 3, 4]
]

print(longest_flower_line(garden))  # Output should be 4
```

Here’s a string manipulation problem that does not require using built-in functions like `split()`, `ord()`, or `chr()`, focusing purely on basic string operations:

---

### Problem 2: The Enchanted Mirror

**Story:**

In a magical realm, there is a mirror known as the Enchanted Mirror of Veritas. This mirror has the unique ability to reveal the hidden messages within words. The mirror can only show the words in reverse order, but it has a special rule: any vowels (a, e, i, o, u) in the words must be replaced with asterisks (*).

One day, the wise wizard, Merlino, challenged you to reveal the hidden messages from a sentence by following the mirror's rules.

### Your Task:

1. **Input:** 
   - Write a function that takes a string (the message) as input.
   - For example:
     ```python
     message = "Hello Universe"
     ```

2. **Output:** 
   - The function should return a new string where each word is reversed, and all vowels are replaced with asterisks.

3. **Example:**
   - For the input string `"Hello Universe"`, the output should be:
     ```
     "ll*H *s*rev*n"
     ```

### Hints:
- You can use a loop to iterate through the string character by character.
- Keep track of the current word and build the reversed version manually.
- Consider using a variable to accumulate the result without relying on built-in functions.

---

### Expected Function Signature:

```python
def enchanted_mirror(message: str) -> str:
    pass
```

### Example Test Case:

```python
message = "Hello Universe"
print(enchanted_mirror(message))  
# Output should be "ll*H *s*rev*n"
```
Sure! Here’s the modified problem where the output is a list instead of a tuple:

---

### Problem 3: The Treasure Hunt

**Story:**

In the mystical land of Altheria, a group of adventurers discovered a hidden treasure buried in a list of numbers. The treasure could only be revealed by performing a special operation: summing up the even numbers and multiplying the odd numbers in the list. The adventurers need your help to unlock the treasure!

### Your Task:

1. **Input:** 
   - Write a function that takes a list of integers as input.
   - For example:
     ```python
     numbers = [1, 2, 3, 4, 5, 6]
     ```

2. **Output:** 
   - The function should return a list containing two values:
     - The sum of all even numbers in the list.
     - The product of all odd numbers in the list.
   - If there are no odd numbers, the product should be `1`.

3. **Example:**
   - For the input list `[1, 2, 3, 4, 5, 6]`, the output should be:
     ```python
     [12, 15]
     ```
     - Explanation: The sum of even numbers (2 + 4 + 6) is `12`, and the product of odd numbers (1 * 3 * 5) is `15`.

### Hints:
- Use loops to iterate through the list and separate even and odd numbers.
- Initialize variables to keep track of the sum and product.

---

### Expected Function Signature:

```python
def treasure_hunt(numbers: list) -> list:
    pass
```

### Example Test Case:

```python
numbers = [1, 2, 3, 4, 5, 6]
print(treasure_hunt(numbers))  
# Output should be [12, 15]
```

### Instructions for Assert Test Cases:

After writing the function, use assert statements to validate the correctness of your solution. Here are some example test cases you can use:

give at least 3 other assert test case containing corner cases in 1 of the assert statement.
```python
# Test cases
assert treasure_hunt([1, 2, 3, 4, 5, 6]) == [12, 15]  # Example case

```

This version of the problem retains the original concept while changing the output format to a list, allowing students to work with lists and validate their code using assert test cases.
