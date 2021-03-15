# Lists
There are lots of occasions when we need to use lists. HTML provides us with three different types:
*	Ordered lists
*	Unordered lists
*	Definition lists
 
 ### Ordered lists
lists where each item in the list is numbered. For example, the list might be a set of steps for a recipe that must be performed in order, or a legal contract where each point needs to be identified by a section number.
< ol> The ordered list is created with the < ol> element.

###  Unorder lists
re lists that begin with a bullet point (rather than characters that indicate order).
< ul> The unordered list is created with the < ul> element.

### Definition lists
are made up of a set of terms along with the definitions for each of those terms.
< dl> The definition list is created with the < dl> element and usually consists of a series of terms and their definitions. Inside the < dl> element you will usually see pairs of < dt> and < dd> elements.
< dt> This is used to contain the term being defined (the definition term).
< dd> This is used to contain the definition. Sometimes you might see a list where there are two terms used for the same definition or two different definitions for the same term.

### Nested lists 
You can put a second list inside an < li> element to create a sublist or nested list.
< ul>
< li>tea< /li>
< li>Tea
< ul>
   < li>Black tea< /li>
  < li>Green tea< /li>
< /ul>
< /li>
< li>Milk< /li>
< /ul>

### This will result as the following
*	Coffee
*	Tea
*	Black tea
*	Green tea
*	Milk
< li> Each item in the list is placed between an opening < li> tag and a closing < /li> tag. (The li stands for list item.)
### Boxes
when using CSS to style html page it will take each element in the page as a box.
We can set several properties that affect the appearance of these boxes.
*	Control the dimensions of boxes.
*	Create borders around boxes.
*	Set margins and padding for boxes.
*	Show and hide boxes.
### Box Dimensions
#### width, height
By default a box is sized just big enough to hold its contents. To set your own dimensions for a box you can use the height and width properties.
The most popular ways to specify the size of a box are to use pixels, percentages, or ems. Traditionally, pixels have been the most popular method because they allow designers to accurately control their size
## SWITCH STATEMENTS
A switch statement starts with a variable called the switch value. Each case indicates a possible value for this variable and the code that should run if the variable matches that value
    
  ### Why do we need a Switch case?
  There is one potential problem with the if-else statement which is the complexity of the program increases whenever the number of alternative path increases. If you use multiple if-else constructs in the program, a program might become difficult to read and comprehend. Sometimes it may even confuse the developer who himself wrote the program.
  ### The solution to this problem is the switch statement.
  #### Rules for switch statement:
  *	An expression must always execute to a result.
*	Case labels must be constants and unique.
*	Case labels must end with a colon ( : ).
*	A break keyword must be present in each case.
*	There can be only one default label.
*	We can nest multiple switch statements.


