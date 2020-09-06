# Working with HTML and CSS
Aside from styling your page with **CSS**, you can use some tags inside your **HTML** file that can apply some changes to your texts.
## Creating paragraphs in HTML
You can create a paragraph as you surround the text with the opening tag `<p>` and the closing tag `</p>`.

Notice that any white space inside a `<p>` tag will be collapsed and won't affect the result when rendering the page. This is called ***'White space collapsing'***

In order to add a line break inside a paragraph you can use the `br />` tag. 

### How to break sections with a horizontal rule?

To achieve this you can use the `<hr  />` tag.
To get a result like <sup>this</sup> in HTML, you can use `<sup>` tag.

But for <sub>this</sub> you can use `<sub>` tag.

### A two `<p>` tags in a row will be treated as if the next paragraph is on a new line.

## What is an example of HTML styling tags?
- `<b>` This tag make texts bold.
- `<i>` This tag make texts italic.
## Another elements that affect the format of your texts
- `<h1>,<h2>,<h3>,<h4>,<h5>,<h6>`
    - These tags make different size headings. Obviously, the h1 tag wil have the largest font size among other h tags and the h6 will have the smallest size.
- `<strong>` This one is used to give a strong importance of what is inside. By default  browsers will show the text inside in bold.
- `<em>` This tag *emphasizes* what is inside it. By default  browsers will show the text in italic.

## different browsers won't show the content of some tags in the same way as other browsers. Here is an example:

`<address>` This tag is used to contain your contact details. Here your text will **often** be shown in *italic*.

There are many other elements that a browser will interpret in a similar way:
`<cite>` for *citation*.
`<dfn>` for the first time mentioned *definitions*. 
`<ins>` this will underline the text, means this text was inserted.
`<del>` this will show a line through the text. `<s>` tag works similarly.
### These are used to give semantic information rather than a styling purposes.

## How CSS styles your sheets?
Well, there are two types of elements:
- **Block elements**: each of these elements will be shown in a new line such as: `<h1>`,`<h6>`, `<p>` and `<div>`.
- **Inline elements**: these elements will show next to each other such as:
   `<b>`, `<i>`,`<img>`, `<em>` and `<span>`.

## In CSS you can modify various types of objects inside your page 
You can add border to your text with a specific width and height.
You can change some texts style and size.
You can add colors to your page.

### CSS follow certain rules in order to apply changes on an HTML page

A basic CSS rule will be like:

            body {background-color: black;
            ^
            |
            This part is called 'Selector' which is responsible for 
            what HTML element this style will affect.

            The part in the braces is called 'Declaration'. This tells
            about the (property and the value) of the styling type.

*in the above rule* the 'background-color' is the ***property*** 
and 'black' is the ***value*** of that declaration.

## What are the ways to style an HTML page?
You can do either:

- EXTERNAL(*Recommended*): this can be done by putting a `<link>` in the head of your HTML page that relates to the CSS file. it needs to be like this:

        `<link href="css/styles.css" type="text/css" rel="stylesheet" />` - This is called an empty tag. Means that it doesn't require a closing tag.

**Of course** you can link more than one CSS file to the same HTML page by adding the links to that sheets in the head.

- INLINE 

- INTERNAL: this can be done by adding a `<style>` in the head of the HTML page.

## CSS selectors:
There are many selectors that you will use when applying styles to your site
 - A **universal selector** is the one that could affect the whole document. To apply this, in CSS file you put * followed by { the-Declaration }
 - A **type selector** where you type only the element type in CSS file before the curly brackets.
 - A **class selector** you write a period then the class name.
 - A **id selector** here you put # before the id name.
## As you go down you will be more specified about what elemnt you would affect

### CSS rules 
1. If two selector are the same, the last one will be executed as it goes line by line when running.
2. The selector's specificity will determine what style should be applied.
3. Importance, you can play with the priority rule by adding !important after the property value followed by semicolon before and the closing bracket.

### CSS versions have evolved with time 
1. CSS1
2. CSS2
3. CSS3 (nowadays version)

***After all it's worth mentioning that every site should be tested on more than one browser before its publishing.***

# In JavaScript you bring life to your web pages

You write a script that computers can follow and one-by-one.

> **A code block** is a group of statements, which are surrounded by curly braces.

A *best practice* in JavaScript is to add comments that explain what your code does. Surround any text with /* and */ for multi-line comments, it won't be displayed to the user.
for single-line comments use // before the text.
 
 ## In JavaScript you will use variables much
 var--->its name; //this is variable declaration

 ## What is a variable?
 It's like a store where you can keep whatever information you want.
 you assign a value to a variable by the assignment operator (=).

 ### JavaScript data types
 - numeric
 - string
 - boolean

*You can create(declare) a variable and assign a value to it at the same line.*

## Variables naming rules
You can not start a variable name with a number
You can not inclue the - or the . inside a vraible name.
Some keywords are reserved and therefor you can not use them.







