# Python-Test
## Part-A

---

**1. What will be the output of the following code?**

```python
def func(x, y=[]):
    y.append(x)
    return y

print(func(1))
print(func(2))
```


a) 6  
b) 8  
c) 9  
d) 16  

---

**2. Which of the following is the correct way to declare a variable in Python?**

a) `int x = 10`  
b) `x : int = 10`  
c) `x = 10`  
d) `var x = 10`  

---

**3. What is the data type of the following expression?**

```python
type(3.5)
```

a) `int`  
b) `float`  
c) `str`  
d) `complex`  

---

**4. What will be the output of the following code?**

```python
a = [1, 2, 3]
a.append([4, 5])
print(len(a))
```

a) 4  
b) 5  
c) 6  
d) 7  

---

**5. Which keyword is used to define a function in Python?**

a) `def`  
b) `function`  
c) `func`  
d) `define`  

---

**6. What will be the output of the following code?**

```python
a = 10
b = 20
print(a, b)
a, b = b, a
print(a, b)
```

a) `10 20` and `10 20`  
b) `10 20` and `20 10`  
c) `20 10` and `10 20`  
d) `20 10` and `20 10`  

---

**7. What will be the output of the following code?**

```python
a = (1, 2, 3)
a[0] = 5
```

a) `(5, 2, 3)`  
b) `(1, 2, 3)`  
c) `Error`  
d) `[5, 2, 3]`  

---

**8. What is the output of the following code?**

```python
def foo(bar=[]):
    bar.append("baz")
    return bar

print(foo())
print(foo())
```

a) `["baz"], ["baz"]`  
b) `["baz"], ["baz", "baz"]`  
c) `["baz"], ["baz", "bar"]`  
d) `Error`  


---

**9. What will be the output of the following code?**

```python
a = [1, 2, 3, 4]
b = [x**2 for x in a if x % 2 == 0]
print(b)
```

a) `[4, 16]`  
b) `[1, 9]`  
c) `[2, 4]`  
d) `[2, 16]`  

---


**10. What is the output of this code?**

```python
d = {'x': 100, 'y': 200}
print(d.get('z', 300))
```

a) 100  
b) 200  
c) 300  
d) KeyError  



---

**11. How do you create a dictionary in Python?**

a) `dict = {}`  
b) `dict = []`  
c) `dict = ()`  
d) `dict = set()`  

---

**12. Which of the following is not a valid Python variable name?**

a) `_var1`  
b) `2variable`  
c) `variable_name`  
d) `var123`  

---

**13. What will be the output of the following code?**

```python
x = [1, 2, 3]
y = x
y.append(4)
print(x)
```

a) `[1, 2, 3]`  
b) `[1, 2, 3, 4]`  
c) `None`  
d) `Error`  

---

**14. What does the `range()` function return in Python 3?**

a) A list  
b) A tuple  
c) A range object  
d) A generator  

---

**15. How can you add an element to the end of a list in Python?**

a) `list.add()`  
b) `list.append()`  
c) `list.insert()`  
d) `list.extend()`  

---


## Part - B
Here’s a Python code that includes **loops**, **conditions**, **lists**, and **strings**, and is at least 8 lines long:

---

### **Code 1**

```python
words = ["level", "world", "madam", "python", "radar", "openai"]
palindromes = []

for word in words:
    if word == word[::-1]:  # Checking if the word is a palindrome
        palindromes.append(word)

if palindromes:
    print("Palindromes found:", palindromes)
else:
    print("No palindromes found.")
```

---

### **Code 2**

```python
sentence = "Python is fun and exciting"
words = sentence.split()
vowel_count = {}

for word in words:
    count = 0
    for char in word:
        if char.lower() in 'aeiou':
            count += 1
    vowel_count[word] = count

print("Vowel count per word:", vowel_count)
```


---

### **Code 3**

```python
numbers = [10, 23, 36, 41, 58, 63, 72]
even_numbers = []

for num in numbers:
    if num % 2 == 0:  # Checking if the number is even
        even_numbers.append(str(num))  # Convert to string and append

if even_numbers:
    print("Even numbers are:", ", ".join(even_numbers))
else:
    print("No even numbers found.")
```


---

### **Code 4**

```python
sentence = "hello world, python programming is fun"
words = sentence.split()
capitalized_words = []

for word in words:
    if word[0].islower():  # Check if the first letter is lowercase
        capitalized_words.append(word.capitalize())
    else:
        capitalized_words.append(word)

new_sentence = " ".join(capitalized_words)
print("Capitalized sentence:", new_sentence)
```


---

### **Code 5**

```python
words = ["Python", "code", "excitement", "short", "lists", "automation"]
long_words = []

for word in words:
    if len(word) > 5:  # Checking if the word length is greater than 5
        long_words.append(word)

if long_words:
    print("Words longer than 5 characters:", long_words)
else:
    print("No long words found.")
```
Here’s another Python code that includes **loops**, **conditions**, **lists**, and **strings**, and is at least 8 lines long:

---

### **Code 6**

```python
sentence = "Python programming is fun and challenging"
words = sentence.split()
short_words = []
long_words = []

for word in words:
    if len(word) <= 3:  # Words with 3 or fewer characters
        short_words.append(word)
    else:  # Words with more than 3 characters
        long_words.append(word)

print("Short words:", short_words)
print("Long words:", long_words)
```

---

## Part - C
Here’s how we can make the above problems more engaging and challenging, by adding extra layers of logic that students need to work through. These additions involve more dynamic inputs, additional constraints, and multi-step problem-solving.

---

### **1.**

**Story:**  
The local library’s operations have become more complex, and the librarian wants additional functionality. Apart from organizing books by categories, the librarian also wants to:
1. Add new books to existing categories.
2. Add new categories to the library.
3. Remove books from the library.

Your task is to create a program that allows the librarian to perform these actions dynamically and handle errors such as trying to remove a book or category that doesn't exist.

**Task:**  
Write a Python program that:
1. Lets the librarian view books by category.
2. Allows the librarian to add new books to an existing category or create a new category if it doesn't exist.
3. Lets the librarian remove books or categories if needed.
4. Handles errors like trying to remove a non-existent book or category.

**Additional Challenge:**
- Allow the librarian to perform multiple actions until they decide to exit.

**Example Input:**  
The librarian might input a series of actions like:
- "view Fiction"
- "add book 'Brave New World' to Fiction"
- "remove book '1984' from Fiction"
- "remove category 'Mystery'"
- "exit"

**Output:**  
The program should respond dynamically to each action:
- Show the updated book list.
- Show error messages if a book or category cannot be found.
- Allow repeated actions until the librarian chooses to exit.

---

### **2.**

**Story:**  
The village is now monitoring water consumption more closely, and there’s a new rule: any household that exceeds 350 liters of water in a week will receive a "Water Usage Alert." The village head also wants to know how the average daily water usage compares across households.

**Task:**  
Write a Python program that:
1. Tracks the daily water consumption for each household over 7 days.
2. Calculates the total weekly water consumption for each household.
3. Issues a "Water Usage Alert" for households that exceed 350 liters in a week.
4. Determines the household with the highest weekly consumption.
5. Calculates and compares the average daily water usage of each household.

**Additional Challenge:**
- Add functionality for the village head to request data for specific days, such as: "Show me the water usage for all households on Day 3."
- Implement a summary at the end that shows how each household’s total consumption compares to the village average.

**Example Input:**  
Data for 7 days like:
```python
week_data = [
    {'House1': 50, 'House2': 30, 'House3': 60},
    {'House1': 45, 'House2': 35, 'House3': 55},
    {'House1': 40, 'House2': 32, 'House3': 58},
    {'House1': 55, 'House2': 33, 'House3': 60},
    {'House1': 60, 'House2': 36, 'House3': 62},
    {'House1': 50, 'House2': 31, 'House3': 64},
    {'House1': 65, 'House2': 38, 'House3': 66},
]
```

**Output:**
- Total weekly water consumption for each household.
- Water usage alerts for households exceeding 350 liters.
- The household with the highest consumption.
- Daily averages and comparison across households.

---

### **3.**

**Story:**  
You’re now managing a high-profile event where not only must the VIP guests be seated first, but the event also has limited seating. VIPs get first priority, but you still need to allocate seats for Regular guests based on the remaining capacity.

Your task is to ensure that:
1. VIPs are always seated first, without duplicates.
2. Regular guests can only be seated if there are remaining seats after all VIPs are seated.
3. The seating capacity is limited, and the total number of guests (VIPs + Regulars) cannot exceed this limit.
4. Guests are seated in alphabetical order (VIPs first, then Regulars).

**Task:**  
Write a Python program that:
1. Takes two lists (VIP guests and Regular guests).
2. Removes duplicates within and across both lists.
3. Allocates seats, prioritizing VIPs.
4. Stops accepting regular guests if seating capacity is reached.
5. Displays the final seated guest list in alphabetical order.

**Additional Challenge:**
- Allow the event manager to input the total seating capacity dynamically.
- If any Regular guests cannot be seated due to lack of capacity, display a message with their names and explain that they couldn’t be accommodated.

**Example Input:**
- VIP guest list: `['Alice', 'Bob', 'Charlie', 'Alice']`
- Regular guest list: `['David', 'Eve', 'Bob', 'Frank']`
- Seating capacity: `5`

**Output:**
- Final guest list with seated guests in alphabetical order.
- Names of Regular guests who couldn’t be seated if the seating capacity is exceeded.

---

