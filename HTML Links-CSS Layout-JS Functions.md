Html   ... links 

<a>
Links are created using the <a> element which has an attribute called href. The value of the href attribute is the page that you want people to go to when they click on the link.
Users can click on anything that appears between the opening <a> tag and the closing </a> tag and will be taken to the page specified in the href attribute.
When you link to a different website, the value of the href attribute will be the full web address for the site, which is known as an absolute URL.




Directory structure
On larger websites it's a good idea to organize your code by placing the pages for each different section of the site into a new folder. Folders on a website are sometimes referred to as directories.
structure
The diagram on the right shows the directory structure for a fictional entertainment listings website called ExampleArts.
The top-level folder is known
as the root folder. (In this example, the root folder is called examplearts.) The root folder contains all of the other files and folders for a website.
Each section of the site is placed in a separate folder; this helps organize the files.
If you are working with a content management system, blogging software, or an e-commerce system, you might not have individual files for each page of the website.
reLAtionshiPs
The relationship between files and folders on a website is described using the same terminology as a family tree.
In the diagram on the right, you can see some relationships have been drawn in.
The examplearts folder is a parent of the movies, music and theater folders. And the the movies, music and theater folders are children of the examplearts folder.
Instead, these systems often use one template file for each different type of page (such as news articles, blog posts, or products).
homePAges
The main homepage of a site written in HTML (and the homepages of each section in a child folder) is called index.html.
Web servers are usually set up to return the index.html file if no file name is specified.
Therefore, if you enter examplearts.com it will return examplearts.com/index .html, and examplearts.com/ music will return examplearts .com/music/index.html.



reLAtive urLs
Relative URLs can be used when linking to pages within your own website. They provide a shorthand way of telling the browser where to find your files.


emAiL Links
mailto:
To create a link that starts up
the user's email program and addresses an email to a specified email address, you use the <a> element. However, this time the value of the href attribute starts with mailto: and is followed by the email address you want the email to be sent to.
On the right you can see that an email link looks just like any other link but, when it is clicked on, the user's email program will open a new email message and address it to the person specified in the link


CSS layout 


CSS Building Blocks

Box Model
Every element in HTML is a rectangular box. And each box has a content area, margin area, padding area and border area. This system of margin, padding and borders surrounded by block level elements is known as CSS Box Model.
Margin
The margin property is used to set the margin between an HTML element and its neighbour. Margin property can be given in length, percentage or it can be auto. Auto value means that the browser will automatically set it for you. Margin property cannot be inherited from its parent. Margins can be set for top, right, left and bottom of an element. Full list of margin properties are as follows:
* margin-top - sets the top margin of an element
* margin-right - sets the right margin of an element
* margin-bottom - sets the bottom margin of an element
* margin-left - sets the left margin of an element
* margin - its a shorthand property to set all values


Padding
The padding property is used to set the distance between the border of an element and its content. Padding property can be given in length or percentage. Negative values are not allowed. Paddings can be set for top, right, left and bottom of an element. Full list of padding properties are as follows:
* padding-top - sets the top padding of an element
* padding-right - sets the right padding of an element
* padding-bottom - sets the bottom padding of an element
* padding-left - sets the left padding of an element
* padding - its a shorthand property to set all values



Border
Border property is used to set the border of an HTML element. It can be set around all the sides of an element or can be specific. It can be of different colors, widths and styles. Full list of border properties are as follows:
* border-top - sets the top border of an element
* border-right - sets the right border of an element
* border-bottom - sets the bottom border of an element
* border-left - sets the left border of an element
* border-style - sets the border style of an element.
* Possible values for border-style are none, dotted, dashed, solid, double, groove, ridge, inset and outset
* border-color - sets the border color of an element
* border-width - sets the border width of an element
* border-top-width - sets only the top border width
* border-right-width - sets only the right border width
* border-bottom-width - sets only the bottom border width
* border-left-width - sets only the left border width
* border - its a shorthand property to set all properties
