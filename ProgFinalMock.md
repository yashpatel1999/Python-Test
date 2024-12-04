

#### **Part A: Multiple Choice Questions (20 questions)**  

**Q1.** What is the result of this expression?  
```python
5 ** 2 // 10 + 3 - 4 % 2 * 5
```  
a) 5  
b) 4  
c) 25  
d) 3  

---

**Q2.** What is the output of this code?  
```python
x = (1, 2)
y = (1, 2)
print(x is y)
```  
a) True  
b) False  
c) None  
d) Error  

---

**Q3.** Which of the following does **not** produce a syntax error?  
a) `x = 1 + (2 * )`  
b) `y = [1, 2: 3]`  
c) `z = 10 // 0`  
d) `a = b = c = None`  

---

**Q4.** What is the output of this code?  
```python
x = "abcde"
y = x[1:-1]
print("a" in y)
```  
a) True  
b) False  
c) Error  
d) None  

---

**Q5.** What will this code print?  
```python
d = {"a": 1, "b": 2, "c": 3}
print(d["b"] + d.get("d", 0))
```  
a) 2  
b) 3  
c) 5  
d) Error  

---

**Q6.** Which of the following is True regarding Python lists?  
a) They are immutable.  
b) The elements can have different types.  
c) The length must be defined at creation.  
d) They cannot be nested.  

---

**Q7.** What does this code print?  
```python
x = [1, 2, 3]
y = x
y.append(4)
print(x == y and x is not y)
```  
a) True  
b) False  
c) Error  
d) None  

---

**Q8.** What does this slice return?  
```python
lst = [10, 20, 30, 40, 50]
print(lst[-3:-1:1])
```  
a) `[30, 40]`  
b) `[40, 30]`  
c) `[30, 40, 50]`  
d) Error  

---

**Q9.** What is the output of this code?  
```python
print(sorted(["apple", "Banana", "cherry"], key=str.lower))
```  
a) `['apple', 'Banana', 'cherry']`  
b) `['Banana', 'apple', 'cherry']`  
c) `['Banana', 'cherry', 'apple']`  
d) Error  

---

**Q10.** What is the result of this code?  
```python
def func(a, b=[]):
    b.append(a)
    return b

print(func(1))
print(func(2))
```  
a) `[1], [2]`  
b) `[1], [1, 2]`  
c) `[1], [1, 2, 2]`  
d) Error  

---

**Q11.** What is the output of this code?  
```python
print(any([False, 0, [], {}, None]))
```  
a) True  
b) False  
c) Error  
d) None  

---

**Q12.** What is the output of this code?  
```python
s = "abcde"
print(s.find("e") == len(s) - 1)
```  
a) True  
b) False  
c) Error  
d) None  

---

**Q13.** What will this code print?  
```python
a = [1, 2, 3]
b = a[:]
a[0] = 10
print(b[0])
```  
a) 1  
b) 10  
c) Error  
d) None  

---

**Q14.** Which of the following statements will cause a runtime error?  
a) `print(10 / 0)`  
b) `print([1, 2] + (3, 4))`  
c) `print(int("abc"))`  
d) `print({1, 2} | {3})`  

---

**Q15.** What is the output of this code?  
```python
x = {1: "a", 2: "b"}
print(x.get(3, "default"))
```  
a) `None`  
b) `default`  
c) Error  
d) None  

---

**Q16.** What is the result of this code?  
```python
s = {x for x in range(5) if x % 2 == 0}
print(len(s))
```  
a) 2  
b) 3  
c) 4  
d) 5  

---

**Q17.** Which of the following is **not** a valid Python function?  
a) `sum()`  
b) `len()`  
c) `map()`  
d) `list.add()`  

---

**Q18.** Which statement about the `range()` function is correct?  
a) `range(5)` generates `[0, 1, 2, 3, 4, 5]`  
b) `range(1, 5)` excludes 5  
c) `range(0, 10, 2)` generates all odd numbers  
d) `range()` can only accept one argument  

---

**Q19.** What will be the result of this code?  
```python
x = lambda a: a + 10
print(x(5))
```  
a) 15  
b) 10  
c) Error  
d) None  

---

**Q20.** Which of the following is True for the `reversed()` function?  
a) It modifies the list in place.  
b) It returns an iterator.  
c) It is the same as `.reverse()`.  
d) It works only for strings.  

---
#### **Part B: Find the Output (15 Questions)**  

---

**Q1.** What is the output of the following code?  
```python
for i in range(1, 4):
    for j in range(1, i + 1):
        print(i * j, end=" ")
    print()
```  

---

**Q2.** What is the output of this snippet?  
```python
matrix = [
    [1, 2, 3],
    [4, 5, 6],
    [7, 8, 9]
]
result = []
for i in range(len(matrix)):
    result.append(matrix[i][i])
print(result)
```  

---

**Q3.** What will this code print?  
```python
f = open("output.txt", "w")
f.write("Hello\nWorld")
f.close()

f = open("output.txt", "r")
lines = f.readlines()
print(lines)
f.close()
```  

---

**Q4.** What is the output of this code?  
```python
x = [10, 20, 30]
y = []
for n in x:
    row = []
    for i in range(1, 4):
        row.append(n * i)
    y.append(row)
print(y[1][2])
```  

---

**Q5.** What will this nested loop print?  
```python
for i in range(2):
    for j in range(2, 4):
        print(i, "-", j)
```  

---

**Q6.** What does the following code produce?  
```python
x = 3.14159
formatted = "{:.2f}".format(x)
print("The value is", formatted)
```  

---

**Q7.** What will this file handling code print?  
```python
with open("test.txt", "w") as f:
    f.write("Python\nProgramming")

with open("test.txt", "r") as f:
    lines = f.read().splitlines()
    print(lines)
```  

---

**Q8.** What is the output of this code?  
```python
matrix = [[0, 1], [2, 3], [4, 5]]
transposed = []
for i in range(len(matrix[0])):
    row = []
    for row_vals in matrix:
        row.append(row_vals[i])
    transposed.append(row)
print(transposed)
```  

---

**Q9.** Predict the output:  
```python
for i in range(1, 6):
    stars = "*" * i
    print(stars)
```  

---

**Q10.** What is the output of this snippet?  
```python
word = "python"
padded = "-" * 2 + word + "-" * 2
print(padded)
```  

---

**Q11.** What will this print?  
```python
for i in range(3):
    for j in range(3):
        if i == j:
            break
        print(i, j, end=" | ")
```  

---

**Q12.** What is the output?  
```python
fruits = ["apple", "banana", "cherry"]
prices = [100, 200, 150]
combined = {}
for i in range(len(fruits)):
    combined[fruits[i]] = prices[i]
print(combined)
```  

---

**Q13.** What does this produce?  
```python
file_content = "a,b,c\nd,e,f\ng,h,i"
with open("file.csv", "w") as f:
    f.write(file_content)

with open("file.csv", "r") as f:
    for line in f:
        print(line.strip())
```  

---

**Q14.** What is the output of this nested list code?  
```python
result = []
for i in range(4):
    inner = []
    for j in range(i):
        inner.append(j)
    result.append(inner)
print(result)
```  

---

**Q15.** What does this produce?  
```python
for i in range(1, 4):
    print("Row", i, ":", end=" ")
    for j in range(i):
        print("(", i, ",", j, ")", end=" ")
    print()
```  

---

This updated version uses simpler syntax and focuses on clarity while retaining the challenge. Let me know if you need more adjustments!

Here's a more challenging and interesting version of the exam questions, making them trickier by adding more constraints, deeper logical steps, and more engaging real-world applications:

---

**Part C: Code Writing (40 points)**


**Question 1:**
You are given a list of transaction records stored as strings in the format `"Date, Description, Amount"`. Write a function that:
1. Parses the input and extracts the total transaction amount.
2. Calculates the highest transaction amount and the lowest transaction amount along with their corresponding descriptions.
3. If a transaction description contains the word "refund," it should be considered a negative amount, and all refunds should be subtracted from the total. If a description contains the word "bonus," it should be considered a positive boost (double the amount).
4. If any transaction exceeds $1000, apply a 5% tax on the amount and adjust the total.
5. After calculating, print the total transaction amount, the highest transaction, the lowest transaction, and the adjusted amount if applicable.

**Example Input:**
```python
transactions = [
    "2024-12-01, Grocery, 50",
    "2024-12-02, Refund, -10",
    "2024-12-03, Electronics, 2000",
    "2024-12-04, Bonus, 300",
    "2024-12-05, Refund, -20"
]
```

**Question 2:**
You are given a text file `orders.txt` that contains multiple lines, each representing an order with the following format:
```
OrderID, Product, Quantity, Price
```
Write a function that:
1. Opens the file and reads its content.
2. Finds and replaces all occurrences of the word "OldProduct" with "NewProduct".
3. Saves the modified content back to the same file.
4. Ensure that after modification, all lines where `Quantity` is more than 10 are printed to the console.

**Example Content in `orders.txt`:**
```
123, OldProduct, 5, 10
456, OldProduct, 15, 20
789, NewProduct, 10, 30
```

**Expected Output (in Console after replacement):**
```
456, NewProduct, 15, 20
```

---

**Combined Question: 3**

**Story:**  
You are designing a system for an e-commerce platform that tracks product sales and stock levels across multiple warehouses. The system stores data in a matrix where each row represents a warehouse, and each column represents a product. You also store product information in a dictionary with the product's name, price, and a stock threshold (the minimum number of units that should remain in stock).

Write a function that:
1. Converts the sales data matrix to total revenue (quantity sold * product price) for each warehouse. Each cell in the matrix represents the number of units sold of a product in a warehouse.
2. Updates the stock levels for each product in each warehouse. After sales, decrease the stock based on the number of units sold, and check if any product's stock falls below the threshold. If it does, print a message saying that product needs restocking.
3. If a product's stock across all warehouses falls below the threshold, add it to a list of products needing restocking.
4. Create a new dictionary with products that need restocking and their total stock across all warehouses.

**Example Input:**

```python
sales_matrix = [
    [20, 15, 30],  # Warehouse 1
    [50, 40, 25],  # Warehouse 2
    [30, 35, 10]   # Warehouse 3
]

products = {
    "Laptop": {"price": 1000, "threshold": 30, "stock": 50},
    "Smartphone": {"price": 500, "threshold": 20, "stock": 70},
    "Headphones": {"price": 100, "threshold": 10, "stock": 20}
}
```

**Expected Output:**
```
Revenue for each warehouse:
[50000, 65000, 32000]

Products needing restocking:
Laptop, Headphones

Products with total stock below threshold:
Headphones - Total Stock: 20
Laptop - Total Stock: 50
```

---
