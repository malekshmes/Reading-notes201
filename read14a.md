# What is new in CSS3

## As you know. in CSS many properties can achieve the desired results
## Some of the newly added abilites to CSS3 is object animations
You can change an element behavior or shape or size by using **CSS3 transitions**
### Pseudo-classes
They are classes used to define the state of an element. They target elements that can't be targeted with combinators or simple selectors like id or class.

## Those classes alter an object whenever it's triggered, for example:
- :hover > will change a cursor state when the mouse is over it.

### A regular transition property is____________and it's measured in seconds/mille seconds
~~*transition-duration*~~

### The three required transition properties for any transitoin effect
Transition   | The effect
  -------------      | -------------
  transition-property           | determines what object's related feture to change 
  transition-duration       | the time period that the effect needs to take place
 transition-timing-function | determines how the feature will be styled of affected

 ## What are *vendor perfixes*?
 An added perfixe is used to ensure that a certain browser support the CSS property.

 ### For example : This one is used for ***Chrome***
 `-webkit-transition-property: background;`

#### Why to use *transitions*?
- It will excite your users
- Increase engagement
- Increas your conversions

## Animation
Animation in CSS is associated with_________.
> @key-frames
 - they include:
    - The animation name
    - The animation property
    - Any animation breakpoints


![image](https://i.pinimg.com/originals/58/4b/60/584b607f5c2ff075429dc0e7b8d142ef.gif)


You will specify the direction that the object should go on.
You can set an infinite animation 


## The transform property
It can be used for **positioning** objects or changing its **size**, the transform property comes in two different settings, two-dimensional and three-dimensional.

![image](https://miro.medium.com/max/1108/1*BsBS05gsSDhBt63BYAE-oQ.png)

### The transform above has the value of *skew* with the amount within the parentheses.

### Other transform values:
- Rotate: The negative degrees cause a counterclockwise.
- Scale: The scale could be set to x or y axes
- Perspective

#### Using the *perspective* alongside the *rotate* value will create a 3D rotation effect

## Effects used with Pseudo-classes
> Make sure you set a class for the target element

In this example:

`.fade`

`{`
 ` opacity:0.5;`
`}`

`.fade:hover`

`{`
        `opacity:1;`
`}`

The element in the *fade* class will change opacity whenever the mouse is over it

