---
layout: project
category: ch2-using-objects
title: Ch2 Method Madness
---
Combine these 3 parts to create one big Method Madness program.

Part 1:

Use Math.min() and Math.max() to create the following. This is a sample transcript of what your program should do. Items in bold are user input and should not be put on the screen by your program.
<pre>
Enter your first number: 15
Enter your second number: 25
25 is larger than 15
</pre>
A second run of the code might give this output:
<pre>
Enter your first number: 99
Enter your second number: 21
99 is larger than 21
</pre>
Part 2:

Your program will determine the correct lexographic ordering (Links to an external site.) of those strings. For this exercise you will need to use the compareTo() String method. Look up the compareTo method in the API docs. This is a sample transcript of what your program should do. Items in bold are user input and should not be put on the screen by your program.
<pre>
Enter the first string: apple
Enter the second string: bananas
apple comes before bananas lexiographically
</pre>
A second run of this code might produce the following output:
<pre>
Enter the first string: bananas
Enter the second string: apple
apple comes before bananas lexiographically
</pre>
Part 3:

Your program will generate two random integers between 1 and 20 and then ask a series of math questions. Each question will be evaluated as to whether it is the right or wrong answer. In the end a final score should be reported for the user. This is a sample transcript of what your program should do. Items in bold are user input and should not be put on the screen by your program.
<pre>
Enter your name: Jeremy
Welcome Jeremy! Please answer the following questions:
4 + 6 = 10
Correct!
4 * 6 = 24
Correct!
4 / 6 = 1
Wrong!
The correct answer is 0
4 % 6 = 4
Correct!
You got 3 correct answers
That's 75.0%!
</pre>
Your code will behave differently based on the random numbers it selects and the answers provided by the user. Here is a second possible execution of this code:
<pre>
Enter your name: Bob
Welcome Bob! Please answer the following questions:
3 + 3 = 0
Wrong!
The correct answer is 6
3 * 3 = 6
Wrong!
The correct answer is 9
3 / 3 = 0
Wrong!
The correct answer is 1
3 % 3 = 1
Wrong!
The correct answer is 0
You got 0 correct answers
That's 0.0%!
</pre>
