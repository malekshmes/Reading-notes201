# Tables in HTML
## tables make it easier to read and understand complex information.
Example of tables:
- Student names for class attendence.
## Tables arrange data into rows and coloumns.
In HTML tables are written row by row.
### What is the element to create a table in **HTML**?
1. `<table>` 
    - This is the main opening tag for any table.
    2. `<tr>` 
        - This indicates the start of any row.
        3. `<td>`
         - Each cell of a row must be inside td tag.


         ![image height=10px](https://www.realmeye.com/forum/uploads/default/original/2X/c/cf367e39bb642ed71b48511cee77d1692ef426c1.png)
### How to put a heading to a table?
`<th>` element is used to set heading for rows and columns. In case the cell is empty you **still** need to use *either* `<th></th>` or `<td></td>`.

### Why to use headings?
1. Helps screen readers.
2. Improve search engines to index your pages.
3. You have better control when styling with CSS.


## Two important attributes
- colspan attribute: is used to indicate how many coloumns a cell can take.
- rowspan attribute: is used to indicate how many rows a cell can take.

### As goes with a general HTML page sructure, long tables should follow this:
`<thead>` tag to contain table headings.
`<tbody>` tag to contain table content.
`<foot>`  tag to contain the footer.

___________________________________________________________

# What is object in JavaScript?
## objects simply have properties and methods
For example:

**car.name = 'BMW';** 

will either assing a name key with the value ***BMW*** to the object *car*, or add this property to the object if it was not existed before.

### The above method is called **'dot declaration'**, another way is by using [square brackets] to set the key.

![image](images/object.png)

## You can delete a value of an object property by either:
- using the delete keyword 
  - delete car.name;

OR
- set the value to empty string
  - car.name ='';

### How to create objects in JavaScript?
- Literal notation
var car = {type:"Fiat", model:"500", color:"white"};

You can create objects using the word **new** when declaring a variable.


## Don't Not Declare Strings, Numbers, and Booleans as Objects!

## Accissing one of the object properties
 ### you can use the name of the object then a period then the property 
 - car.model;
    ### OR
 - car["model"];

## when using function in objects use *this* keyword

## Using this keyword 
For example:

var shape = {

    height : 500,

    width : 200,

    getArea : function (){

        return this.height * this.width;
    }
};

## Here, getArea is called object *Method*

For the above example: *this.height* means the *height* property of **shape** object
You can use instead of **'this'** the object name.

### How to access a method?

*ObjectName.methodNmae();*

## When to use arryas?

The difference between objects and array is that in arrays the order of items is important, as each item has a number ***(index)***.

The same goes to strings values.

The property of any object can hold an array.

## What are the built-in browsers objects and why to use them?

1. **browser object model**

Topmost object it the *window* object. The window's method *print()* will show a dialog box..
other examples are: the screen and the history objects.


2. **Document object model**
The **(DOM)** creates a model of the current web page. The topmost one is **document** object


3. **Global javaScript objects**
JavaScript objects start with a capital letter and they deal with real-world concepts
- Examples :
Date 
Math
toUppercase

## Built-in objects offer a range of tools help you write scripts for web pages.



