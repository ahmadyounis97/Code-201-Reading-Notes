# HTML Links, JS Functions, and Intro to CSS Layout
### Writing Links
Links are created using the <a> element. Users can click on anything 
between the opening < a> tag and the closing < /a> tag. You specify 
which page you want to link to using the href attribute.
 
 > example:  < a href="http://www.imdb.com">IMDB< /a>
#### Linking to Other Sites
Links are created using the <a>
element which has an attribute 
called href. The value of the 
href attribute is the page that 
you want people to go to when 
they click on the link.
Users can click on anything that 
appears between the opening 
 < a> tag and the closing < /a>
tag and will be taken to the page 
specified in the href attribute.
When you link to a different 
website, the value of the href
attribute will be the full web 
address for the site, which is 
known as an absolute URL
   
   
![11](https://user-images.githubusercontent.com/79832772/111380887-9e67d080-86ad-11eb-9758-bf4e8f87a30f.png)
 

   #### Linking to Other Pages on the Same Site:
  
When you are linking to other 
pages within the same site, 
you do not need to specify the 
domain name in the URL. You 
can use a shorthand known as a 
relative URL.
If all the pages of the site are in 
the same folder, then the value 
of the href attribute is just the 
name of the file.

### Relative URLs

Relative URLs can be used when linking to pages within your own 
website. They provide a shorthand way of telling the browser where to 
find your files.

When you are linking to a page 
on your own website, you do 
not need to specify the domain 
name. You can use relative URLs
which are a shorthand way to tell 
the browser where a page is in 
relation to the current page.
This is especially helpful when 
creating a new website or 
learning about HTML because 
you can create links between 
pages when they are only on 
your personal computer (before 
you have got a domain name and 
uploaded them to the web).

#### Opening Links in a New Window
If you want a link to open in a 
new window, you can use the 
target attribute on the opening 
<a> tag. The value of this 
attribute should be _blank.
One of the most common 
reasons a web page author 
might want a link to be opened 
in a new window is if it points to 
another website. In such cases, 
they hope the user will return 
to the window containing their 
site after finishing looking at the 
other one.
  ![12](https://user-images.githubusercontent.com/79832772/111381824-e0454680-86ae-11eb-8b46-2ab3b05716c0.png)
  
#### Linking to a Specific Part of the Same Page
At the top of a long page 
you might want to add a list 
of contents that links to the 
corresponding sections lower 
down. Or you might want to add 
a link from part way down the 
page back to the top of it to save 
users from having to scroll back 
to the top.
Before you can link to a specific 
part of a page, you need to 
identify the points in the page 
that the link will go to. You do 
this using the id attribute (which 
can be used on every HTML 
element). You can see that the 
<h1> and <h2> elements in this 
example have been given id
attributes that identify those 
sections of the page.
The value of the id attribute 
should start with a letter or an 
underscore (not a number or 
any other character) and, on a 
single page, no two id attributes 
should have the same value.
  
  ![13](https://user-images.githubusercontent.com/79832772/111382155-49c55500-86af-11eb-8fb2-3f60d29614c9.png)

#### Linking to a Specific Part of Another Page
f you want to link to a specific 
part of a different page (whether 
on your own site or a different 
website) you can use a similar 
technique.
As long as the page you are 
linking to has id attributes that 
identify specific parts of the 
page, you can simply add the 
same syntax to the end of the 
link for that page.
![14](https://user-images.githubusercontent.com/79832772/111382320-83965b80-86af-11eb-8379-a3422f6a375a.png)

## summary 
* Links are created using the <a> element.
* The <a> element uses the href attribute to indicate 
the page you are linking to.
* If you are linking to a page within your own site, it is 
best to use relative links rather than qualified URLs.
* You can create links to open email programs with an 
email address in the "to" field.
* You can use the id attribute to target elements within 
a page that can be linked to.
  
  ## Key Concepts in Positioning Elements
  #### Controlling the Position of Elements
CSS has the following positioning schemes that allow you to control 
the layout of a page: normal flow, relative positioning, and absolute 
positioning. You specify the positioning scheme using the position
property in CSS. You can also float elements using the float property.
Normal flow
Every block-level element 
appears on a new line, causing 
each item to appear lower down 
the page than the previous one. 
Even if you specify the width 
of the boxes and there is space 
for two elements to sit side-byside, they will not appear next 
to each other. This is the default 
behavior (unless you tell the 
browser to do something else).
Relative Positioning
This moves an element from the 
position it would be in normal 
flow, shifting it to the top, right, 
bottom, or left of where it 
would have been placed. This 
does not affect the position of 
surrounding elements; they stay 
in the position they would be in 
in normal flow.
Absolute positioning
This positions the element 
in relation to its containing 
element. It is taken out of 
normal flow, meaning that it 
does not affect the position 
of any surrounding elements 
(as they simply ignore the 
space it would have taken up). 
Absolutely positioned elements 
move as users scroll up and 
down the page

#### Normal Flow
In normal flow, each block-level 
element sits on top of the next 
one. Since this is the default 
way in which browsers treat 
HTML elements, you do not 
need a CSS property to indicate 
that elements should appear 
in normal flow, but the syntax 
would be:
position: static; 
I have not specified a width
property for the heading 
element, so you can see how it 
stretches the width of the entire 
browser window by default.

#### Absolute Positioning
When the position property 
is given a value of absolute, 
the box is taken out of normal 
flow and no longer affects the 
position of other elements on 
the page. (They act like it is not 
there.) 
The box offset properties (top
or bottom and left or right) 
specify where the element 
should appear in relation to its 
containing element.
In this example, the heading has 
been positioned at the top of the 
page and 500 pixels from its left 
edge. The width of the heading is 
set to be 250 pixels wide.

#### Overlapping Elements
When you use relative, fixed, or 
absolute positioning, boxes can 
overlap. If boxes do overlap, the 
elements that appear later in the 
HTML code sit on top of those 
that are earlier in the page. 
If you want to control which 
element sits on top, you can use 
the z-index property. Its value 
is a number, and the higher the 
number the closer that element 
is to the front. For example, an 
element with a z-index of 10
will appear over the top of one 
with a z-index of 5.
#### Creating Multi-Column Layouts with Floats
Many web pages use multiple 
columns in their design. This 
is achieved by using a <div>
element to represent each 
column. The following three CSS 
properties are used to position 
the columns next to each other: 
width
This sets the width of the 
columns.
float
This positions the columns next 
to each other.
margin
This creates a gap between the 
columns.
A two-column layout like the one 
shown on this page would need 
two <div> elements, one for the 
main content of the page and 
one for the sidebar.
  ![15](https://user-images.githubusercontent.com/79832772/111383210-96f5f680-86b0-11eb-84d8-86927993d65d.png)

### Summary
* <div> elements are often used as containing elements 
to group together sections of a page.
* Browsers display pages in normal flow unless you 
specify relative, absolute, or fixed positioning.
* The float property moves content to the left or right 
of the page and can be used to create multi-column 
layouts. (Floated items require a defined width.)
* Pages can be fixed width or liquid (stretchy) layouts.
* Designers keep pages within 960-1000 pixels wide, 
and indicate what the site is about within the top 600 
pixels (to demonstrate its relevance without scrolling).
* Grids help create professional and flexible designs.
* CSS Frameworks provide rules for common tasks.
* You can include multiple CSS files in one page

## WHAT IS A FUNCTION? 
Functions let you group a series of statements together to perform a 
specific task. If different parts of a script repeat the same task, you can 
reuse the function (rather than repeating the same set of statements).

#### A BASIC FUNCTION 
In this example, the user is 
shown a message at the top of 
the page. The message is held 
in an HTML element whose id 
attribute has a value of message. 
The message is going to be 
changed using JavaScript. 
+:ii.\11 
<!DOCTYPE html> 
<html> 
<head> 
Before the closing </body> 
tag, you can see the link to the 
JavaScript file. The JavaScript 
file starts with a variable used 
to hold a new message, and is 
followed by a function called 
updateMessage(). 
  ![16](https://user-images.githubusercontent.com/79832772/111384068-bfcabb80-86b1-11eb-8a13-e5dc7ceb26a3.png)
#### calling function 
  ![16](https://user-images.githubusercontent.com/79832772/111384450-2d76e780-86b2-11eb-8731-4a8453d7911b.png)

### ANONYMOUS FUNCTIONS & FUNCTION EXPRESSIONS
Expressions produce a value. They can be used where values are expected. 
If a function is placed where a browser expects to see an expression, 
(e.g., as an argument to a function), then it gets treated as an expression. 
#### FUNCTION DECLARATION 
A function declaration creates a function that you 
can call later in your code. It is the type of function 
you have seen so far in this book. 
In order to call the function later in your code, you 
must give it a name, so these are known as named 
functions. Below, a function called area() is 
declared, which can then be called using its name
#### FUNCTION EXPRESSION 
If you put a function where the interpreter would 
expect to see an expression, then it is treated as an 
expression, and it is known as a function expression. 
In function expressions, the name is usually omitted. 
A function with no name is called an anonymous 
function. Below, the function is stored in a variable 
called area. It can be called like any function created 
with a function declaration
#### HOW MEMORY & VARIABLES WORK 
Global variables use more memory. The browser has to remember them 
for as long as the web page using them is loaded. Local variables are only 
remembered during the period of time that a function is being executed. 
* CREATING THE VARIABLES IN CODE 
Each variable that you declare takes up memory. 
The more variables a browser has to remember, 
the more memory your script requires to run. 
Scripts that require a lot of memory can perform 
slower, which in turn makes your web page take 
longer to respond to the user. 

* NAMING COLLISIONS 
You might think you would avoid naming collisions; 
after all you know which variables you are using. 
But many sites use scripts written by several people. 
If an HTML page uses two JavaScript files, and both 
have a global variable with the same name, it can 
cause errors. Imagine a page using these two scripts

#### 6 Reasons for Pair Programming
1. Greater efficiency
It is a common misconception that pair programming takes a lot longer and is less efficient. In reality, when two people focus on the same code base, it is easier to catch mistakes in the making.
2. Engaged collaboration
When two programmers focus on the same code, the experience is more engaging and both programmers are more focused than if they were working alone.
3. Learning from fellow students
Everyone has a different approach to problem solving; working with a teammate can expose developers to techniques they otherwise would not have thought of. If one developer has a unique approach to a specific problem, pair programming exposes the other developer to a new solution.
4. Social skills
Pair programming is great for improving social skills. When working with someone who has a different coding style, communication is key. This can become more difficult when two programmers have different personalities. 
5. Job interview readiness
A common step in many interview processes involves pair programming between a current employee and an applicant, either in person or through a shared screen.
6. Work environment readiness
Many companies that utilize pair programing expect to train fresh hires from CS-degree programs on how they operate to actually deliver a product. Code Fellows graduates who are already familiar with how pairing works can hit the ground running at a new job, with one less hurdle to overcome.
