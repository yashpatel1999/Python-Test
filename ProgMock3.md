## PART A

1. **Which of the following is the output of the following code?**
   ```python
   x = [1, 2, 3]
   y = [4, 5, 6]
   z = x + y
   z[0] = 10
   print(x[0])
   ```
   a) 1  
   b) 10  
   c) IndexError  
   d) None of the above  

2. **What will be the output of the following code?**
   ```python
   def func(x=[]):
       x.append(1)
       return x
   print(func())
   print(func())
   ```
   a) [1] [1]  
   b) [1] [1, 1]  
   c) [1, 1] [1, 1]  
   d) Error  

3. **What is the output of the following code?**
   ```python
   a = [1, 2, 3, 4]
   b = a
   a[0] = 10
   print(b[0])
   ```
   a) 1  
   b) 10  
   c) [1, 2, 3, 4]  
   d) Error  

4. **Which of the following can be used to correctly check if a string is a palindrome in Python?**
   a) `str == str[::-1]`  
   b) `str.isPalindrome()`  
   c) `str[::] == str[::-1]`  
   d) `str == str[::]`  

5. **What will be the output of the following code?**
   ```python
   def foo(x, y=[]):
       y.append(x)
       return y
   print(foo(10))
   print(foo(20, []))
   ```
   a) [10] [20]  
   b) [10] [20, 10]  
   c) [20] [10]  
   d) [10, 20] [20]  

**6. Which of the following statements will result in a `TypeError` in Python?**

a) `x = "hello" * 2`  
b) `x = "hello" + 2`  
c) `x = 5 + 3`  
d) `x = [1, 2, 3] + [4, 5]`  

7. **What will be the output of the following code?**
   ```python
   x = 10
   def foo():
       x = 20
       def bar():
           global x
           x = 30
       bar()
   foo()
   print(x)
   ```
   a) 10  
   b) 20  
   c) 30  
   d) Error  

8. **Which of the following is a valid variable name in Python?**
   a) `my-variable`  
   b) `my.variable`  
   c) `my@variable`  
   d) `my_variable`  

9. **What will be the result of this operation?**
   ```python
   a = [1, 2, 3]
   a = a + [4]
   a *= 2
   print(a)
   ```
   a) `[1, 2, 3, 4]`  
   b) `[1, 2, 3, 4, 1, 2, 3, 4]`  
   c) `[1, 2, 3, 4, 4]`  
   d) `[1, 2, 3, 4, 8]`  

10. **What will be the output of the following code?**
    ```python
    print(type(3/2))
    ```
    a) `<class 'int'>`  
    b) `<class 'float'>`  
    c) `<class 'str'>`  
    d) `<class 'decimal'>`  

11. **What does the `else` block in a `for` loop do in Python?**
    a) Executes when the loop completes all iterations normally  
    b) Executes when the loop breaks  
    c) Executes after the loop and after the loop terminates  
    d) It is ignored and not executed  

12. **Which of the following will raise an exception in Python?**
    a) `x = [1, 2, 3]`
    b) `x[5]`  
    c) `x[2]`  
    d) `x.append(4)`  

13. **What is the output of this code?**
    ```python
    a = "hello"
    b = "world"
    a, b = b, a
    print(a, b)
    ```
    a) `hello world`  
    b) `world hello`  
    c) `world, hello`  
    d) `world`  

14. **Which operator is used to perform floor division in Python?**
    a) `/`  
    b) `//`  
    c) `%`  
    d) `**`  

15. **What will be the output of this code?**
    ```python
    def foo(*args):
        print(len(args))
    foo(1, 2, 3)
    ```
    a) 3  
    b) 2  
    c) 1  
    d) TypeError  

16. **What is the output of this code?**
    ```python
    lst = [1, 2, 3, 4]
    lst.insert(2, 10)
    print(lst)
    ```
    a) `[1, 2, 10, 3, 4]`  
    b) `[1, 10, 2, 3, 4]`  
    c) `[10, 1, 2, 3, 4]`  
    d) `[1, 2, 3, 4, 10]`  

17. **Which of the following expressions would result in a `SyntaxError`?**
    a) `x = 5`  
    b) `x = 5 +`  
    c) `5 + 3`  
    d) `if x == 5:`  

18. **What is the output of this code?**
    ```python
    x = 'abc'
    y = x[::2]
    print(y)
    ```
    a) `ab`  
    b) `ac`  
    c) `abc`  
    d) `c`  

19. **What is the result of this operation?**
    ```python
    a = "123"
    b = int(a)
    c = str(b)
    print(c)
    ```
    a) `123`  
    b) `int`  
    c) `string`  
    d) `123.0`  

20. **What will be the output of the following code?**
    ```python
    x = {'a': 1, 'b': 2}
    y = {'b': 3, 'c': 4}
    x.update(y)
    print(x)
    ```
    a) `{'a': 1, 'b': 3, 'c': 4}`  
    b) `{'a': 1, 'b': 2, 'c': 4}`  
    c) `{'a': 1, 'b': 2, 'c': 4, 'b': 3}`  
    d) `{'a': 1, 'b': 2, 'c': 4, 'a': 1}`  

## PART B


1. **What is the output of the following code?**
   ```python
   for i in range(3):
       j = 0
       while j < 3:
           print(i, j)
           j += 1
   ```

2. **What is the output of the following code?**
   ```python
   text = "Python Programming"
   result = text.replace('o', '0').upper()
   print(result)
   ```

3. **What is the output of the following code?**
   ```python
   data = "abcdef"
   print(data[2:5])
   ```

4. **What is the output of the following code?**
   ```python
   import math
   print(math.sin(math.pi / 2))
   ```

5. **What is the output of the following code?**
   ```python
   lst = [1, 2, 3, 4, 5]
   i = 0
   while i < len(lst):
       lst[i] *= 2
       i += 1
   print(lst)
   ```

6. **What is the output of the following code?**
   ```python
   d = {'a': 1, 'b': 2, 'c': 3}
   keys = list(d.keys())
   i = 0
   while i < len(keys):
       print(keys[i], d[keys[i]])
       i += 1
   ```

7. **What is the output of the following code?**
   ```python
   x = [2, 3, 5]
   y = [4, 6, 8]
   result = [a * b for a, b in zip(x, y)]
   print(sum(result))
   ```

8. **What is the output of the following code?**
   ```python
   nums = [1, 2, 3, 4]
   print(max([min(nums), 2]))
   ```

9. **What is the output of the following code?**
   ```python
   a = [1, 2, 3]
   b = a.copy()
   b[0] = 100
   print(a, b)
   ```


## PART C

**Question: 1**

---

**The Quest of the Master Scientist Alex**

Alex, the master scientist, has been assigned a critical mission to explore a remote, unknown land where advanced technology and unknown scientific principles are waiting to be uncovered. However, this task is no ordinary one. Alex has to perform several complex operations involving real-time data conversion and calculations for analysis.

1. **Temperature Conversion (Celsius to Fahrenheit)**:
   Alex is monitoring the temperature at different points in this new land, but the readings come in Celsius, and Alex needs them in Fahrenheit to cross-check with the satellite data. However, the temperatures fluctuate every minute, and Alex needs to compute the converted Fahrenheit values in a series of temperature intervals (each interval has different starting points and fluctuations).
   - Alex will receive 5 initial temperatures in Celsius, but these temperatures will change slightly every minute (random fluctuation between -2 and +2 degrees Celsius). The goal is to compute the temperature in Fahrenheit for each reading, taking into account the fluctuation for every minute.

2. **Distance Conversion (Meters to Centimeters)**:
   Alex uses a set of devices that measure distances in meters, but he needs them in centimeters for precise calculations. The distances are not static; they are recorded in intervals across different checkpoints in Alex’s journey, where the interval increases slightly at each point. 
   - Alex will record 5 distances in meters, but for each checkpoint, the distance will increase by a factor that depends on the previous reading. The conversion will also consider the increase in distance, and Alex needs to convert the distances to centimeters (1 meter = 100 centimeters).

3. **Hypotenuse Calculation Using Trigonometry**:
   Alex has to navigate through a challenging terrain with numerous obstacles. To determine the exact route, Alex uses a combination of angles and distances to calculate the shortest path (the hypotenuse) between various points. The calculations involve real-time measurement of adjacent sides and angles at various locations. However, the angles and distances fluctuate slightly due to the topography of the land.
   - Alex is given the length of the adjacent side (in meters) and the angle of elevation (in degrees). Using the trigonometric functions `cos` and `sin`, Alex must calculate the hypotenuse for each measurement while accounting for minor measurement errors that occur due to equipment calibration (random error between 0.5 and 2%).

---

**Your Task:**

Write a Python program to help Alex:

1. **Temperature Conversion**: 
   - Start with 5 initial temperatures in Celsius.
   - For each temperature, randomly fluctuate the value between -2 and +2 degrees Celsius for each reading.
   - Convert each temperature to Fahrenheit and print the results.
   
2. **Distance Conversion**:
   - Start with 5 distances in meters.
   - Each distance will increase by a factor of 1.05 compared to the previous one.
   - Convert each distance to centimeters and print the results.

3. **Hypotenuse Calculation**:
   - For each of 5 data points, calculate the hypotenuse based on the provided adjacent side and angle using trigonometry.
   - Add random fluctuation in the angle (between -2 and +2 degrees) and in the adjacent side (between -0.5 and +0.5 meters) to simulate real-world measurement errors.
   - Use the `math.cos()` and `math.sin()` functions to find the hypotenuse for each case and print the results.

**Hints**:
- Use the `random` library to simulate the fluctuation in temperature, angle, and distance.
- Ensure that you handle angle units properly: `math.cos()` and `math.sin()` expect angles in radians, so you’ll need to convert degrees to radians using the formula:
  \[
  \text{radians} = \text{degrees} \times \frac{\pi}{180}
  \]

---

**Requirements**:
1. Write functions to perform each of these tasks (temperature conversion, distance conversion, hypotenuse calculation).
2. Use loops to iterate over the 5 data points.
3. Make sure the program can handle the random fluctuations and correctly adjust the values.

---


**Question: 2**

---

**The Quest to Unlock the Secrets of Eldoria**

In the legendary city of Eldoria, an ancient civilization has left behind powerful artifacts with magical properties. For centuries, explorers have searched for them, but the coordinates where the artifacts are hidden were written down in an old, faded map. The map is incomplete, and it’s unclear which coordinates are real and which are false. The coordinates are stored in a mysterious list, but Sarah, a brave adventurer and historian, must manually inspect each one to find the true location of these ancient treasures.

Sarah is standing at the foot of an ancient temple, staring at the map’s list of coordinates. The list is long, and although some coordinates seem promising, many are clearly false and lead to empty locations. The task ahead seems daunting: she must carefully examine each coordinate to discover where the true artifacts are buried.

But Sarah is a determined explorer, and she knows that the only way to find the hidden treasures is to **search through every single coordinate one by one** until she uncovers the correct ones. The list contains both real artifact locations and false ones. The only way to know for sure whether a coordinate is valid is to check each one sequentially until she finds all the hidden artifacts.

---

**Your Mission:**

You have been entrusted with a crucial task: help Sarah find the hidden artifacts by implementing a **linear search** algorithm. Your program will help Sarah navigate through the long list of coordinates to discover the locations of the magical artifacts hidden throughout Eldoria.

Here’s how the process will work:

1. Sarah will provide you with a list of coordinates, where each number represents a location.
2. Some coordinates are **valid** locations of hidden artifacts, while others are **false** coordinates that lead to dead ends.
3. Sarah needs your help to search through the list of coordinates and find all the **valid artifact locations**.
4. Your job is to **search through the list sequentially** and find each artifact’s location by checking each coordinate one by one. When a valid artifact is found, return the index (or position) of that artifact in the list.
5. **Your task is to implement a linear search algorithm** to assist Sarah in finding all valid coordinates in the list.

---

### **Example of the Quest**:

Imagine Sarah has the following list of coordinates from the ancient map. In this case, the coordinates `4`, `7`, `5`, `12`, `8`, and `15` are valid artifact locations, and `-1` denotes false coordinates that should be ignored.

```python
coordinates = [4, -1, 7, 5, 12, -1, 8, 15, -1]
```

The program should help Sarah identify and **return the indices** where the valid artifact coordinates are located, allowing her to mark them on the map and continue her adventure.

### **Output**:

For the example list, the output should be the indices of the valid coordinates in the list:
```
Valid coordinates found at indices: [0, 2, 3, 4, 6, 7]
```

Sarah will now know exactly where to search for the artifacts.

---

### **Hints for Success**:

- Use a **linear search** algorithm to examine the list sequentially.
- Keep track of each coordinate as you check it. If it’s a valid artifact location, remember to capture its index.
- The coordinates are stored in a **list**, and the list may contain both positive and negative values. The valid artifact locations are always positive numbers, while `-1` (or any other negative number) indicates a false coordinate.

---

### **Your Objective:**

- Write a Python program that:
  - Takes a list of coordinates as input.
  - Searches through the list one by one.
  - Returns the indices of all the valid artifact coordinates found.

---

**Example of the Task in Action:**

```python
coordinates = [4, -1, 7, 5, 12, -1, 8, 15, -1]
```

Your Python function should return:

```
Valid coordinates found at indices: [0, 2, 3, 4, 6, 7]
```

---

**Deliverables**:
- A Python function called `find_artifact_locations(coordinates)` that performs the linear search and returns the list of indices where valid artifacts are located.

---

**Tricky Story-Based Question:**

---

**The Enigmatic Code of Eldoria: The Matrix Map**

In the heart of Eldoria lies an ancient temple, said to hold secrets and treasures beyond imagination. The only way to unlock these secrets is through an ancient code, hidden deep within the temple's intricate layout. This code, however, is not a simple one. It is buried within a **matrix**, a series of numbers representing different rooms and chambers in the temple. Each room contains a specific artifact or challenge, and the key to understanding the matrix is knowing which rooms contain treasures, which ones are traps, and which ones contain hidden clues to unlock more artifacts.

Sarah, the legendary explorer, has been sent to solve this ancient puzzle. She is holding an encrypted map of the temple, which consists of a matrix of room codes. She has also been given a **dictionary** mapping each room code to the type of room (treasure, trap, clue, or empty) and its security level (low, medium, or high). Some rooms have additional hidden artifacts, and Sarah will need to carefully analyze the matrix and dictionary to uncover them. However, the treasure is not only hidden in rooms with low security, but also in rooms where **certain conditions are met** (e.g., rooms adjacent to traps or rooms that have a combination of treasure and clues).

Sarah must first find all the potential treasures, and then filter them out by their security levels and their relation to adjacent rooms. She must also account for the possibility that clues might lead her to additional treasures.

---

**Your Mission:**

Help Sarah by writing a program that analyzes the matrix of rooms and the dictionary, and returns the coordinates of the most valuable treasures she needs to retrieve. Your program must take into account:

1. **The Matrix Layout**: A matrix that represents rooms in the temple. Each room is represented by a number corresponding to a specific room code.
   
2. **The Room Dictionary**: A dictionary that maps each room code to its **type** (treasure, trap, clue, or empty) and **security level** (low, medium, high). However, some room codes might also have hidden artifacts, depending on their position in the matrix and the presence of adjacent rooms with certain characteristics.

3. **Treasure Identification**:
   - Only **treasure** rooms with **low security** are valuable. However, some treasures may be hidden in **medium security** rooms if adjacent to a **trap** room. The code must identify these treasures based on adjacency rules.
   - **Clue rooms** may reveal hidden treasures in adjacent rooms, even if those rooms would normally be overlooked.

4. **Additional Challenge**:
   - Sarah has learned that some rooms may hide even more treasures if they are adjacent to **trap** rooms, **or** if they are positioned next to **rooms with clues** that have a security level of **medium** or **high**.
   - Your program should also consider the security level of each room when searching for treasures and clues.

### **Example Input:**

Consider the following matrix and dictionary:

**Matrix (rooms in the temple):**
```python
matrix = [
    [101, 200, 102],
    [300, 101, 102],
    [103, 200, 101]
]
```

**Room Dictionary (maps room codes to types and security levels):**
```python
room_info = {
    101: {"type": "treasure", "security": "low"},
    102: {"type": "treasure", "security": "medium"},
    103: {"type": "trap", "security": "high"},
    200: {"type": "empty", "security": "low"},
    300: {"type": "trap", "security": "high"}
}
```

### **Task:**

1. **Find Treasures**: Identify all **treasures** in the matrix with **low security**.
2. **Adjacent Rules**: If a treasure is adjacent to a **trap** room, you need to consider whether it becomes a **hidden artifact** and can be valuable (even if it’s in a room with medium or high security).
3. **Clue Influence**: If a room contains a **clue** and is adjacent to a **treasure room**, the adjacent treasure becomes valuable even if its security level is medium or high.
4. **Return Coordinates**: Return the coordinates of all valuable treasures in the matrix.

### **Example Output:**

For the matrix above, the program should:

- Identify treasures in **low security rooms** (`101` at indices `(0, 0)`, `(1, 1)`, and `(2, 2)`).
- Consider that treasures adjacent to **trap rooms** (`300` at `(1, 0)`, `(2, 0)`) should be considered even if they are medium security.
- Check if any clues influence the treasures.

Thus, the output might look like:

```
The most valuable treasures are located at: [(0, 0), (1, 1), (2, 2), (1, 2)]
```

### **Additional Requirements:**

- **Edge cases**: Handle situations where there are **no treasures**, **no traps**, or **no clues** in the matrix. You may need to filter out rooms based on certain conditions (e.g., if they are not adjacent to a trap or clue).
  
