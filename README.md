Download Link: https://assignmentchef.com/product/solved-cse271-lab11-recursivefinder
<br>
For today’s lab you will be doing two exercises pertaining to recursion. The learning objective is to demonstrate your knowledge of recursion by solving two basic problems recursively.  These programs do not require a lot of code, but will require some thought and planning beforehand. So, as always, our advice is to work away from the computer. Design your solutions for each specific level, then trace through variables/method calls. Then go to the computer!

You should be able to finish in class, but have until your respective due dates.  We recommend finishing these early on but well, and then continuing to work on your projects!

Part 1

Write a program, RecursiveFinder, that has a <strong>static</strong> method<strong> <em>int largestElement(int[])</em> .</strong>

In that method, using recursion, find the largest element in an array. You may not use/need any loops or any static variables for finding the largest element. If you need to copy arrays for your solution, consider the <u><a href="https://docs.oracle.com/javase/7/docs/api/java/util/Arrays.html#copyOf(int%5B%5D,%20int)">helper method in the Arrays class for doing so</a> <a href="https://docs.oracle.com/javase/7/docs/api/java/util/Arrays.html#copyOf(int%5B%5D,%20int)">(link here)</a> </u><a href="https://docs.oracle.com/javase/7/docs/api/java/util/Arrays.html#copyOf(int%5B%5D,%20int)">o</a>r you may use a loop to create a new array (but not to determine the answer).

<em>Hint</em>: In each step, find the largest element in the subset containing all but the last element. That is, pull out that last element, and recursively determine the largest element in the remaining set. Then compare the maximum of that recursively derived value to the value of the last element you have extracted. Simplify at each step!  To help design it, you can/should draw it out on paper with an example array.

In the main method of RecursiveFinder, test this method using at least three arrays showcasing that your method can handle different properties like size and order of elements

Part 2)

Write a program, Reverser, that has a static recursive method <sub>String reverse(String text)</sub> that reverses a string.

For example, <sub>reverse(“Hello!”)</sub> returns the string <sub>“!olleH”</sub>. Implement a recursive solution by removing the first character, reversing the remaining text, and combining the two (reversed remaining text + first removed character).

In the main method of Reverser, test this method by using at least three Strings of varying complexity and size.

Feel free to model your code after the examples we did in class.