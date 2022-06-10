# 0.2 Intro to Programming in Python

*Estimated Time: 20 minutes*

---

In this section, you’ll learn...

- [What is a program?](0%202%20Intro%20to%20Programming%20in%20Python%2019bba79709544d1bb5d9b21eeddd01c9.md)
- [What is Python?](0%202%20Intro%20to%20Programming%20in%20Python%2019bba79709544d1bb5d9b21eeddd01c9.md)
- [Basic Python](0%202%20Intro%20to%20Programming%20in%20Python%2019bba79709544d1bb5d9b21eeddd01c9.md)

# What is a program?

Everything you do on the computer has a computer program — “software” — behind the scenes.

We write computer programs to help us solve problems or perform tasks, like editing documents, browsing web pages, sharing images, or chatting with friends.

## Translating for machines

Underneath the screens and keyboards, computers are mechanical. They only understand 1s and 0s. But, *people don’t think in 1s and 0s*! When you want something, you use words.

So, how do we tell computers what we want them to do, like “send a message” or “show this webpage”? 

We need a **translator**.

*Programming languages let us write instructions for computers using words*. Those words translate into instructions that the machine understands (1s and 0s). Then, we can type something like “send a message”, and it’ll get translated into something like `00011101001010001 001010010001001 101000010010100 10001010001010100000 01001010010`, which will make the computer send the message.

## A Very Picky Translator

Programming languages are **very picky** about what you type in. You can’t actually type in `send a message` — the programming language wouldn’t understand! Instead, it would be more like `send_message("Hello!")` . The program has to be crafted precisely, with lots of attention to detail, so that the programming language knows *exactly* what you mean.

Programming languages only understand a **few specific words and symbols**, in a **few specific combinations**. Those words, symbols, and combinations are the **vocabulary, grammar and syntax** of a programming language — and that’s what you’ll learn in this course!

# What is Python?

Python is a programming language. You can write Python code, and then it will turn into instructions the computer understands and runs. 

Here’s a small program that prints out 10 copies of the word “Programming”.

```python
message = "Programming"
number_of_copies = 10

print(message * number_of_copies) # ProgrammingProgrammingProgrammingProgrammingProgrammingProgrammingProgrammingProgrammingProgrammingProgramming
```

As you can see:

- It uses words, like `message` and `print` and numbers like `10`
- It uses symbols like `=` , `*`, and `()`
- The words and symbols are arranged in a particular order

## What is python used for?

- Python is a **general purpose programming language**, which means it’s a good fit for a wide variety of problems.
- Python is popular for **data science**, **mathematics**, **web development**, and more. It’s commonly used for “scripting” - small programs to do specific tasks.
- Python is a widely recommended language for beginners. The syntax is not as hard to get started with as some other languages, and you can build cool, real-world projects with it.

# Basic Python

Over the next few weeks, you’ll learn about Python in more detail. These are just a few topics to get you started:

### 1. Print: Showing output from your program

The easiest way to make your program display some result is to use `print`.

Here’s an example:

```python
print("This is the output")
```

The program would output:

`This is the output`

- You use the keyword `print`
- Then parentheses
- Inside the `(  )` you put the the value you want to show
- Text has to go in inside quote marks `" "`

To run code and test our programs, we use an online tool called **Replit**. Below is an example of a Replit code file embedded in the lesson.

Click the green play button ▶️ to run a program and see the output in the Console box.

[https://replit.com/@kibocurriculum/Output-with-print?v=1](https://replit.com/@kibocurriculum/Output-with-print?v=1)

     

<aside>
💡 Try to change the text between the `" "` and run the program again by clicking the green play button. Notice the output in the Console window.

</aside>

## 2. More than one print

If you want more than one line of output, you can use more than one `print`.

```python
print("This is line 1")
print("This is line 2")
print("This is line 3")
```

Which would output:

`This is line 1`
`This is line 2` 
`This is line 3`

Try printing more than one line in the code below.

[https://replit.com/@kibocurriculum/Output-with-print?v=1](https://replit.com/@kibocurriculum/Output-with-print?v=1)

### 3. Variables

You can give a value a name, and use it later, using a variable.

```python
message = "I love programming"
print(message)
print(message)
print(message)
```

`message` is a variable. It stores the value `"I love programming"` . 

The equals sign `=`  assigns the value to the variable.

The program would output:

`I love programming`
`I love programming` 
`I love programming`

Click the green play button ▶️ to run a program and see the output in the Console box.

[https://replit.com/@kibocurriculum/Using-a-variable](https://replit.com/@kibocurriculum/Using-a-variable)

### 4. Adding with `+`

In Python, you can add things together with the `+` operator.

```python
print(10 + 10) # 20
print(10 + 154) # 164
print(12345 + 23456) # 35801
```

Computers are good at arithmetic — they are very fancy calculators.

Python can also add text together with `+`:

```python
message = " loves programming"
print("Adesola" + message)
print("Chidi" + message)
print("Ebbe" + message)
```

The program would output:

`Adesola loves programming`
`Chidi loves programming` 
`Ebbe loves programming`

Click the green play button ▶️ to run a program and see the output in the Console box.

[https://replit.com/@kibocurriculum/Adding-with](https://replit.com/@kibocurriculum/Adding-with)

     

### 5. Input from the user

Python can ask the user to type in a message using `input` .

```python
favorite = input("What is your favorite thing? ")
print("I like " + favorite + " too!")
```

When the program sees `input`, it prints the message and waits for the user to enter their response. Then, it continues from there.

The variable `favorite` stores the value that the user typed in.

If the user typed in `playing soccer`, then the output would look like:

`What is your favorite thing? playing soccer`
`I like playing soccer too!`

When you run this program, be sure to click in the black “Console” box to type a response and press Enter.

[https://replit.com/@kibocurriculum/Input-from-the-user#main.py](https://replit.com/@kibocurriculum/Input-from-the-user#main.py)

## In summary

- Programming languages get translated into 1s and 0s the machine understands
- Python is a beginner-friendly language that has tons of real-world use
- You can make basic programs in Python using `print`, `input`, `+`, and `=`

In the next lesson, we’ll show you more about Replit and how to sign up.

---

<aside>
<img src="man-in-hike.png" alt="man-in-hike.png" width="40px" /> Next up: [Sign Up for Replit](0%203%20Sign%20Up%20for%20Replit%20145cd711691c4db09f413990737af3e6.md)

</aside>