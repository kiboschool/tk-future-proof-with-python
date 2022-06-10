# 1.3. Variables and Assignment

*Estimated Time: 15 minutes*

---

## What you need to know about variables

- A Variable is a name you give to data, so you can use it later in the program
- You assign a variable with `=`
- There are lots names you can use for variables, but there are some rules
- Using meaningful variable names makes your program better

## Video: What are variables?

<aside>
<img src="../instruction.png" alt="../instruction.png" width="40px" /> Watch this video to learn about variables.

</aside>

[https://www.youtube.com/watch?v=ZDjxKGNfJKo](https://www.youtube.com/watch?v=ZDjxKGNfJKo)

## Video Notes

- Working with variables and data is a core part of learning programming
- A **Variable** is a named place in memory. We can use it to store data and manipulate it, using its name.
- An **assignment statement** assigns some value (on the right-hand side) to the variable name on the left-hand side. Technically this means putting this value in memory and point to it using that variable name.

## Video: Variable Names

<aside>
<img src="../instruction.png" alt="../instruction.png" width="40px" /> Watch this video to learn about variable naming rules

</aside>

[https://www.youtube.com/watch?v=csYYlAITTzU](https://www.youtube.com/watch?v=csYYlAITTzU)

### Video Notes

- Variable names in Python must follow some rules:
    - We cannot use r**eserved words for** variables names**.** Reserved words include words like `if`, `for,` `return`, which have specific meanings in Python
    - Names can start with letters or underscores, and can only contain letters, numbers, and underscores. They can’t have spaces.
- Variable names are case-sensitive. That means `shop` and `Shop` can refer to different values.

### Good and Bad Variable Names

Good variable naming is important! Variable names should be descriptive and help a human reader to understand the code. 

For example, take a look at the code below:

```python
x1q3z9ocd = 35.0
x1q3z9afd = 12.50
x1q3p9afd = x1q3z9ocd * x1q3z9afd
print(x1q3p9afd) # 437.5
```

The variable names above are allowed in Python, but they are **not helpful**.  

**Contrast with:**

```python
hours = 35.0
pay_rate = 12.50
pay = hours * pay_rate
print(pay) # 437.5
```

These variable names are descriptive and helpful! 

## Practice: Assigning and printing variables

<aside>
👩🏿‍💻 Let's practice assigning values to variables and printing variables. Read the code below, and make the changes requested in the comments.

</aside>

[https://replit.com/team/kibo-fpwp5/Variables-and-Assignment-Practice](https://replit.com/team/kibo-fpwp5/Variables-and-Assignment-Practice)

<aside>
📌 When your code runs, the output should look like this

![1%203%20Variables%20and%20Assignment%207a30aa1380874207a16f80c2e997197d/Untitled.png](1%203%20Variables%20and%20Assignment%207a30aa1380874207a16f80c2e997197d/Untitled.png)

</aside>

- **Solution** (try for 5 minutes before looking!)
    
    ```python
    books_read = 13
    print(books_read)
    
    meals_eaten = 4
    meals_eaten = meals_eaten + 1
    print(meals_eaten)
    ```
    

<aside>
<img src="../Lesson%200%20Learning%20With%20Kibo%2032002756da8b4ed2a610df0347af2a08/man-in-hike.png" alt="../Lesson%200%20Learning%20With%20Kibo%2032002756da8b4ed2a610df0347af2a08/man-in-hike.png" width="40px" /> Next up: [Data Types, Operators, and Expressions](1%204%20Data%20Types,%20Operators,%20and%20Expressions%201e6cf178bfac4c3190acd92477c61b0f.md)

</aside>