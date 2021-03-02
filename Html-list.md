Working with HTML Lists
HTML lists are used to present list of information in well formed and semantic way. There are three different types of list in HTML and each one has a specific purpose and meaning.
* Unordered list — Used to create a list of related items, in no particular order.
* Ordered list — Used to create a list of related items, in a specific order.
* Description list — Used to create a list of terms and their descriptions.

Note: Inside a list item you can put text, images, links, line breaks, etc. You can also place an entire list inside a list item to create the nested list.
In the following sections we will cover all the three types of list one by one:
HTML Unordered Lists
An unordered list created using the <ul> element, and each list item starts with the <li> element.
The list items in unordered lists are marked with bullets. Here's an example:



HTML Ordered Lists
An ordered list created using the <ol> element, and each list item starts with the <li> element. Ordered lists are used when the order of the list's items is important.
The list items in an ordered list are marked with numbers. Here's an example:
Example
Try this code »
<ol>
    <li>Fasten your seatbelt</li>
    <li>Starts the car's engine</li>
    <li>Look around and go</li>
</ol>





— The output of the above example will look something like this:
1. Fasten your seatbelt
2. Starts the car's engine
3. Look around and go
The numbering of items in an ordered list typically starts with 1. However, if you want to change that you can use the start attribute, as shown in the following example:
Example
Try this code »
<ol start="10">
    <li>Mix ingredients</li>
    <li>Bake in oven for an hour</li>
    <li>Allow to stand for ten minutes</li>
</ol>





— The output of the above example will look something like this:
10. Mix ingredients
11. Bake in oven for an hour
12. Allow to stand for ten minutes
Like unordered list, you can also use the CSS list-style-type property to change the numbering type in an ordered list. The following style rule changes the marker type to roman numbers.
Example
Try this code »
ol {
    list-style-type: upper-roman;
}

HTML Description Lists
A description list is a list of items with a description or definition of each item.
The description list is created using <dl> element. The <dl> element is used in conjunction with the <dt> element which specify a term, and the <dd> element which specify the term's definition.
Browsers usually render the definition lists by placing the terms and definitions in separate lines, where the term's definitions are slightly indented. Here's an example:
Example
Try this code »
<dl>
    <dt>Bread</dt>
    <dd>A baked food made of flour.</dd>
    <dt>Coffee</dt>
    <dd>A drink made from roasted coffee beans.</dd>
</dl>






— The output of the above example will look something like this:
Bread
A baked food made of flour.
Coffee
A drink made from roasted coffee beans.

