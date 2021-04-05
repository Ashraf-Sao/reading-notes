# Design web pages with CSS

### Hello dear reader, in this read everything will be in the for of quistion and answer, to help you get as excited about CSS as much I am, enjoy.

- **What is CSS**

CSS is short for Cascading Styles Sheets which is a way to style and present HTML. Whereas the HTML is the meaning or content, the style sheet is the presentation of that document.

- **How it works?**

> When a browser displays a document, it must combine the document's content with its style information. It processes the document in a number of stages, which we've listed below. Bear in mind that this is a very simplified version of what happens when a browser loads a webpage, and that different browsers will handle the process in different ways. But this is roughly what happens.

>The browser loads the HTML (e.g. receives it from the network).
It converts the HTML into a DOM (Document Object Model). The DOM represents the document in the computer's memory. The DOM is explained in a bit more detail in the next section.
The browser then fetches most of the resources that are linked to by the HTML document, such as embedded images and videos ... and linked CSS! JavaScript is handled a bit later on in the process, and we won't talk about it here to keep things simpler.
The browser parses the fetched CSS, and sorts the different rules by their selector types into different "buckets", e.g. element, class, ID, and so on. Based on the selectors it finds, it works out which rules should be applied to which nodes in the DOM, and attaches style to them as required (this intermediate step is called a render tree).
The render tree is laid out in the structure it should appear in after the rules have been applied to it.
The visual display of the page is shown on the screen (this stage is called painting).
                                        
 ###### *Source: https://developer.mozilla.org/*


 - **What are the rules, properties and values in CSS?**

  1 - Preperties: are used to target what HTML element I want to change or control
  
  2- Rules: the rules in CSS are used to to target one or more element the webpage and must contain a selector and a decleration

  3- Values: CSS rule makes tracing types of values : Integers and real numbers, Lengths, Percentages, URLs and URIs, Counters, Colors, Strings, Unsupported Values possible without the need to target them one by one.

  - **How to specify colors in CSS?**

  There are different ways to select a color in CSS There are several different ways to specify colors in CSS. such as RGB, RGBA, HSL, HSLA, Hexadecimal, each of them has a unique way and work just fine together depending your preference

