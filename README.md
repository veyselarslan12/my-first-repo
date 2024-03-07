# my-first-repo
The first repo from the first night of class

## Terminal

* cd - change directory
* ls - list all the things in current location
* pwd - print working directory (print current location)
* touch - creates files
* mkdir - make directory   example : mkdir images /  example 2. : mkdir js css / i just made 2 folders
* clear -  clears the terminal

## Git commands

* git status
* git add . 
* git commint -m "my commit message"
* git push -u origin main

## HTML

* HTML headings are defined with the ``` <h1> ``` to ``` <h6> ``` tags.
* HTML paragraphs are defined with the ``` <p> ``` tag.

* HTML links are defined with the ``` <a> ``` tag.
* Example:``` <a href="https://www.w3schools.com">This is a link</a>```
* HTML images are defined with the ``` <img> ```tag.The source file ```(src)```, alternative text ```(alt)```, ```width```, and ```height``` are provided as attributes:
* Example: ```<img src="w3schools.jpg" alt="W3Schools.com" width="104" height="142">```
* The ```<br>``` tag defines a line break, and is an empty element without a closing tag:
* Example: ```<p>This is a <br> paragraph with a line break.</p>```
* HTML formatting
* ```<b>``` - Bold text
* ```<strong> ```- Important text
* ```<i>``` - Italic text
* ```<em> ```- Emphasized text
* ```<mark>``` - Marked text
* ```<small> ```- Smaller text
* ```<del> ```- Deleted text
* ```<ins>``` - Inserted text
* ```<sub>``` - Subscript text
* ```<sup>``` - Superscript text
* HTML comment tag: ```<!-- Write your comments here -->```
* Link target attributes: The target attribute can have one of the following values:

* ```_self``` - Default. Opens the document in the same window/tab as it was clicked
* ```_blank``` - Opens the document in a new window or tab
* ```_parent``` - Opens the document in the parent frame
* ```_top``` - Opens the document in the full body of the window
* Example: ```<a href="https://www.w3schools.com/" target="_blank">Visit W3Schools!</a>```
* Use an image as a link:To use an image as a link, just put the ```<img>``` tag inside the ```<a>``` tag.
* Example: ```<a href="default.asp">```

* ```<img src="smiley.gif" alt="HTML tutorial" style="width:42px;height:42px;">```

* ```</a>```

* Link an Email: ```<a href="mailto:someone@example.com">Send email</a>```

* Button as a link: ```<button onclick="document.location='default.asp'">HTML Tutorial</button>```

* Link titles: ```<a href="https://www.w3schools.com/html/" title="Go to W3Schools HTML section">Visit our HTML Tutorial</a>```

* Unordered HTML list: An unordered list starts with the ```<ul>``` tag. Each list item starts with the ```<li>``` tag. 

* Ordered HTML list: An ordered list starts with the ```<ol>``` tag. Each list item starts with the ```<li>``` tag.

* The HTML ```class``` attribute is used to specify a class for an HTML element.

* The HTML ```id``` attribute is used to specify a unique id for an HTML element.You cannot have more than one element with the same id in an HTML document.

## CSS

* ```#``` id selector
* ```.``` class selector
* ```*``` universal selector selects all HTML elements on the page
* ```<link rel="stylesheet" href="example.css">``` How to connect your CSS file with HTML file.Put this code in your HTML file.
* ``` /* Your comment */ ```  - Comments start with / and end with . If you want to write a multiline comment, add another / at the beginning of each line.
* The ```background-color``` property specifies the background color of an element.
* The ```opacity``` property specifies the opacity/transparency of an element. It can take a value from 0.0 - 1.0. The lower value, the more transparent.
* The ```background-image``` property specifies an image to use as the background of an element. ```body { ```

 ``` background-image: url("paper.gif");```
```}```
* The ```background-position``` property is used to specify the position of the background image.
* The ```background-attachment``` property specifies whether the background image should ```scroll``` or be ```fixed``` (will not scroll with the rest of the page): 

* The ```border-style``` property specifies what kind of border to display.
The following values are allowed:
* ```dotted``` - Defines a dotted border
* ```dashed``` - Defines a dashed border
* ```solid``` - Defines a solid border
* ```double``` - Defines a double border
* ```groove```- Defines a 3D grooved border. The effect depends on the border-color value
* ```ridge``` - Defines a 3D ridged border. The effect depends on the border-color value
* ```inset``` - Defines a 3D inset border. The effect depends on the border-color value
* ```outset``` - Defines a 3D outset border. The effect depends on the border-color value
* ```none``` - Defines no border
* ```hidden``` - Defines a hidden border
* The ```border-style``` property can have from one to four values (for the top border, right border, bottom border, and the left border).
* The ```border-width``` property specifies the width of the four borders.
* The ```border-color``` property is used to set the color of the four borders.
* The ```border-radius``` property is used to add rounded borders to an element.
* The CSS ```margin``` properties are used to create space around elements, outside of any defined borders.

With CSS, you have full control over the margins. There are properties for setting the margin for each side of an element (top, right, bottom, and left).
* The CSS ```padding``` properties are used to generate space around an element's content, inside of any defined borders.

With CSS, you have full control over the padding. There are properties for setting the padding for each side of an element (top, right, bottom, and left).
* The CSS ```width``` property specifies the width of the element's content area. The content area is the portion inside the padding, border, and margin of an element (the box model).

So, if an element has a specified width, the padding added to that element will be added to the total width of the element. This is often an undesirable result.
* The CSS ```height``` and ```width``` properties are used to set the height and width of an element.

The CSS ```max-width``` property is used to set the maximum width of an element.
* Screenshot comes here
* The ```text-align``` property is used to set the horizontal alignment of a text.

A text can be left or right aligned, centered, or justified.
* When the ```text-align``` property is set to ```"justify"```, each line is stretched so that every line has equal width, and the left and right margins are straight (like in magazines and newspapers)
* The ```text-align-last``` property specifies how to align the last line of a text. ```right,left,center and justify```
* The ```text-decoration-line``` property is used to add a decoration line to text.``` overline```,```line-through```,```underline```and```overline underline```.
* The ```text-decoration-color``` property is used to set the color of the decoration line.
* The ```text-decoration-style``` property is used to set the style of the decoration line.```solid```,```double```,```dotted```,```dashed```and```wavy```.
* The ```text-decoration-thickness``` property is used to set the thickness of the decoration line.
* All links in HTML are underlined by default. Sometimes you see that links are styled with no underline. The ```text-decoration: none;``` is used to remove the underline from links, like this:
* The ```text-transform``` property is used to specify uppercase and lowercase letters in a text.

It can be used to turn everything into ```uppercase``` or ```lowercase``` letters, or ```capitalize``` the first letter of each word:
* The ```text-shadow``` property adds shadow to text.

In its simplest use, you only specify the horizontal shadow (2px) and the vertical shadow (2px):
* 
* 
* 
* 
* 
* 
* 
* 
* 
* 
* 
* 
* 
* 
* 







