# Skim revision for Text of HTML

## HTML elements are used to describe the structure of the page 
 For _e.g_ :

+ headings
+ subheadings 
+ paragraphs


## They also provide semantic information 
For _e.g_ : 
+ Strong & Emphasis
+ Quotations
+ Abbreviations 
+ Citations & Definitions
+ Author Details


# intro to CSS 

> The key to understanding how CSS works is to imagine that there is an invisible box around every HTML element.

- CSS works by associating rules with HTML elements. These rules govern how the content of specified elements should be displayed. A CSS rule contains two parts:
 **a selector and a declaration.**
 _p_ {
 _font-family: Arial;}_

 **p is a selector** _and_ what inside the curly bracet is **declaration** .



_CSS declarations sit inside curly br
ackets and each is made up of two parts: a property and a value, separated by a colon. You can specify several properties in one declaration, each separated by a semi-colon._

**For Example :**

_h1, h2, h3 {_
 _font-family: Arial;_
 _color: yellow;}_





 **_Example of Styles_**

 + Boxes : 

 Width and height, Borders (color, width, and style), Background color and images Position in the browser window.

 + Text :

Size,Color,Italics, bold, uppercase,,lowercase, small-caps etc...


## In additional , CSS rules usually appear in a separate document, although they may appear within an HTML page.
 


# Basic JavaScript Instructions :

## Lets Start With :

1. **Statement :**

A script as we know is a series of instructions that a computer can follow one-by-one.
Each individual instruction or step is known as a **statement**, Statements should end with a **semicolon (;)**.

**"STATEMENTS ARE INSTRUCTIONS AND EACH ONE STARTS ON A NEW LINE & STATEMENTS CAN BE ORGANIZED INTO CODE BLOCKS"**

2. **COMMENTS :**

You should write **comments** to explain what your code does.
They help make your code easier to read and understand.
This can help you and others who read your code. 

3. **VARIABLE :**

A script will have to temporarily
store the bits of information it
needs to do its job. It can store this
data in variables. 

__*How to declare a variable and assign a value?*__

>**Var varName = value ;** 

## RULES FOR NAMING VARIABLES : 
- The name must begin with a letter, dollar sign ($),or an underscore (_). It must not start with a number. 
- The name can contain letters, numbers, dollar sign ($), or an underscore (_). Note that youmust not use a dash(-) or a period (.) in a variable name.
- You cannot use **keywords** or **reserved** words. Keywords are special words that tell the interpreter to do something. For example, var is a keyword used to declare a variable. Reserved words are ones that may be used in a future version of JavaScript.  
- All variables are case sensitive, so score and Score would be different variable names, but it is bad practice to create two variables that have the same name using different cases.
- Use a name that describes the kind of information that the variable stores. For example, first Name might be used to
store a person's first name, lastNarne for their last name, and age for their age 
- If your variable name is made up of more than one word, use a capital letter for the first letter of every word after the first word. For example, f i rstName rather than fi rstnarne (this is referred to as camel case). You can also use an underscore between each word (you cannot use a dash).

4. **Data type :**

- NUMERIC DATA TYPE :
  The numeric data type handles numbers. 

- STRING DATA TYPE :
 The strings data type consists of letters and other characters.

 - BOOLEAN DATA TYPE :
Boolean data types can have one of two values: true or false. 

5. **ARRAYS:**

- An array is a special type of variable. It doesn't just store one value; it stores a list of values. 

- You should consider using an array whenever you are working with a list or a set of values that are related to each other. 

- If you don't know how many items a list will contain, rather than creating enough variables for a long list (when you might only use a small percentage of them), using an array is considered a better solution.

- values in an array are separated by commas. 

__*Create an Array*__

_ex no1_ :
var colors;
colors ['white', 'black', ' custom'];

- create an array and give it a name just like you would any other variable
- The values are assigned to the array inside a pair of square brackets, and each value is separated by a comma .
- The values in the array do not need to be the same data type, so you can store a string, a number and a Boolean all in the same array.
- This technique for creating an array is known as an **array literal**. It is usually the preferred method for creating an array. You can also write each value on a separate line:

colors= ['white',
'black',
'custom'];

_ex no2_ :


var colors = new Array('white ' ,
'black',
'custom');
var el = document.getElementByid( ' colors' );
el.innerHTML = colors.item(O); 

 There is different technique called an **array constructor**. This uses the new keyword followed by Array(); The values are then specified in parentheses (not square brackets), and each value is separated by a comma. 



_Values in an array are accessed as if they are in a numbered list. It is important to know that the numbering of this list starts at zero (not one)_

**NUMBERING ITEMS IN AN ARRAY**

Each item in an array is automatically given a number called an **index.** This can be used to access specific items in the array.

|INDEX |VALUE     |
|------|----------|
|o     |'white '  |
|1     |'bl ack'  |
|2     |' custom' | 


**ACCESSING ITEMS IN AN ARRAY**
To retrieve the third item on the list, the array name is specified along with the index number in square brackets 

_Here you can see a variable_
_called i temThree is declared._
_Its value is set to be the third_
_color from the co 1 ors array._:

var itemThree;
itemThree = colors [2] ;


**NUMBER OF ITEMS IN AN ARRAY**
Each array has a property called length, which holds the number of items in the array.

Below you can see that a variable
called numColors is declared. Its
value is set to be the number of
the items in the array.
The name of the array is
followed by a period symbol (or
full stop) which is then followed
by the length keyword :

var numColors ;
numColors =colors.length;































