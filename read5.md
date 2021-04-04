# Operators and loops 

In Javascript we have something called operators and loops, today I'm going to try to explain them to you my friend in my best understanding and hope that I will not confuse you as they are simple to understand but need a little bit of logic to fully appreciate them.

## 1. Comparison operators

Comparison operators are used in logical statements to determine equality or difference between variables or values.



|Operator     |    Discription|
|:---          |:---           | 
| Equal (==)|Returns true if the operands are equal            |
| Not equal (!=) |Returns true if the operands are not equal.|
| Strict equal (===) |Returns true if the operands are equal and of the same type|
| Strict not equal (!==)|Returns true if the operands are of the same type but not equal, or are of different type.|
|Greater than (>)|Returns true if the left operand is greater than the right operand.|
|Greater than or equal (>=)|Returns true if the left operand is greater than or equal to the right operand.|
| Less than (<)|Returns true if the left operand is less than the right operand.|
|Less than or equal (<=)|Returns true if the left operand is less than or equal to the right operand.|

As the table above shows, 
> A comparison operator compares its operands and returns a logical value based on whether the comparison is true. The operands can be numerical, string, logical, or object values. Strings are compared based on standard lexicographical ordering, using Unicode values. In most cases, if the two operands are not of the same type, JavaScript attempts to convert them to an appropriate type for the comparison. This behavior generally results in comparing the operands numerically. The sole exceptions to type conversion within comparisons involve the === and !== operators, which perform strict equality and inequality comparisons. These operators do not attempt to convert the operands to compatible types before checking equality.

## 2. Logical operators

> Logical operators are typically used with Boolean (logical) values; when they are, they return a Boolean value. However, the && and || operators actually return the value of one of the specified operands, so if these operators are used with non-Boolean values, they may return a non-Boolean value. 

Here are some examples of the three logical operators, how they are described.

[Logical "OR"](https://i.ytimg.com/vi/z8ixkLDNuQw/maxresdefault.jpg)

[Logical "AND"](https://www.devopsschool.com/blog/wp-content/uploads/2020/07/JavaScript-Logical-AND.png)

[Logical "NOT"](https://www.devopsschool.com/blog/wp-content/uploads/2020/07/JavaScript-Logical-NOT.png)


## Now let us talk about loops

loops are a very nice tool to master if you want to run the same code over and over again but with a different value, but you must have a loop breaker depending on the loop condition, otherwise it will keep looping infinitely, for the loop breaker to be achieved we use a tool called loop counter to help us understand how the end user can break the loop and get to the result that the site owner hopes for.

There are three types of loops that we mainly focus on

* For: A for loop repeats until a specified condition evaluates to false

for (statement 1; statement 2; statement 3) {
  // code block to be executed
}

_example_

>for (i = 0; i < 5; i++) {
  text += "The number is " + i + "<br>";
}







* Do While: A do while statement repeats until a specified condition evaluates to false.

do

statement

while (condition);


_exampel_

>let i = 0;
do {
  i += 1;
  console.log(i);
} while (i < 5);


* While: A while statement executes its statements as long as a specified condition evaluates to true

while (condition)

  statement

  _example_

  >llet n = 0;
let x = 0;
while (n < 3) {
  n++;
  x += n;
}




## hope thsese resources that I gathered from ww3 scools and MDN Web Docs, among the explenation that we took from today's lectures help you understand better about the subject matter, thank you for reading.