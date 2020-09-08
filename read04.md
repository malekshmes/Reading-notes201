# Creating links in HTML

## Type of links in HTML:

- ### Links to another pages within the same site.
- ### Links to another websites.
- ### Links to be opened in a new window.
- ### Links to jump through one page.


## How to create a link in HTML?

### The element used to that is `<a"link-text" >`**Link Description**`</a>`
The link description is the part which *users* can click on, also it will be blue and underlined by defualt.

## Another type of links
The *email link*, this one will open the user's email app and address a specified email address.
The href value starts with **mailto:** followed by the target email address.

## What is URL?
### It stands for Uniform Resource Locator ( the web address ).
The URL is made up of the domain name followed by the path to that page or image.

### The "link-text" (above) will contain the href attribute (The URL)

### There are two types of URLs: 
- Relative: this type is used when you are referring to a page on the same site.
    - In this case you put **only** the page(file) name in the href *href* value
- Absolute: this type is used when you are referring to a different site.

### In HTML you work with many files (pages), thus you need to organize them and keep same file types together
You may have a **folder** for each of this:
1. images
2. stylesheets
3. javaScript files
4. audio files 
and so on.
 
Folders are called **Directories** in HTML and they go like this:

In this image the *index.html* is in the **root folder**. And this is the main page of the website.


![image](https://i.stack.imgur.com/0ityY.png) 

Other folders are called **sub folders**. These folders contain other files and folders related to the same site.

### This is important when you link pages, you need to put the right path for the desired page

Relative link type | Example
------------------ | -------
Same Folder        | `<a href="contact-us">Contact us</a>`
Child Folder       | `<a href="series/comedy.html">Comedy</a>`
Grandchild Folder  | `<a href="games/action/reviews.html>Reviews</a>`
Parent Folder      |   to a higher level folder you use ../ then index.html
Grandparent Folder |   to the same above level you use ../../ then index.html   
       




### For links that open in a new window use    
the attribute *target* with the value _blink.





