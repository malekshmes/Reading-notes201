# What is a CSS layout?
It means to control **where** each piece of your web page will appear, and how to make your website more appealing.

## In other words, it's the design of your web page

## How do CSS and HTML treat elements?
Elements are treated as if each element has its own box.

## Two types of (elements) boxes
- Block element: by default this type will take the whole available width of the page, thus it starts always in a new line.
> Examples:
   ` <div>, <p>, <ul>, <li>, <h1> `

### Why to use block elements?
    You use a block element to contain other elements to make it easier for organizing your site parts. Usually a div tag is used to group elements such as images and paragraphs that relate to one secton of your page.

- Inline element: by default, inline elements will show next to each other.
> Examples:  `<span>, <img>, <em>, <b>`

### What is the CSS property?
Simply, it's *position*. When you want to float objects use *float* property.

## The positioning schemes in CSS
1. Normal flow: this will leave elements to their default displaying type.
 - A number of *p* tags will show vertically down each other.

2. Relative positioning: setting this property wont change the normal postion of any object unless you change any of the other properties like *left* *top* *right* and *bottom*. 

 - The object will shift this amount of px **relatively** to its original position.

3. Absolute positioning

 - this will change an element position in relation to its containing element *(its parent)*. Also this make the page render as this element was not exiceted and remove it completly from the flow.

 - when setting an object to **absolute** while its containing object position is set to *relative* then this absolute positioned object will be set ***realtively*** to its containing object *not* to the page. 

 - Setting a *top, left, right, bottom* values will make this element shifts from any of these page sides. So ***top: ;** will **stick** it to the top of the screen wihtout any spaces.



4. Fixed positioning

 - this will cause the *fixed positioned* element to change in relatoin to the browser window and has nothing to do with **parents**. However, these elements will stay in place when you scroll,**IN opposite** to abslute positioning.

 - you set any of these properties like *left* *top* *right* and *bottom*. so to shift that element from your page edges.

 ## How to prevent relatively positioned elements from overlappin?
  use the z-index property **(stacking content)**
  It simply works as '**bring to front**' and '**bring to back**'. The higher the number the more distance on z axis it will travel.

# What are the factors to consider when designing a website?
1. Screen sizes: measured in *inches*. It's the distance from the left lower corner to the upper right corner of the screen **diagonal**.
2. Screen resoulution: the amount of pixles that can be displayed within these physical limits.
3. Page sizes: how many pixles are shown in a page.

### What is Fixed Width Layout?
These designs do not change size as the user increases or decreases their browser size.

- Sometimes this would be helpful.

![image](https://miro.medium.com/max/2160/1*dUZudP2xfPLzMiw5L8ieTQ.gif)



### The liquid layouts tend to use percentage when a user change the browser page size

As goes with designers, web designer use **Grids** to set their page visual elements.

## What is a good practice when working on layout?

web aothurs split their style sheets, they may use one for the layout and another for the fonts or colors.

## How?

1. using `link` element inside the `head` element in your HTML page.
    - `<link rel="stylesheet" type="tables/css" href="css/site.css"/>`
2. in your `stylesheet` can use the (@import) rule to import other style sheets.






