Html & css 


ChoosIng Images for Your sIte
A picture can say a thousand words, and great images help make the difference between an average-looking site and a really engaging one


Images should...
Be relevant
Convey information Convey the right mood Be instantly recognisable Fit the color palette

storing Images on Your site   : If you are building a site from scratch, it is good practice to create a folder for all of the images the site uses.


addIng Images

<img>
To add an image into the page you need to use an <img> element. This is an empty element (which means there is no closing tag). It must carry the following two attributes:
src
This tells the browser where
it can find the image file. This will usually be a relative URL pointing to an image on your own site. (Here you can see that the images are in a child folder called images — relative URLs were covered on pages 83-84).
alt
This provides a text description of the image which describes the image if you cannot see it.
title
You can also use the title attribute with the <img> element to provide additional information about the image. Most browsers will display the content of this attribute in a tootip when the user hovers over the image


Hight and width of images 


* height
This specifies the height of the image in pixels.
* width
This specifies the width of the image in pixels.
Images often take longer to
load than the HTML code that makes up the rest of the page.
It is, therefore, a good idea to specify the size of the image
so that the browser can render the rest of the text on the page while leaving the right amount of space for the image that is still loading.



Where to place Images In Your Code

Where an image is placed
in the code will affect how it is displayed. Here are three examples of image placement that produce different results:
1: before a paragraph
The paragraph starts on a new line after the image.
2: InsIde the start of a paragraph
The first row of text aligns with the bottom of the image.
3: In the mIddle of a paragraph
The image is placed between the words of the paragraph that it appears in.




* Color

The color property allows you to specify the color of text inside an element. You can specify any color in CSS in one of three ways:
rgb values
These express colors in terms of how much red, green and blue are used to make it up. For example: rgb(100,100,90)
hex Codes
These are six-digit codes that represent the amount of red, green and blue in a color, preceded by a pound or hash # sign. For example: #ee3e80
Color names
There are 147 predefined color names that are recognized
by browser 


background-color
CSS treats each HTML element as if it appears in a box, and the background-color property sets the color of the background for that box.
You can specify your choice of background color in the same three ways you can specify foreground colors: RGB values, hex codes, and color names (covered on the next page).
If you do not specify a background color, then the background is transparent.
By default, most browser windows have a white background, but browser users can set a background color for their windows, so if you want
to be sure that the background is white you can use the background-color property on the <body> element.
