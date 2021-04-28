# **Part 1. Intro to Javascript**
## **Part 1a. A Quick Introduction**

### **var declaration**

1. What is printed by line 9 is `"values added:", 20`
2. What is printed by line 13 is also `"final result:", 20`

### **let declaration**

3. What is printed by line 9 is `"values added:", 20`
4. What is printed by line 13 is the following **error**: `"<a class='gotoLine' href='#47:31'>47:31</a> Uncaught ReferenceError: result is not defined"` This is expected because on line 5 we defined the variable `result` only *within* its respective block, **not** as a global variable.

### **const declaration**

5. As expected, we get an **error** *before* line 9 can even be executed. The error is the following: `"<a class='gotoLine' href='#44:12'>44:12</a> Uncaught TypeError: Assignment to constant variable."` In short, we get this error because we are assigning to a constant.
6. As expected, we get an **error** *before* line 13 can even be executed. The error is the following: `"<a class='gotoLine' href='#44:12'>44:12</a> Uncaught TypeError: Assignment to constant variable."` In short, we get this error because we are assigning to a constant.

## **Part 1b. A Little More of a Challenge...**
1. What is printed is `3` which makes sense since the iterator variable i is set to global so it is still in memory.
2. What is printed is `150`, which makes sense because that is the final value assigned to `discountedPrice`.
3. Again, what is printed is `150`, which makes sense because that is the final value assigned to `finalPrice`.
4. This function returns an array an int. Specifically, this array is: `[50,100,150]`.
5. There is an **error** as expected because now the variable `i` is *outside* the scope of our print statement.
6. There is an **error** as expected because now the variable `discountedPrice` is *outside* the scope of our print statement.
7. As above, the console prints out `[50,100,150]` as expected because `finalPrice` is *within* the scope of our print statement.
8. The functions returns `[50,100,150]` as expected because the scopes don't *unintentionally* modify the final output.  
9. An **error** as expected because the iterator `i` is outside our scope.
10.  Prints `3` as expected because our input has three elements.
11. The function returns an int array of `[50, 100, 150]`. 

### **Data Types**
12. Refer below...
    
    A. `name.student`
    
    B. `student['Grad Year']`

    C. `student.greeting()`

    D. `student['Favorite Teacher'].name`

    E. `student.courseLoad[0]`

### **Basic Operators & Type Conversion**

13. Arithmetic
    
    A. `"32"` *The final output is converted to a string*

    B. `1` *The final output is registered as an int*

    C. `3` *null is classified as simply zero*

    D. `"3null"` *final output is converted to a string*

    E. `4` *true is converted to one*

    F. `0` *false and null are converted to zero*

    G. `"3undefined"` *undefined is converted to a string*

    H. `NaN` *undefined is not converted so everything is converted to undefined.*

14. Comparison

    A. `true` *'2' is converted to an int*

    B. `false` *both strings converted to int*

    C. `true` *both converted to int*

    D. `false` *have an extra equal sign which checks the datatypes, which in this case, are different*

    E. `false` *true is equal to one*

    F. `true` *both have same values and datatypes*

15. `==` is used for comparing two variables, but it ignores the datatype of variable whereas `===` is used for comparing two variables, but this operator also checks datatype and compares two values.

### **Loops**

16. Refer to the file **part1b-question16.js**

17. It returns an array of ints `[2,4,6]`. Essentially it iterates through the original array and for each element calls the function `doSomething` to get the new value for the new array.

### **setInterval(), setTimeout(), clearTimeout()**

18. Refer to the file **part1b-question18.js**

19. The program prints out...
```angular2html
1
4
3
2
```
