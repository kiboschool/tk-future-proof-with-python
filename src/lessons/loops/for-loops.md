# For loops

_Estimated Time: 1 hour_

---

We often want code to run again and again, until it’s time to stop. We learned that a `while` loop is a great tool when you know the stopping condition.

In this section we will explore a second tool for repeating code: the `for` loop. A `for` loop is a good fit when we want to run a block of code a definite number of times, or when we want to iterate over list of things.

# `for` Loops

`for` loops step through a list of items in order. Each iteration will assign the next item to the loop variable, then execute the loop body.

The syntax of a `for` loop starts with the `for` keyword, and has an indented loop body. A `for` loop has a variable name, the `in` keyword, and a list of things to loop through.

```python
for variable in items:
	loop body to execute
```

The flow chart of a `for` loop is:

![For-Loops-1.png](for-loops/untitled.png)

Let's take a look at an example of a `for` loop:

```python
for i in [5, 4, 3, 2, 1] :
	print(i)
print('Blastoff!')
```

This `for` loop will have the same output as the `while` loop we saw in the previous section:

```
5
4
3
2
1
Blastoff!
```

Let’s compare the `for` loop with the `while` loop :

```python
for i in [5, 4, 3, 2, 1] :
	print(i)
print('Blastoff!')
```

```python
n = 5
while n > 0:
    print(n)
    n = n - 1
print('Blastoff!')
```

🤔 Compare the two code examples above (the `for` loop and the `while` loop). What do you notice about them?

<details><summary><code>while</code> vs. <code>for</code></summary>

Similarities:

- loop keyword, then something, then `:`
- loop body is indented

Differences:

- variable `n` created before the while loop, variable `i` created as part of the `for` loop
- `while` loop changes the variable with `n = n - 1`, `for` loop variable changes automatically
- `for` loop has to write out exactly what numbers to loop through

</details>

## `for` loop iteration variable

The initial statement in the `for` loop is:

```python
for i in [5,4,3,2,1]:
```

In this code, the loop creates a new variable `i`. The value of `i` will change in each iteration of the loop, to take on the value of each item in the list. In this example, `i` will take on successive values of 5, 4, 3, 2, and 1.

As you can see, `for` loops offer a more direct syntax than `while` loops, because you can explicitly declare the values of the iteration variable.

We’ll cover the list syntax `[5, 4, 3, 2, 1]` in more detail later in the course. For now, you can use it to write `for` loops, without knowing exactly what it means. You can put any values inside the `[]`, and the loop variable will be assigned to each value in turn.

## Practice

<aside>

👩🏿‍💻 Write a `for` loop that displays Hello, plus each name in the list. Follow the code comments in the below Replit exercise.

The output should be like this screenshot:

![For-Loops-2.png](for-loops/untitled-1.png)

</aside>

<div style="position: relative; padding-bottom: 56.25%; height: 0;"><iframe src="https://replit.com/team/tk12-fpwp/W32-For-Loop-Practice" frameborder="0" webkitallowfullscreen mozallowfullscreen allowfullscreen style="position: absolute; top: 0; left: 0; width: 100%; height: 100%;"></iframe></div>
