---
layout: project
category: ch2usingobjects
title: Method Madness
---
Combine these 3 parts to create one big Method Madness program.

## Part 1:

Use Math.min() and Math.max() to create the following. This is a sample transcript of what your program should do. The numbers 15 and 25 are user input and should not be put on the screen by your program.
```
Enter your first number: 15
Enter your second number: 25
25 is larger than 15
```
A second run of the code might give this output:
```
Enter your first number: 6
Enter your second number: 4
6 is larger than 4
```

## Part 2:

Your program will determine the correct [lexicographic ordering](https://en.wikipedia.org/wiki/Lexicographic_order) of those strings. For this exercise you will need to use the compareTo() String method. Look up the compareTo method in the API docs. This is a sample transcript of what your program should do. The words "apple" and "bananas" are user input and should not be put on the screen by your program.
```
Enter the first string: apple
Enter the second string: bananas
apple comes before bananas lexicographically
```
A second run of this code might produce the following output:
```
Enter the first string: bananas
Enter the second string: apple
apple comes before bananas lexicographically
```

## Part 3:

Your program will use the two numbers from Part 1 and then ask a series of math questions. Each question will be evaluated as to whether it is the right or wrong answer. In the end a final score should be reported for the user. This is a sample transcript of what your program should do. User input always comes after a colon : and should not be put on the screen by your program.
```
Enter your name: Jeremy
Welcome Jeremy! Please answer the following questions...
6 + 4: 1
Wrong!
The correct answer is 10
6 * 4: 24
Correct!
6 / 4: 1
Correct!
6 % 4: 2
Correct!
You got 3 correct answers
That's 75.0%!
```

Your code will behave differently based on the numbers from Part 1 and the answers provided by the user. Here is a second possible execution of this code:
```
Enter your name: Bob
Welcome Bob! Please answer the following questions...
15 + 25: 1
Wrong!
The correct answer is 40
15 * 25: 2
Wrong!
The correct answer is 375
15 / 25: 3
Wrong!
The correct answer is 0
15 % 25: 4
Wrong!
The correct answer is 15
You got 0 correct answers
That's 0.0%!
```

## Expected Output

Here is an example of the expected output that shows all 3 parts together...
```
Enter your first number: 3
Enter your second number: 7
7 is larger than 3
Enter the first string: coconut
Enter the second string: dragonfruit
coconut comes before dragonfruit lexicographically
Enter your name: Amy
Welcome Amy! Please answer the following questions...
3 + 7: 10
Correct!
3 * 7: 22
Wrong!
The correct answer is 21
3 / 7: 2
Wrong!
The correct answer is 0
3 % 7: 0
Wrong!
The correct answer is 3
You got 1 correct answers
That's 25.0%!
```

WHEN FINISHED: On the left side of the Replit editor, click the checkmark icon. Then run the tests. Click the "Results" button to see the difference between the Expected Output and the Actual Output.
