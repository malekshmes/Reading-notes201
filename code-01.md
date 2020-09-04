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

A heading tag would be like:

- `<h1>` with the closing tag `</h1>`.

Headings go from `<h1>` to `<h6>`.


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

## There is a declaration that should AN HTML page begin with:
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

Some elements by default are calle *Block elements*. Each of these elements will start a new line, such as
`<h1>, <p>, <ul>, and <li>.`

*Inline elements*. These are by default will show next to each other, such as `<a>, <b>, <em>, and <img>.` 




