Download Link: https://assignmentchef.com/product/solved-lab-3-cse110
<br>
<h1>Topics</h1>

<ul>

 <li>Using methods from the String class – Section 2.5</li>

 <li>Using conditional (if, if-else) statements – Chapter 3</li>

</ul>

<h2>Coding Guidelines</h2>

<ul>

 <li>Give identifiers semantic meaning and make them easy to read (examples numStudents, grossPay, etc).</li>

 <li>Keep identifiers to a reasonably short length.</li>

 <li>Use upper case for constants. Use title case (first letter is upper case) for classes. Use lower case with uppercase word separators for all other identifiers (variables, methods, objects).</li>

 <li>Use tabs or spaces to indent code within blocks (code surrounded by braces). This includes classes, methods, and code associated with ifs, switches and loops. Be consistent with the number of spaces or tabs that you use to indent.</li>

 <li>Use white space to make your program more readable.</li>

 <li>Use comments after the ending brace of classes, methods, and blocks to identify to which block it belongs.</li>

</ul>

<h2>Assignment/Lab Documentation</h2>

At the beginning of each programming assignment you must have a comment block with the following information:

/*————————————————————————-

// AUTHOR: your name

// FILENAME: title of the source file

// SPECIFICATION: description of the program

// FOR: CSE 110- Lab #3

// TIME SPENT: how long it took you to complete the assignment

//———————————————————–*/

<h1>Getting Started</h1>

Create a class called Lab3. Use the same setup for setting up your class and main method as you did for the previous assignments. Be sure to name your file Lab3.java.

<h1>Part 1: String Comparison</h1>

In your main method, write a segment of code which will <strong>read in two strings </strong>and <strong>output whether the strings are equal or not</strong>. For example, if both Strings have the value “hello”, the following should be printed:

The strings are the same.

If the strings have different values, for example the first String had “hello” and the second String had “world”, then the following should be printed:

The strings are not the same.

The strings can contain spaces in them, so be sure to use the nextLine() method of the Scanner class to read them in.

Hint: See pg. 90 for information on comparing strings using the String class’s equals method.

Question for thought (You do not have to submit your answer): What happens if instead of using the equals method, you use == to compare two Strings? Change your code and input the same string and see what the output is.

<h1>Part 2: String Length Comparison</h1>

After part 1, write a segment of code which will determine which String has the longer length or if they are the same. For example, if the user entered “hello” and “world” in the first part, the output would be:

The strings have the same length.

If the user entered “Java is fun” and I like to code, then the output should be:

“I like to code” is longer than “Java is fun”

Hints: One possibility is to use an if-else if-else structure given in the following pseudocode:

} test if string 1 is longer than string 2 print the appropriate message

otherwise check if string 2 is longer than string 1 print the appropriate message

otherwise print they have the same length

The length() method will give you the length of a String. The escape sequence ” can be used in a String to print the quotation mark.

<h2>Note</h2>

Labs are not graded by a program, so you do not need to spend a large amount of time making the output match perfectly with the sample below. Do, however, make sure your output is reasonable. The goal here is for you to demonstrate that you understand the underlying concepts.

<h2>Sample Output</h2>

Below is an example of what your output should roughly look like when this lab is completed. All text in bold represents user input.

Sample Run 1:

Enter a string: <strong>hello </strong>Enter another string: <strong>hello </strong>The strings are the same.

The strings have the same length.

Sample Run 2:

Enter a string: <strong>I like programming</strong>

Enter another string: <strong>Java is fun</strong>

The strings are not the same

“I like programming” is longer than “Java is fun”.


