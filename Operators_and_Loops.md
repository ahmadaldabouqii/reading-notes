# ***Operators And Loops...***

![](https://www.tutsmake.com/wp-content/uploads/2020/05/Loops-In-JavaScript.jpeg)

## ***Operation conditions...***
* == egual to 
* != not equal to
* === strict equal to 
* !=== strict not equal to
* (>) greater than 
* (<) less than 
* (>=) greater than or equal 
* <= less than or equal 

<br>

## ***The summary of Comparison and logical operators...***

1. Comparison operators (===, ! ==, ==, ! =, <, >, <=, =>).
2. are used to compare two operands.
3. Logical operators allow you to combine more than one.
4. set of comparison operators.
5. if ... else statements allow you to run one set of code.
6. if a condition is true, and another if it is false.
7. switch statements allow you to compare a value.
8. against possible outcomes (and also provides a default option if none match).
9. Data types can be coerced from one type to another.
10. All values evaluate to either truthy or falsy.
There are three types of loop: for, while, and do ... while. Each repeats a set of statements.

<br>

##  ***for Loops...***

**for loops have the same purpose as while loops**, but they use a condensed syntax that works well when iterating over arrays and other sequences. A for loop combines variable initialization, a loop condition, and the variable increment/decrement expression all on the same line, The sole difference between the two loops is the scope of any variables declared by the initialization clause. In the while statement, the scope includes the code that surrounds the loop; in the for statement, the scope is the for statement and its body.
example:
var i;
for (i = 0; i < cars.length; i++) {
text += cars[i] + " "; }

<br>

## ***While Loops...***
**A while loop is slightly different than a for loop for the fact that it’s good to use** when we don’t know how many times we want to loop through a problem beforehand. This is the key difference between using a for loop or a while loop. 