# Hello and welcome to another read

### Today we will be talking about four important topics

1- Lists

2- Boxes

3- Basic Javascript instructions

4- Switch statements

let's get started

---

## Lists

There are three types of lists in the HTML structure, ordered, unordered and definitions 

* Ordered lists use numbers, to create one we use < ol> element followed by < li> element

* Unordered lists begin with bullet points, to create one we use the < ul> element followed by the < li> element 

* Definition lists have a set terms along with the definition of each term, to create one we use the < dl> element and it has two following element options, the first is the < dt> which is used to contain **term** that is defined, and the < dd> element which is used to contain the **whole definistion**

Lists can be nested and we can use anothe < li> elemnt inside the main < li> element to create a nested list

this sums up everything we need to know about lists

---

## moving on to Boxes 

we talked before about boxes and how the CSS treats each element as if it is inside an imaginary box, in this summary we will be talking about how these to control the dimensions of these boxes 

first thing to play around with is width and height, we can manipulate them as we wish and the best way to manipulate them is using pixeles or percentages, we can also limit them using (min and max properties)

also we can use overflow tools in case the content is bigger than the box with the *hidden* property that tells the browser to hide extra content or by *scroll* which tells to add a scroll bar that allows the user to scroll the page to see extra content

let talk a little bit about border margin and padding 

* border is the the outside of the box, if it's not visible it is there, and to make it visible we can use border-width, or border-style or border-color, as well as adding border images 

* margin is the space between each box border, usually we control margin using margin-auto but we can still also use(margin-top,margin-righ, margin-bottom and margin-left) and we give it a value in pixles

* padding is the space between the border and its content, we can manipulate padding using (padding-top,padding-right, padding-bottom and padding-left) and the value we use is usually is pixeles 

now that we understood the boxes and how they work, let's try to make sense of why are they there, for example they help us to control the location of content on the web page by centering them or moving them left, right, up and down as we wish

we can still also break free of these boxes by changing them to **inline** which means that instead of occuping a box the content will take up an entire line of web page or we vise versa,, we can even hide boxes, the web page will stop the content from appearing to the user but neverthe less it will be there in the source code 


also we can add shadows to these boxes or make their corners round if we chose to make them visible in the first place 

---

## Basic Javascript functions

Arrays: An array is a special type of variable, it stores a list of values. we use this function when we are working on a set values that are relaate dto each other, it is most useful when we don't know how many items a list will contain so an array doesn't specify how many values it will hold 

> var colors;
colors ['red', 'green', 'custom'];

> var el document.getElementByld('colors'); el.textContent =colors[O];

Values in the array are accessed as if they numbers, keeping in  ind that this numbering starts at zero not one, we can as well access and change values in an array item by selecting it and assigning it a new value just as we would any other variable (using the equals sign and the new value for that item).

---

## for the final part, we will now be talking about switch statments

The switch statement is used to perform different actions based on different conditions, it starts with variable called the switch value, using switch statments benift us through having a default option that is run anyway even if none of the cases match, and if the value is matched the *break* statement will break the rest of the statement from running 

Type coercion is
 >When you write an expression, function, etc. (anything with a variable in it really), JavaScript will take the variable you declare and define and do it’s best to figure out what data type seems appropriate to the context. This is called type coercion. For example, if you are performing some nifty string concatenation with a variable like this:
var num = 27;

>JavaScript will actually convert this number into a string because concatenation only applies to string objects.  
Now the reason why this works is because JavaScript does not force your to declare the data type when declaring the variable itself. So this means that in the previous example, the variable “num” has a datatype that is variable in itself. This is an example of a weakly typedlanguage. Like clay, the datatype can be molded to fit the situation. In a strongly typedlanguage, the datatype is set in stone and cannot be molded at all.

###### Source: https://medium.com/


Loops 

there are three common types of loops 

* for loop is used when we need to run a code specific number of times, this has traditionally a counter that we use to tell how many times the loop should run and for that we use loop counters for example see the image below 

[for loop counters](https://images.code.org/b93a044fc07cb4bbabb95b43132a005b-image-1447342829632.png)

 to use a for loop start with the **for** keyword, then contains the condition inside the parentheses as long as the counter is less than the total number of items
in the array, the contents of the curly braces will continue to
run. Each time the loop runs, the round number is increased


* while loop we use this when we don't know how many times the code should run, and it will keep running until the value returns true

* do while loop is used like a while loop but it is inside curly braces at and is run least once 


> LOOPS & ARRAYS Loops are very helpful when dealing with arrays if you want to run the same code for each item in the array.

> If the condition never returns fa1se, you get what is commonly referred to as an infinite loop. The code will not stop running until your browser runs out of memory (breaking your script).
###### source: Javascript Ducket page 175
