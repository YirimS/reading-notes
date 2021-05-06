# list

In HTML there are aseveral different types of list.
 - Ordered List
    - this list uses numbers.

 - Unordered List
    - this list use bullets.

 - Definitions list
    - this list is used to define terminology.

 - Nested List
    -you can put a second list inside a list element to create a aublist.

# Boxes

You can use boxe to contain images and informaation making your page layout more visually pleasing.
you can control the size of the boxes, display and hided boxes, create box models for boarders, margins and padding.  you can control the boarder width, height and style. centering content can be better achieved usingb a box. Controlling the design of your site is all done in CSS. Using CSS you can control the display and visibility.  stylistically you can elyptical shapes and rounded corners. CSS treats each HTML element as if it has it's own box.

# Arrays

An array is a special variable that that stores a list of values. You name arrays just like you would any otheer variableValues are assigned to the array inside of square brackets.

  var colors;
  colors = ['Red', 'Black', 'Green'];

Each ioten in the array is assigned a number starting with zero, called an index.  If you look at the array up above Red = 0, Black = 1, Green = 2. To acces items in the array specify the name and the index number.

  var itemThree;
  itemThree = colors[2];

An array has a property called length which holds all of the items in your array. the name of the array is followed by a period, followed by the length keyword.

  var numColor;
  numColors = colors.length;

To acess the value from an array by specifying the array name and putting the index number in square brackets.

  el.textContent = colors[2];

  if you want to write out all of the items in an array you would have to use a loop

# Decisions and Loops

Using If Else statements provide 2 sets of code. one set if the condition evaluates to true and another set if the condition is false.

if (score >= 25) {
  congratulate();
}

else {
  encoutage();
}

You can also use loops which check conditions. There are three different types of loops.

  * For Lops
    - Used for running code a specific number of times. In for loops the condition is usually a counter which tells how many times a loop should run.

  * While Loops
    - you use a while loop if you are not sure how many times the code should run.  the condition can be something other than a counter.

  * Do while Loops 
    - This loop is very simular to the wwhile loop, the only difference is that they will always run statements in the curly brackets
