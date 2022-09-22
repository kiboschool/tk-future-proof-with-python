# Admissions challenge - for reference only
---

<aside>

  **Well done on completing the challenge and gaining admission to the program.** This page includes all the lessons you did as part of the challenge, for reference only. You've finished the challenge, so there is nothing more for you to do on this page.

</aside>



## In this lesson, you’ll get:

- an overview of how learning at Kibo works
- instructions to set up the tools you need
- a brief intro to python
- an assignment with tasks to complete

<aside>

</aside>

### Learning with Kibo

Kibo is different from other classes you have been a part of.

- Kibo is an online program. That means that **you’re in charge of your own learning**.
- Learning is **asynchronous:** you go at your own pace.
  - There is a **weekly live class** everyone will attend
  - There are **weekly assignments** everyone will submit.
- Get ready for a challenging journey. You need to **schedule lots of practice time.**
- We love learning to code together. Once the program starts, you’ll **work with partners and groups**.

We want everyone who enrolls in Kibo to be successful. Therefore, before you can fully enroll in the program, we want to check that Kibo-style learning works for you. That’s why we want you to read these pages, set up your tools, and complete the assignment.

### Learning Outcomes

After this Lesson, you will be able to:

- Use **Replit** and **Notion** to learn with Kibo
- Use basic input and output in Python
- Copy, paste, and run code step by step to solve problems

### Challenge Outline

<aside>

  Complete the challenge by following the steps below

</aside>

1. Sign Up for Replit
2. Intro to Programming in Python
3. Assignment
4. Wrap Up

# 1. Sign Up for Replit

## What is Replit?

Replit is an online integrated development environment (IDE). It is the tool that we will use to write, test, and run our programs in this course. Replit is also where you’ll complete practice exercises and projects.

## Sign up for Replit

<aside>

🛠️ **Replit**
Throughout the Try Kibo program, you will write code in Replit. It has everything you need to build and run computer programs in Python

You will use Replit to **practice coding** and to **submit your assignments**.

</aside>

**To create a Replit account:**

- Go to [replit.com](http://replit.com)
- Select "Sign up" on the top right corner, and enter the required information

<aside>

🚨 We need to know who you are! When you sign up for Replit:

1. **Use the email you used to apply to Kibo**
2. Go to your account page [here](https://replit.com/account) and add your first and last name

</aside>

## Replit Tutorial Video

<aside>

Watch this video for a brief introduction on how to use Replit

</aside>

<div style="position: relative; padding-bottom: 56.25%; height: 0;"><iframe src="https://www.loom.com/embed/4787fd806c6541ad84c4f232e37de33a" frameborder="0" webkitallowfullscreen mozallowfullscreen allowfullscreen style="position: absolute; top: 0; left: 0; width: 100%; height: 100%;"></iframe></div>


# 2. Intro to Programming in Python

In this section, you’ll learn...

- What is a program?
- What is Python?
- Basic Python

<aside>

⚠️ You’ll see all this material again in Week 1 of the class — you don’t need to memorize it now. Think of it as a preview of what the course will be like.

</aside>

## What is a program?

Everything you do on the computer has a computer program — “software” — behind the scenes.

We write computer programs to help us solve problems or perform tasks, like editing documents, browsing web pages, sharing images, or chatting with friends.

### Translating for machines

Underneath the screens and keyboards, computers are mechanical. They only understand 1s and 0s. But, *people don’t think in 1s and 0s*! When you want something, you use words.

So, how do we tell computers what we want them to do, like “send a message” or “show this webpage”?

We need a **translator**.

*Programming languages let us write instructions for computers using words*. Those words translate into instructions that the machine understands (1s and 0s). Then, we can type something like “send a message”, and it’ll get translated into something like `00011101001010001 001010010001001 101000010010100 10001010001010100000 01001010010`, which will make the computer send the message.

### A Very Picky Translator

Programming languages are **very picky** about what you type in. You can’t actually type in `send a message` — the programming language wouldn’t understand! Instead, it would be more like `send_message("Hello!")` . The program has to be crafted precisely, with lots of attention to detail, so that the programming language knows *exactly* what you mean.

Programming languages only understand a **few specific words and symbols**, in a **few specific combinations**. Those words, symbols, and combinations are the **vocabulary, grammar and syntax** of a programming language — and that’s what you’ll learn in this course!

## What is Python?

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

### What is python used for?

- Python is a **general purpose programming language**, which means it’s a good fit for a wide variety of problems.
- Python is popular for **data science**, **mathematics**, **web development**, and more. It’s commonly used for “scripting” - small programs to do specific tasks.
- Python is a widely recommended language for beginners. The syntax is not as hard to get started with as some other languages, and you can build cool, real-world projects with it.

## Basic Python

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
- Inside the `(  )` you put the value you want to show
- Text has to go in inside quote marks `" "`

To run code and test our programs, we use **Replit**. Below is an example of a Replit code file embedded in the lesson.

Click the green ▶️  button to run a program and see the output in the Console box.

*Note: if the embedded code below doesn’t work, you can click this link to go directly to the repl: [https://replit.com/@kibocurriculum/Output-with-print](https://replit.com/@kibocurriculum/Output-with-print)*

<div style="position: relative; padding-bottom: 56.25%; height: 0;"><iframe src="https://replit.com/@kibocurriculum/Output-with-print?lite=true" frameborder="0" webkitallowfullscreen mozallowfullscreen allowfullscreen style="position: absolute; top: 0; left: 0; width: 100%; height: 100%;"></iframe></div>


<aside>

💡 Try to change the text between the `" "` and run the program again by clicking the green 'Run' button. Notice the output in the Console window.

</aside>

### 2. More than one print

If you want more than one line of output, you can use more than one `print`.

```python
print("This is line 1")
print("This is line 2")
print("This is line 3")
```

Which would output:

```text
This is line 1
This is line 2
This is line 3
```

Try editing the code below to print more than one line.

<div style="position: relative; padding-bottom: 56.25%; height: 0;"><iframe src="https://replit.com/@kibocurriculum/Output-with-print?lite=true" frameborder="0" webkitallowfullscreen mozallowfullscreen allowfullscreen style="position: absolute; top: 0; left: 0; width: 100%; height: 100%;"></iframe></div>

### 3. Variables

You can give a value a name, and use it later, using a variable.

```python
message = "I love programming"
print(message)
print(message)
print(message)
```

`message` is a variable. It stores the value `"I love programming"`.

The equals sign `=`  assigns the value to the variable.

The program would output:

```text
I love programming
I love programming
I love programming
```

Click the green ▶️ button  to run the program and see the output in the Console box.

*Note: if the embedded code below doesn’t work, you can click this link to go directly to the repl: [https://replit.com/@kibocurriculum/Using-a-variable](https://replit.com/@kibocurriculum/Using-a-variable)*

<div style="position: relative; padding-bottom: 56.25%; height: 0;"><iframe src="https://replit.com/@kibocurriculum/Using-a-variable?lite=true" frameborder="0" webkitallowfullscreen mozallowfullscreen allowfullscreen style="position: absolute; top: 0; left: 0; width: 100%; height: 100%;"></iframe></div>

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

Click the green ▶️  button to run a program and see the output in the Console box.

*Note: if the embedded code below doesn’t work, you can click this link to go directly to the repl: [https://replit.com/@kibocurriculum/Adding-with](https://replit.com/@kibocurriculum/Adding-with)*

<div style="position: relative; padding-bottom: 56.25%; height: 0;"><iframe src="https://replit.com/@kibocurriculum/Adding-with?lite=true" frameborder="0" webkitallowfullscreen mozallowfullscreen allowfullscreen style="position: absolute; top: 0; left: 0; width: 100%; height: 100%;"></iframe></div>

### 5. Input from the user

Python can ask the user to type in a message using `input`.

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

*Note: if the embedded code below doesn’t work, you can click this link to go directly to the repl: [https://replit.com/@kibocurriculum/Input-from-the-user#main.py](https://replit.com/@kibocurriculum/Input-from-the-user#main.py)*

<div style="position: relative; padding-bottom: 56.25%; height: 0;"><iframe src="https://replit.com/@kibocurriculum/Input-from-the-user?lite=true" frameborder="0" webkitallowfullscreen mozallowfullscreen allowfullscreen style="position: absolute; top: 0; left: 0; width: 100%; height: 100%;"></iframe></div>

## In summary

- Programming languages get translated into 1s and 0s the machine understands
- Python is a beginner-friendly language that has tons of real-world use
- You can make basic programs in Python using `print`, `input`, `+`, and `=`

# 3. Assignment

Complete these challenges in Replit. You’ll practice using input and output in Python, and you’ll learn how assignments in Replit will work.

<aside>

⚠️ **You must submit the two Replit assignments** below to gain admission to the program.

</aside>

## Task 1: Hello, World

Traditionally, the first program you write in a new language is a program that says “Hello, World!”.

Click the link below to access the assignment in Replit, then follow the directions in the **Instructions** tab.

<aside>

➡️ **Access** and **submit** the task in Replit here: [https://replit.com/team/challenge-fpwp6/1-hello-world](https://replit.com/team/challenge-fpwp6/1-hello-world)

</aside>

## Task 2: Decrypt Me

Encryption and decryption play an important role in information security and computer science. It’s used everywhere to secure the transmitted data between two entities. In this exercise, we have a sample program that decrypts secret messages. In this task, you will follow some steps to decrypt a secret message.

Click the link below to access the assignment in Replit, then follow the directions in the **Instructions** tab.

<aside>

➡️ **Access** and **submit** the task in Replit here: [https://replit.com/team/challenge-fpwp6/Decrypt-me](https://replit.com/team/challenge-fpwp6/Decrypt-me)

</aside>

<details><summary><strong>If you get stuck, click here.</strong></summary>

Watch this video to see how to solve the challenge, step by step.

<div style="position: relative; padding-bottom: 56.25%; height: 0;"><iframe src="https://www.loom.com/embed/bd70ce6e605a48fbad8742da64b9a03d" frameborder="0" webkitallowfullscreen mozallowfullscreen allowfullscreen style="position: absolute; top: 0; left: 0; width: 100%; height: 100%;"></iframe></div>

</details>

## Submit your assignment

When you are finished with the above tasks, **enter the full secret message** into the form below

<aside>

🚨 We need to know who you are! When you fill out the form

1. **Use your preferred first and last name**
2. **Use the email you used to apply for Kibo**
</aside>

<div style="width:100%;height:500px;"><iframe src="https://docs.google.com/forms/d/e/1FAIpQLSds6HWJYBJv49zRoUzLSJ7pc-aQM6jxTY0e3Fg7z3KdSM1ojA/viewform?usp=send_form&embed=true" frameborder="0" sandbox="allow-scripts allow-popups allow-top-navigation-by-user-activation allow-forms allow-same-origin" allowfullscreen="" style="width: 100%; height: 100%; border-radius: 1px; pointer-events: auto; background-color: white;"></iframe></div>

# 4. Wrap Up

<aside>

⚠️ **Have you submitted the form with your answer to Decrypt me?**

</aside>

### **If so, congratulations! You have now completed the Future Proof with Python admissions challenge! 🎉**

## Here’s what you learned:

- How to use **Replit** and **Notion** to learn with Kibo.
- How to use basic input and output in Python.
- How to copy, paste, and run code step by step to solve problems

Plus, hopefully some tidbits about codes and cryptography!

## What’s next?

- **Receive your admission decision:** we will review your submission and send you an email within one week if you have been admitted to the program.
- **Complete onboarding:** You will select your live class time, and join our Discord learning community. Once you complete these steps, you will be sent an invite to Orientation which is mandatory, on Zoom.

## Congrats!

We’re so excited for you to join Kibo! We hope this brief taste of Programming in Python gets you excited for what’s to come.

At Kibo we love learning together!

As a tradition, we take a “peakture” together on zoom!

![Peak1.png](/future-proof-with-python/wrapping-up-final-steps-for-fpwp/peak1.png)

See you soon! ✨

