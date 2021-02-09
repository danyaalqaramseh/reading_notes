# List in HTMl :


+ _There are three types of HTML lists: ordered, unordered, and definition._
+ _Ordered lists use numbers._
+ _Unordered lists use bullets._
+ _Definition lists are used to define terminology._
+ _Lists can be nested inside one another._

# Boxes in HTML

+ CSS treats each HTML element as if it has its own box.
+ You can use CSS to control the dimensions of a box.
+ You can also control the borders, margin and padding for each box with CSS.
+ It is possible to hide elements using the display and visibility properties.
+ Block-level boxes can be made into inline boxes, and inline boxes made into block-level boxes.
+ Legibility can be improved by controlling the width of boxes containing text and the leading.
+ CSS3 has introduced the ability to create image borders and rounded borders.


# JS reading

 **ARRAYS:**

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



**Switch Statement** 

A switch statement starts with a variable called the switch value. Each case indicates a possible value for this variable and the code that should run if the variable matches that value.

![Switch Statment](https://cdn.javascripttutorial.net/wp-content/uploads/2016/08/JavaScript-switch-case.png) 