### Hello again

today's read is going to be dense with information, so lets get going

# Object Literals

an object is a group of a set variables and functions that we can work with in web developement, depending on the use an object can change the way we deal with vriables and functions, for example in an object a variables becomes known as properties and if a function is part of an object it becomes a method

now that we have a clearer definition of what's an object, what is an object literal,

literal notation is the easiest and the most common way to create objects

> The Object literal notation is basically an array of key:value pairs, with a colon separating the keys and values, and a comma after every key:value pair, except for the last, just like a regular array. Values created with anonymous functions are methods of your object. Simple values are properties.

###### source: http://www.standardista.com/

we create object litterals to call out functions in a cleaner way, and inside these object litterals we can manipulate and change variables to our advantage and our best use

we can access it using dot notations or square brackets, see example below

<img src="images/object litterals .png" alt="object litterals">

---
---

# Document Object Model

what is a document object model?
Doccument object model or **DOM** is the way the browser views the HTML and shows it the user while Javascript access and updates the contents of the webpage,

it is not part of the HTML or the Javascript, it's implemented inside the browser

when a browser loads an html page it created a tree for that page and this tree is called **DOM tree**, is made of four of four main types of **nodes** which are *document nodes,
element nodes, attribute nodes, and text nodes.*

[DOM TREE](https://upload.wikimedia.org/wikipedia/commons/thumb/5/5a/DOM-model.svg/1200px-DOM-model.svg.png)

as the image clearly shows how we can understand how the DOM works and interacts with the website' build
first it accesses element, then it access the text, image, links within it,

this method helps us access content faster and makes the webpage appear smoother to the user, creating a tree and nodes within that tree is for sure the best way to make web surfing better

we should keep in mind that there two methods that nodes

1- methods that return one node like **getElementByID** ('id') which selects one element, or **querySelector** ('css selector) and this method returns the first matching element

2- methods that return nodelist such as **getElementByClassName** ('class') this selects one or more elements by its class name, or the **getElementByTagName** ('TagName')and this one selects all the element in the page via the specified tage name, and finally the **querySelectorAll** ('css selector) this uses a css selector syntax and and returns all the elements that match it,

methods to access a single node from a nodelist,
 
* The item method() you specify the index number which will return a single node from the node list , if it finds more than one element it runs the code in the If statement, then stores the first element from the Nodelist and calls it firstItem

* array syntax this method provides faster node selecting process, because it creates a list containing elements and stores it as a nodelist, then if that numbr is greater or equal to one it runs the code inside the if statement then it gets the first element from inside the if statement

 we can repeat actions for an entire nodelist, and apply the same statement to each one,

 Looping through a nodelist

 <img src = "images/Inorder-Traversal.png" alt = "Nodelistloop"/>

 as you can see this loop clealry shows us how the nodelist is accessed in the fastest route possible, the loop starts at one but in the matter of fact in returns from 4 to 2 then 1 and moves to 7, 5, 8, 3, 6 and this by itself is the heart of node in Javascript

 before we talked about finding an element in the DOM tree, now we will talk about how to access element content depending on what the element contains

 there are more than way to access elemnt content

* accessing and updating a text node with *NODEVALUE*

* accessing and changing a text node 

* accessing and updating a text with text content

* accessing text only

there are two ways to add or remove content from and HTML page which are related to the DOM tree that are *InnerHTML* and the *DOM Manipulation*, each has its own proprities,

DOMs give us the freedome to access, manipulate, delete and add elemnts to the DOM tree easily, and with help of modern browsers we can access these DOM trees easily to see how the website works and operates and how the browser interpeted these DOMs and that will help us build better, smoother websites

**comparing techniques when updating HTML content** 

|technique name |   advanteges      |     disadvanteges  |
| ---     |  ---    | ---  |
|document.write()| quick and easy to show how content can be added the page |It only works when the page initially loads.
|element.innerHTML|It can be faster than DOM manipulation when adding a lot of new elements to a web page.|It can be difficult to isolate single elements that you want to update within a larger DOM fragment.
|DOM MANIPULATION|It is suited to changing one element from a DOM fragment where there are many siblings.|If you have to make a lot of changes to the content of a page, it is slower than innerHTML.

 we should wary of cross site scripting (XSS) attacks that happend whem an attacker places melacious code into a site, and this attacks give that attacker access to the DOM, the website coockies, access user acounts and make purchases with that content,

 we can defend against these cross site scripting through validating input going into the server through

 1) Only let visitors input the kind of characters they need to when supplying information

 2) Double-check validation on the server before displaying user content that is stored in a database.

 3) The database may safely contain markup and script
from trusted sources

 4) As your data leaves the database, all potentially dangerous characters should be escaped

 5) Make sure that you are only insertingcontent generated by users

 6) Do not create DOM fragments containing HTMLfrom untrusted sources.

This was my summary of DOM and Object literals, I hope that I was clear and informative, thank you for reading