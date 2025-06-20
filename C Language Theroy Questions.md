
### 🧠 **History of C Language**

1. **Who developed C language?**
   → Dennis Ritchie at Bell Labs in 1972.

2. **Why was C language developed?**
   → To develop the UNIX operating system.

3. **Is C a high-level or low-level language?**
   → C is a middle-level language (mix of high-level + low-level features).

4. **Which language is the base of C?**
   → B Language.

---

### 🔤 **Variables & Data Types**

5. **What is a variable?**
   → A variable stores data that can be changed during program execution.

6. **How to declare a variable in C?**
   → `int a;`, `float b;`, `char c;`

7. **What are the main data types in C?**
   → `int`, `float`, `char`, `double`.

8. **What is the size of `int`, `float`, `char` and `double`?**
   → `int` = 4 bytes, `float` = 4 bytes, `char` = 1 byte, `double` = 8 bytes.

9. **What is a constant?**
   → A value that does not change during program execution (e.g., `#define PI 3.14`).

---

### 🔢 **Operators**

10. **What are operators in C?**
    → Symbols used to perform operations.

11. **Types of operators?**
    → Arithmetic, Relational, Logical, Assignment, Increment/Decrement.

12. **Example of Arithmetic Operators?**
    → `+`, `-`, `*`, `/`, `%`

13. **What is `==` operator?**
    → Compares two values (checks equality).

14. **What is `&&` in C?**
    → Logical AND. Returns true if both conditions are true.

15. **What is `||` in C?**
    → Logical OR. Returns true if at least one condition is true.

16. **What is `!` in C?**
    → Logical NOT. Reverses the condition.

---

### 🔄 **Control Structures**

17. **What are control structures?**
    → They control the flow of program (e.g., `if`, `else`, `switch`, loops).

---

### ❓ **If, Else If, Nested If**

18. **What is `if` statement?**
    → Executes code if the condition is true.

19. **What is `else` statement?**
    → Executes code when the `if` condition is false.

20. **What is `else if`?**
    → Checks multiple conditions one after another.

21. **What is nested `if`?**
    → An `if` inside another `if`.

22. **Example of nested `if`:**
    →

    ```c
    if(a > b) {
       if(a > c) {
          printf("a is max");
       }
    }
    ```

---

### 🔁 **Loops & Types**

23. **What is a loop?**
    → Repeats a block of code multiple times.

24. **Types of loops in C?**
    → `for`, `while`, `do-while`.

25. **When to use `for` loop?**
    → When number of repetitions is known.

26. **Syntax of `for` loop?**
    → `for(i = 0; i < 10; i++) { }`

27. **When to use `while` loop?**
    → When the condition is checked before loop execution.

28. **Syntax of `while` loop?**
    →

    ```c
    while(i < 10) {
       // code
    }
    ```

29. **When to use `do-while` loop?**
    → When the loop must run at least once.

30. **Syntax of `do-while`:**
    →

    ```c
    do {
       // code
    } while(i < 10);
    ```

---

### 📦 **Arrays & 2D Arrays**

31. **What is an array?**
    → A collection of elements of the same type.

32. **How to declare an array?**
    → `int a[5];`

33. **How are array elements accessed?**
    → Using index. `a[0]`, `a[1]`, etc.

34. **What is a 2D array?**
    → Array of arrays. Like a matrix.

35. **Syntax of 2D array?**
    → `int a[3][3];`

36. **How to access 2D array elements?**
    → `a[i][j]`

37. **How to input values in 2D array?**
    → Using nested loops and `scanf`.

---

### 🧮 **Functions**

38. **What is a function?**
    → A reusable block of code.

39. **Types of functions in C?**
    → Library functions (`printf`) and user-defined functions.

40. **Syntax of a function?**
    →

    ```c
    int add(int a, int b) {
       return a + b;
    }
    ```

41. **What is `main()` function?**
    → Starting point of a C program.

---

### 🔁 **Recursion**

42. **What is recursion?**
    → A function calling itself.

43. **Example of recursion?**
    →

    ```c
    int fact(int n) {
       if(n == 0) return 1;
       return n * fact(n - 1);
    }
    ```

44. **Where is recursion used?**
    → In factorial, Fibonacci, tree, etc.

---

### 🧷 **Pointers**

45. **What is a pointer?**
    → A variable that stores address of another variable.

46. **Syntax of pointer declaration?**
    → `int *p;`

47. **What is `&` in C?**
    → Address-of operator.

48. **What is `*` in pointer?**
    → Value at address (dereferencing).

49. **How to assign address to pointer?**
    → `p = &a;`

50. **How to access value using pointer?**
    → `*p`

---

### 🧵 **Strings**

51. **What is a string in C?**
    → A sequence of characters ending with `\0`.

52. **How to declare a string?**
    → `char name[20];`

53. **How to take string input?**
    → Using `gets(name);` or `scanf("%s", name);`

54. **Which header file for string functions?**
    → `<string.h>`

55. **Popular string functions?**
    → `strlen()`, `strcpy()`, `strcmp()`, `strcat()`
