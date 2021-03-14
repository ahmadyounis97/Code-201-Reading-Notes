#  Basics of HTML, CSS & JS 
## HTML 
HTML has six "levels" of
headings:
* h1 is used for main headings
* h2 is used for subheadings
If there are further sections
under the subheadings then the 
* h3 element is used, and so
on...")

### Paragraphs 

(p)
To create a paragraph, surround
the words that make up the
paragraph with an opening <p>
tag and closing </p> tag.

### Bold & Italic 

By enclosing words in the tags
<(i)> and </(i)> we can make
characters appear italic.
The <i> element also represents
a section of text that would be
said in a different way from
surrounding content — such as
technical terms, names of ships,
foreign words, thoughts, or other
terms that would usually be
italicized.
<b>
### Superscript &Subscrip
  (sup) The (sup) element is used
to contain characters that
should be superscript such
as the suffixes of dates or
mathematical concepts like
raising a number to a power such
as 22
.
(sub)
The (sub) element is used to
contain characters that should
be subscript. It is commonly
used with foot notes or chemical
formulas such as H2


### Line Breaks & Horizontal Rules
(br /)
As you have already seen, the
browser will automatically show
each new paragraph or heading
on a new line. But if you wanted
to add a line break inside the
middle of a paragraph you can
use the line break tag (br /)

<hr />
(hr /)To create a break between
themes — such as a change of
topic in a book or a new scene
in a play — you can add a
horizontal rule between sections
using the (hr /) tag.

## Visual Editors& Their Code views
Content management systems and HTML editors such as Dreamweaver
usually have two views of the page you are creating: a visual editor and a
code view
Visual editors often resemble
word processors. Although
each editor will differ slightly,
there are some features that
are common to most editors
that allow you to control the
presentation of text.

Code views show you the code
created by the visual editor so
you can manually edit it, or so
you can just enter new code
yourself. It is often activated
using a button with an icon
that says HTML or has angled
brackets. White space may be
added to the code by the editor
to make the code easier to read.

###Semantic Markup 
There are some text elements that are not intended to affect the
structure of your web pages, but they do add extra information to the
pages — they are known as semantic markup

### Strong & Emphasis
(strong)
The use of the (strong)
element indicates that its
content has strong importance.
For example, the words
contained in this element might
be said with strong emphasis.
By default, browsers will show
the contents of a(strong)
element in bold

(em)
The (em)
 element indicates
emphasis that subtly changes
the meaning of a sentence.
By default browsers will show
the contents of an (em)

(address) chapter-02/address.html HTML
The (address) element has
quite a specific use: to contain
contact details for the author of
the page.
It can contain a physical address,
but it does not have to. For
example, it may also contain a
phone number or email address
 element
in italic.

## css 
CSS allows you to create rules that control the
way that each individual box (and the contents
of that box) is presented

CSS works by associating rules with HTML elements. These rules govern
how the content of specified elements should be displayed. A CSS rule
contains two parts: a selector and a declaration.
EX :p {
 font-family: Arial;}
 
 Selectors indicate which
element the rule applies to.
The same rule can apply to
more than one element if you
separate the element names
with commas.

CSS declarations sit inside curly brackets and each is made up of two
parts: a property and a value, separated by a colon. You can specify
several properties in one declaration, each separated by a semi-colon.

Properties indicate the aspects
of the element you want to
change. For example, color, font,
width, height and border.
Values specify the settings
you want to use for the chosen
properties. For example, if you
want to specify a color property
then the value is the color you
want the text in these elements
to be


![Untitledcss](https://user-images.githubusercontent.com/79832772/111072218-4466df80-84e2-11eb-986e-d085052d512b.png)


### Using External CSS
<link> chapter-10/using-external-css.html HTML
The <link> element can be used
in an HTML document to tell the
browser where to find the CSS
file used to style the page. It is an
empty element (meaning it does
not need a closing tag), and it
lives inside the <head> element.
It should use three attributes:
href
This specifies the path to the
CSS file (which is often placed in
a folder called css or styles).
type
This attribute specifies the type
of document being linked to. The
value should be text/css
  
  ### Using Internal CSS
You can also include CSS rules
within an HTML page by placing
them inside a <style> element,
which usually sits inside the
<head> element of the page.
The <style> element should use
the type attribute to indicate
that the styles are specified in
CSS. The value should be text/
css. 
  
  ### Why use External Style Sheets?
All of your web pages can share
the same style sheet. This is
achieved by using the <link>
element on each HTML page of
your site to link to the same CSS
document. This means that the
same code does not need to be
repeated in every page (which
results in less code and smaller
HTML pages).

# JS 
A script is a series of instructions that a computer can follow one-by-one.
Each individual instruction or step is known as a statement.
Statements should end with a semicolon. 
### COMMENTS 
You should write comments to explain what your code does.
They help make your code easier to read and understand.
This can help you and others who read your code. 

### WHAT IS A VARIABLE? 
A script will have to temporarily
store the bits of information it
needs to do its job. It can store this
data in variables.
When you write JavaScript, you have to tell the
interpreter every individual step that you want it to
perform. This sometimes involves more detail than
you might expect. 

A variable is a good name for this
concept because the data stored
in a variable can change (or vary)
each time a script runs. 

### DATA TYPES 

* NUMERIC DATA TYPE
The numeric data type handles
numbers. 
* STRING DATA TYPE
The strings data type consists of
letters and other characters.  
* BOOLEAN DATA TYPE
Boolean data types can have one
of two values: true or false.  

USING A VARIABLE TO STORE A NUMBER 
Here, three variables are created
and values are assigned to them.
• price holds the price of an
individual tile
• quantity holds the number
of tiles a customer wants
• to ta 1 holds the total cost of
the tiles
Note that the numbers are not
written inside quotation marks.
Once a value has been assigned
to a variable, you can use the
variable name to represent that
value (much like you might have
done in algebra). Here, the total
cost is calculated by multiplying
the price of a single tile by the
number of tiles the customer
wants. 

1. USING A VARIABLE TO STORE A STRING 
For the moment, concentrate on
the first four lines of JavaScript.
Two variables are declared
(username and message), and
they are used to hold strings (the
user's name and a message for
that user).
c02/js/string-variable.js JAVA SCRIPT
The code to update t he page
(shown in the last four lines)
is discussed fully in Chapter 5.
This code selects two elements
using the values of their id
attributes. The text in those
elements is updated using the
values stored in these variables.
Note how the string is placed
inside quote marks. The quotes
can be single or double quotes,
but they must match. If you start
with a single quote, you must end
with a single quote, and if you
start with a double quote, you
must end with a double quote:

2. USING QUOTES INSIDE A STRING 
Sometimes you will want to use
a double or single quote mark
within a string.
Because strings can live in single
or double quotes, if you just
want to use double quotes in the
string, you could surround the
entire string in single quotes.
If you just want to use single
quotes in the string, you could
surround the string in double
quotes (as shown in the third line
of this code example).

3. USING A VARIABLE TO STORE A BOOLEAN 
4. A Boolean variable can only have
a value of true or fa 1 se, but this
data type is very helpful.
In the example on the right, the
values true or fa 1 se are used
in the cl ass attributes of HTML
elements. These values trigger
different CSS class rules: true
shows a check, fa 1 se shows a
cross. (You learn how the class
attribute is set in Chapter 5.)
It is rare that you would want to
write the words true or false
into the page for the user to read,
but this data type does have two
very popular uses.

### RULES FOR NAMING VARIABLES 

1.The name must begin with
a letter, dollar sign ($),or an
underscore (_). It must not start
with a number.

2.All variables are case sensitive,
so score and Score would be
different variable names, but
it is bad practice to create two
variables that have the same
name using different cases.

3.The name can contain letters,
numbers, dollar sign ($), or an
underscore (_). Note that you
must not use a dash(-) or a
period (.) in a variable name.

4.Use a name that describes the
kind of information that the
variable stores. For example,
fi rstName might be used to
store a person's first name,
l astNarne for their last name,
and age for their age.

5.You cannot use keywords or
reserved words. Keywords
are special words that tell the
interpreter to do something. For
example, var is a keyword used
to declare a variable. Reserved
words are ones that may be used
in a future version of JavaScript.
ONLINE EXTRA
View a full list of keywords and
reserved words in JavaScript.

6.If your variable name is made
up of more than one word, use a
capital letter for the first letter of
every word after the first word.
For example, f i rstName rather
than fi rstnarne (this is referred
to as camel case). You can also
use an underscore between each
word (you cannot use a dash). 
