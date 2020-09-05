# This is a simple way to look at how web pages are built
## What is behind a website?
**Firstly**, you will know about the languages you will use in order to create a web page and they are:
- HTML5: it's like a building blocks for web pages.
- CSS3 : it's the language we use to style an HTML document.
- JavaScript : here you make your web page more interactive with the user.

**Secondly**, there are a few definitions you need to hear about and they are:
- Tags:
  - which are called also *elements* and they define a specific features to texts and other objects while creating web pages.
- Links: 
  - Also could be called elements but their job is to *bridge* different web page components.
- Attributes:
  - provide additional information about the contents of an element.
- SEO:
  - Which stands for ***search engine optimisation*** which means looking through web pages visitors' eyes and knowing what they are *seeking*.
## What are the tools?
To access the world wide web you have to use a device (e.g. Computer) and this *devise* should have a **web browser** running on it. And one importatnt part will be **web server** which is a special computer that hosts the website. 

### How can a web browser connects you to the right website?
You access the web via an Internet Service Provider **(ISP)**.
Web servers host websites and in order to your browser to get to the right server it will connect to a Domain Name System server **(DNS)**.
The **DNS** will send what is called the *IP* address of the right server to your computer. After your computer connects to the server the server sends the requested web page to your web browser.
![image](https://media.geeksforgeeks.org/wp-content/uploads/20190927155217/webserver.png)

## Why to use HTML?
well, you can't imagine a body or an object without a structure. Here HTML is responsible for web pages structure.
HOW?
An HTML page consists **element** which are made of tags. Those elements tell the browser how to show the content inside them. 

The terms "tag" and "element" are often used interchangeably.

Some elements are called **"empty"** those that don't require a closing tag.
like the `<meta>` tag, which holds information about your page that doesn't appear to the user. 

A heading tag would be like:

- `<h1>` with the closing tag `</h1>`.

Headings go from `<h1>` to `<h6>`.

### Other elements:


- `<div>` element allows you to group a set of elements together
in one block-level box.

- `<span>`it works like an inline synonymous of `<div>`. It's mainly used to add some styles to these elements' content.


### What are the essential tags to build an HTML page?
- `<html></html>` This should iclude all HTML tags in your web page.
- `<head></head>` This contains the `<title></title>`.
- `<title></title>` This contains what your browser will show on the page's tab (at the top of the browser window).
- `<body></body>` This is the container for your web page content.

You can use more than one **`<h1> main heading </h1>`** in your page.

A *paragraph* of text appears between these ` <p> and </p> ` tags.

There could be an *attribure* inside the opening tag which provides extra information about the tag's content. 

Attributes are made up of:

- name: indicates what kind of extra information you are supplying about the element's content.

- value: which should be placed in double quotes.

seperated by an equals sign.

Here is an example of whtat an attriute would look like:

`<p lang="fr">Paragraphe en Français</p>` 
in this attribute the name is(lang) abbreviation of language and the value is *fr* which refers to french.

So this is how browsers can tell in which language this specific element was written.

## There is a declaration that should ANY HTML page begin with:
 `DOCTYPE` which tells the browser the used HTML version.
 In HTML5 it's` <!DOCTYPE html>` 

 Commets are available in HTML. You can use them to give yourself and  the other coders information when they are not certain about some elements. 

` <!-- THIS IS A COMMENT IN HTML PAGE THAT WON'T APPEAR ON THE MAIN BROWSER WINDOW>`

## Every element could be individually styled using **ID**. 

ID attribute allows you to identify a certain element within an HTML page to set a CSS style to it. *It must be different for each element*.
 Its value should start with a letter or an underscore (not a number or any other character).

 The id attribute is known as a **global attribute** because it can be used on any element.

## Another attribute used to style a number of element is **CLASS**

In the opposite of IDs you can use the same class value with many elements. ***BUT*** the appeareance won't change untill there is a CSS rule that indicates it.

You can add more than one class to an element by spacing between the classes names.

## How those element will appear on your browser window:

Some elements by default are called *Block elements*. Each of these elements will start a new line, such as
`<h1>, <p>, <ul>, and <li>.`

*Inline elements*. These are by default will show next to each other, such as `<a>, <b>, <em>, and <img>.` 

## What is new in HTML5 layout? 

well, we can start with the tags itself. Before authors used to use div tags to difine each part of a web page e.g.`<div id='header'>` but in HTML5 the div tags were replaced with a more relative tags.

The `<header>` and the `<footer>` are what appear on the top or the bottom of a web page. Tags like `<article>` and `<section>` can also have its own header and footer tags.


The `<articles>` tag is used to contain what is inside a page.
The `<section>` tag is used to group related content together.
The `<a>` is used to turn a block into a link.

## In order to build an effective website you must know your target audience

- their age range.
- their culture .
- their martial state.
- their living environment.

And then you look at what makes your website appealing. 
you will start with a site map and a wireframe wich can be a sketch on paper. Here you should seek good design elements as to **hierarchy, grouping and organizing**.

Another intiutive design rules should be followed like how approximate your web contents should be to each other and what colors go with your website. In a brief your website should be attractive, interactive and clear so you get more visits.

As mentioned before, to make your site interactive and user friendly you should apply some JavaScript codes *(scripts)*.

## JavaScript
### What is it?
It's the language that a computer understand. 

### Scripts

A script is a series of instructions a computer can follow step-by-step.

### Flowcharts
Once you defined your goal, you will draw a flowchart of the tasks that you want to be followed and implemented by a computer.
![image](https://media.cheggcdn.com/study/5e9/5e907033-f93b-4c56-89be-46ce27eeed5b/11280-2-3RQ-i1.png)

At this stage you will learn to think as a computer, cause they have their thinking rules which are different from mine or yours. 

So your website may perform different tasks in respond to different user actions.
 
 ### In programming you would call things differently
 Any phisycal thing --> Object
 The object charactaristics --> Properties
 Each property has a ***value*** & a ***name***.

For this, every borwser has a JavaScript interpreter to translate your
instructions (in JavaScript) into instructions the computer can follow. 
 
### The main object of any page is the *Document* with holds the HTML, CSS and JavaScript codes.

A rendering engine is responsible for what a borwser displays on the screen.

To let JavaScript (.js) work you have to link it to your (.html) page
- `<script src="the-path-of-the-file-you-created.js"></ script>`

Those scripts are better to be added just before the closing `</body>` tag.










