# How to add images to your website?
## Images are one of the most appealing elements in a web page and they play a role in site's visits.
Images can be:
- logos 
- photographs 
- illustration
- diagram
- chart 

## Important thing about images that they should be relevant
## A good practice is to keep your site's images in a single folder
By the time going and your site becoming larger, you may need to add sub-folders in the images folder for more specific images.

### To add an image you use the `<img>` tag (empty tag)
### You need to incule the
- image source 
- alternative 
- title (optional)

`<img src="the-image-path" alt="image-description" title="what-appears-when-one-hover-on-image>`

## How can you adjust images size?

You simply add any of these attributes after the attributes mentioned above, then you put the desired values followed by *px* (pixel).

## When placing images in your website you need to be aware of:
1. image size
2. image format
- > Photographs are best saved as **JPEG**. Illustrations to be **PNG** or **GIF**.
3. image resolution
- > The prefered resolution to use is **72** pixel per inch, therefore it won't take long time to be downloaded.


### The property "align" were used in previous HTML to make a text flow around an image but it's not available in HTML5


# What are the newly added elements to HTML5?

## Images usually have caption associated with them
- To associate a caption with an image use **`<figure>`** tag which holds `<figcaption>` tag and the *`<img>`* tag. You can have more than one image inside the same figure if the caption is relative.

## In this image "The Great Wave" is the caption

![image](https://codex.wordpress.org/images/2/29/image-caption-theme.png)


_________________________________________________

# Color property in CSS3
## Text and backgoround color
## You can pick your favorite color in CSS by:
- RGB values referring to red,green and blue values. They look like rgb(50,20,100).

- HEX values and it's the previous values but it's written like #005558.
- HSLA values referring to hue, saturation, laightness and alpha (opacity).
- - The alpaha property is a number between 0 to 1.0
- Or simply you can use color names.

## For example this 'light green' color would be expressed in three ways:

![](images/Aqua.png)

1. **RGB** values rgb(102,205,170)
- To make this color half transparent, add alpha (*a new value in CSS3*) at last. This would be like **rgba**(102,205,170, 0.5) 

2. **HEX** values #66cdaa

3. **The color name** MediumAquaMarine

# Text in CSS
## What can you change?
- ### Font typeface 
### This can be changed using the property *font-family* and there are a number of font typeface
1. sans-serif *have cleaner look*
- - Arial, Helvatica and Verdan.
2. sans *have extra lines on their strokes*
- - Georgia, Times and Times New Roman.
3. monospace *all letters have the same width*
- - Courier is an example of monospace typeface.
4. Cursive
5. Fantasy

- ### Font weight, color, style 
In order to your site visitor to be able to see the same typeface on the website they need to have the used typeface installed on thier devices.
 
### To ensure that one can see your content you can put multiple typfaces seperated by comma, so if the first one is not on their device they may have one from other typefaces.
## OR 
### You can use **@font-face** which enables the visitors to see your content even if they don't have it on their computers
This enables you to provide path to copy the used font type, so it will be downloaded to the user's computer.

![image](https://www.firststepspublishing.com/wp-content/uploads/2012/03/embed_font_code.jpg)


## Units for specifying your font size
- *pixels* (px)
- *Percentage*
- *the width of the 'm' letter* (ems)

## What are the different font formats?
- ttf/otf
- svg
- woff
- eot

### Why is this?
Because different browsers support different font formats. You need to ensure that any visitor will be able to see your site.

## Other font properties

### Font weight
Use the property *font-weight* to put set your font to either:
- Normal
- **BOLD**
- *italic*
- *obliqu* 
### Text transform 
Use the property *text-transform* to get one of these results:
- lowercase 
- UPPERCASE
- Capitalize 

### Text decoration
By default some tags like `<a>` is underlined. This can be changed using the property *text-decoration*, you can choose upon:
- none
- underline
- overline
- linet-hrough
- blink

## What about links properties?
You can style links in CSS, as you surely noticed the difference between a link that you visited and other links that you didn't click on yet. 

### It's called **Pseudo** (silent P) class
- :link
to style links that are not visited yet
- :visit 
to style links that you already visited

### Other link properties are respond to user's cursor movements
- :hover
- :active
- :focus


![image](https://cdn.splessons.com/wp-content/uploads/2016/09/css-links-1-splessons.png)








 


