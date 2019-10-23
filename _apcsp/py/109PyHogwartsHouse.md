---
layout: project
category: py
title: Hogwarts House
---
In this project, you will create a Tkinter app that:
- says "Bravery Score (1-10)"
- has a box for user input
- says "Teamwork Score (1-10)"
- has a box for user input
- has a submit button

Create a function called validNumber, that requires one argument: number. It returns True or False if the number is 1-10.

Create a function called hogwartsHouse that requires two arguments: bravery and teamwork. It *returns* a string.
- Convert bravery from string to number
- Convert teamwork from string to number
- If bravery and teamwork are both above 5 then return "Gryffindor"
- If bravery is 5 or less and teamwork is above 5 then return "Hufflepuff"
- If bravery and teamwork are both 5 or less then return "Ravenclaw"
- If bravery is above 5 and teamwork is 5 or less then return "Slytherin"

| Slytherin  | High Bravery | Gryffindor |
| Low Teamwork | | High Teamwork |
| Ravenclaw | Low Bravery | Hufflepuff |

Copy/paste this starter code: [https://repl.it/@JustinRiley1/Hogwarts-House-starter-code](https://repl.it/@JustinRiley1/Hogwarts-House-starter-code)

The starter code has an event listener function called buttonPressed. This function will:
- collect the user input for bravery
- collect the user input for teamwork
- verify that both user inputs are numbers 1-10
- If either is invalid, popup an error message
- If valid numbers, call the hogwartsHouse function and popup the quiz result


-=-=-=-=-=-=-=-=-=-

GOLD MEDAL CHALLENGE:

Create your own quiz with four (or more) possible outcomes. The result must NOT be random. For example:
- Which My Little Pony are you?
- Which superhero are you?
- Which meme/advice animal are you?
- Which Spongebob character are you?
- Which emoji are you?
- Which princess are you?
- Which season are you?
- Which planet are you?
- Which sport are you?
- Which Starbucks drink are you?
- Which app are you?
- Which sandwich are you?
- Which phone are you?
- Which Pokemon are you?
- What is your spirit animal?
