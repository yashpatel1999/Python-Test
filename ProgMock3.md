Here are 20 tricky multiple-choice questions (MCQs) on Python programming:

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

These questions cover various tricky Python concepts such as lists, loops, functions, data types, and more.
