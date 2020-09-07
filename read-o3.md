# Using lists and boxes in HTML
The tags for creating lists are:
- `<ol>` for ordered lists 
 1. here your itmes will be numbered.
- `<ul>` for unordered lists 
  - here a *bullet* will be added before your items.
## Inside an ordered list or unordered list 
you will use the `<li>` element, which stands for **list item**.

### Your list will be moved slightly to the right by default.

## There is also a definition list
The tag used for this list is 
**`<dl>`** it will usually contain two other elements:
- `<dt>` This to *contain* the term being defined 
- `<dd>` This to *contain* the definition

You can put list inside a list and this is called ***nested lists***.

# What you know about boxes?
We mentioned that CSS will treat each HTML element as it lives inside its own box. Also each box has several properties that you can modify.
1. Border
2. Margin: The margin property controls the gap between boxes.
3. Padding: The padding property is the space between the content and the border.
![image](https://www.avajava.com/tutorials/cascading-style-sheets/how-are-margins-borders-padding-and-content-related/how-are-margins-borders-padding-and-content-related-01.gif)

Borders by default are invisible 
## You can put a certain width and hieght to your boxes, the common used unit is 
- Pixles(px) 

Some times you want to keep on some dimensions of your content as the users' screen are not in one size. In this case you use:

**min-width**, **max-width** to ensure a minimum or maximum width value

**min-height**, **max-height** to ensure a minimum or maximum height value

You can set the border width either of these:
- thin 
- medium
- thick 

OR you can set it with *pixles*.

### You can alter any of the border's side that you want 
`border-width: 2px 1px 1px 2px;`
                top right bottom left
### You can change the border color as well
`border-color`

## Other border properties:

![image](https://i.pinimg.com/originals/41/0b/30/410b30a354bfffe828c542fc120dccfc.png)

## You can hide boxes using:

The **visibility** value--> hidden

## How to align texts in your pages?

use align-text property followed by center,left or right.


# What is an array in JavaScripts?

It's much like a variable but you can store in maultiple values.
*especially* when the values are related to each other.

Arrays creating techniques:
- literal: the values in curly brackets
- constructor: the values in parentheses

## The index value(the number of an array item) enables you to access the desired value. But important the numbers start from 0 not 1




