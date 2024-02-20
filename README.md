<h1 align="center">Hi 👋, here we have the Rust Projects</h1>
<h3 align="center">Developed these projects in parallel with the optional Rust programming language in the third semester of the faculty.</h3>

---

<h3 align="left">The list of projects:</h3>

1. Evaluator of Mathematical Expressions;
2. Password Generator;
3. ToDo List Generator and Editor;
4. Hang Man Game;
5. File Splitter;

---

<h3 align="left">Installation:</h3>

1. Clone the current repositoy!
2. Change the current directory to the selected project folder..
3. type command: ```cargo r```.


# Evaluator of Mathematical Expressions

<h3 align="left">How does it work?</h3>

- In the Start interface you will see a field for entering the mathematical equation.
- After entering the expression, press the "Calculate" button.
- Wait for the magic to happen! The ``Evaluator of Mathematical Expressions`` will give you the infix expression, the postfix one and not ultimately the result of the inserted expression.
  
-RULES!

- The expression given must contain only digits, linked (no spaces)
- The supported functions and operations are multiplication, division, addition, subtraction.
- Example of expression: 3-8/2*3+6/2-9*5+1

---

<h3 align="left">Structure:</h3>

- Here we have the menu:
![image](https://github.com/AndromedaOMA/Rust-Language---Projects/assets/116078879/201c45a7-3597-4052-bf4d-0767b92e7044)

<h3 align="left">Here are some examples:</h3>

- The first one:
![image](https://github.com/AndromedaOMA/Rust-Language---Projects/assets/116078879/d2fc8d9e-1714-4dc6-99cc-422bb4eb5083)

- The second one:
  
![image](https://github.com/AndromedaOMA/Rust-Language---Projects/assets/116078879/e9c0dc0c-ced3-428e-8343-d7f7f3a845a2)

- The third one:

![image](https://github.com/AndromedaOMA/Rust-Language---Projects/assets/116078879/d6de001a-11bf-44eb-abcb-e5280049c69a)

---

# Password Generator

<h3 align="left">How does it work? -> Here we have the project requirement:</h3>

Write an application that generates and displays on the screen a string representing a password that meets the following conditions:

- It will have a length between 12 and 18 characters.
- It will start with an uppercase letter.
- It will contain alphanumeric characters and at least one symbol from the set ("!", "?", "#", "@").
  
Depending on a parameter given at the command line, the generated password will either be composed of random characters that satisfy the above conditions or be constructed from words in a dictionary saved on disk in a .txt file.

---
<h5>Example input:</h5>

```./pass_gen``` </br>
```./pass_gen --dict dict.txt```

# Hang Man Game

<h3 align="left">How does it work? -> Here we have the project requirement:</h3>

Write an application where the user has to guess a specific word. The words will be read from a dictionary file and will belong to a certain category.

Upon running the application, the user chooses a category, and a random word from the selected category will be chosen. The user can guess one letter at a time. If they guess a letter correctly, the positions of that letter in the word will be displayed. The user is allowed to make a certain number of incorrect letter guesses (depending on the length of the word). During the game, the remaining number of attempts will be displayed.

In the end, the word and the number of unsuccessful attempts will be shown. Words will be saved in specific files for their respective categories. Additionally, scores will be recorded (in a separate file).

---

<h5>Example input:</h5>

```sport```</br>

<h5>Example output:</h5>

```Word: football```</br>
```Incorrect guesses: 2```

---
- ⚡ Fun fact **These are my first projects made using Rust language**
---
