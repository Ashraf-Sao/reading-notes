# Text

## We should always keep in mind that HTML contains tags that are called markup, using these tags give extra meaning and makes the browsers understand what we exactly want to show to the readers

These tags are divided into two categories,

- ### Structural Markup

which is basically the elements that we use describe headings and paragraphs

|   Tag name |  Tag code    | what it does   |
| ---  |  --- | ---|
|   Headings    | < h1> < h2> < h3> < h4> < h5> < h6>    |    it gives a heading to the webpage h1 is the largest to h6 is the smalles|
|     Paragraph |   < p>   |   to create a paragraph just place the text inside it and close the tag < /p > |
|    Bold  |  < b>     |   gives the text a bold format |
|     Italic |   < i>    |   gives the text italic format |
|   Superscript   |  < sup>     | used for text that needs suffixes like rising a number to a power   |
|   Subscript   |   < sub>    |  used for charachters that should be subscript like foot notes   |
|    white space  |   just press space or start new line   |  it is only to make the code easy to read  |
|   Line breaks   |   < br    />    |  used to start a new line inside a paragraph  |
|   Horizontal rules   |   < hr    />     |  it's used to seperate themes with horizontal line  |

*there are many visual editors on the web that you can download or test the code live but keep in mind that their code views might differ from your source code, or might have different shortcuts to style the text that also might not work on your HTML build code*

---

- ### Semantic Markup

These tags are not meant to change the structure of the page but they will add extra information to the page

|    Tag name     |    Tag code     |  What it does    |
| ---   |  ---  | ---|
|    Strong     |     < strong> |   makes the text bold   |
|     Emphasis    |    < em>  |   makes the text italic   |
|     Blockquote    |  < blockquote >  |  used to quote a long paragraph    |
|     Quote    |     < q>  |  used for quoting shorter lines    |
|     Abbreviation    |   < abbr>  |   we use it for abbreviating a word   |
|    Acronym     |     < acronym>  |   we use it for abbreviating multiple words like NASA   |
|    Citation     |    < cite>   |   it is used to to cite where we got the information from  |
|     Definition    |   < dfn>    |    we use it to explain the meaning of a word inside the text  |
|    Address   | < address>|   used for showing the address of the author   |
|    Insert     |    < ins> >  |  we use it to show content that has been inserted    |
|     Delete   |     < del>  |   we use it to show content that has been deleted   |
|     substitue    |     < s>  |   we use iat to show content that has been substituted but still should not be deleted   |

---
---

# Introducing CSS

In this introductory we will answer three simple questions

- What CSS does?

- How CSS works?

- What are the rules, properties and values that we should know?

Before we know what CSS does we should know what it means, **CSS** stands for **Cascading style sheet** which litterally translates to the page of orgnized patterns, and from the name we can deduct what CSS does, that it *orgnises the webpage to our liking and it allows us to to decorate our webpage to our liking without any limitatios*

And for how it works, we must imagine that every element inside the HTML document is trapped within an imaginary box, and from there we can choose to style these boxes via two methods, either as a block or as an inline elements, there are no rules to specify which is used where only rules you need to follow in styling is what the end result you want it to be

nevertheless we must type our commands carefully and pay attention to the tiniest details and respect the CSS properties, in order for it to work flawlessly and as we wish it to be

A CSS rule is made of two parts a selector that indicates which element the rule applies to, and a declaration that indicates how the selected element should be styled using a proprety and a value, yet you can select several properties in one decleration each seperated by a semi-colon

### We also can use external CSS
first we need to link the HTML page with the CSS file using the **(link)** tag with the **(href)** tag and the **(style)** tag

although it is simple but it cannot be this loose and there has to be many selectors and rules to follow carefully

here are some examples for some of the CSS selectors
[CSS Selectors](https://i.pinimg.com/originals/0a/6b/80/0a6b80d7c9c33f6f6f885216a766ebb5.png)

---
---

# Basic JavaScript

- What is a script?

a script is a number of statements that is like a step by step plan to follow, it has very strict instructions

- Why do we use variables?

we use them to store certain information in the script temporarly 

- When should we use arrays?

we use arrays the same way use variables but the main difference is that variables store more than piece of information at once

- can Javascript diffrentiate numbers, texts and values?

yes it can by calling them values like boolean or strings

these were some of the common quistions about Javascript, for a biggener like me Javascript is still vague and unclear but from my read in this chapter I understood that Javascript is like an engine on a car, it is what makes the whole website function and run smoothly
and from googling a little bit about it I understood that it is the number one programming language used in the world and it has really strict rules to follow, yet it is really flexible once you get to understand it

it can contain operators,conditionals, functions, events, image changers

---
---
## Decisions and loops 

"the Ducket was really unhelpful and unclear about this topic so I used google and gathered resourses about this topic from developer.mozilla.org
 w3schools.com and rahultamkhane.medium.com" alonside what I understood from the ducket


> Decision Making in programming is similar to decision making in real life.
    A programming language uses control statements to control the flow of execution of the program based on certain conditions.

JavaScript’s conditional statements are:
  >
  >  1) if statement
    if statement is the most simple decision making statement.
It is used to decide whether a certain statement or block of statements will be executed or not.
If a certain condition is true then a block of statement is executed otherwise not.

> 2) if…else statement
The if-else statement has two parts if block and else block.
If the condition is true then if block (true block) will get executed and if the condition is false then else block (false block) will get executed.

> 3) if…else...if statement
The if…else…if statement statement is an advanced form of if…else that allows JavaScript to make a correct decision out of several conditions.
All the if conditions will be checked one by one. If any condition is true out of given then that block will get executed and other blocks are skipped.

> 4) The objective of a switch statement is to give an expression to evaluate and several different statements to execute based on the value of the expression.
The interpreter checks each case against the value of the expression until a match is found. If nothing matches, a default condition will be used.

###### source = rahultamkhane.medium.com"
---

##  Comparison operators

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


## loops

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
---
---
Thank you for taking the time to read about this with my limited understanding of this subject matter