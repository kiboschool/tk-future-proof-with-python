# Range function

_Estimated Time: 30 minutes_

---

## Range function

There’s another way to tell the `for` loop what values to iterate over. `range()` is a function that generates a series of numbers within a certain range.

```python
# Same loop as before, using range()
for i in range(5,0,-1):
	print(i)
print("Blastoff!")
```

```
5
4
3
2
1
Blastoff!
```

For longer lists of numbers, `range` is easier than typing the whole thing out.

The syntax for the range function is below.

```python
range(start, stop, step)
```

- **_start_** specifies the first value of the range.
- **_stop_** specifies the stopping point.
  - The stop value is **not** included in the range, so `range(1,10)` will only go up to `9`.
- **_step_** specifies how much to count by each time. `range(2,10, 2)` produces `2`, `4`, `6`, `8`.
  - The **default value** is 1, which means that if you leave _step_ out, `range` will count by 1.

Here’s some examples using `range`:

```python
# Print the numbers 1-10
for n in range(1,11): # 11 is not included!
	print(n)

# Print the numbers 5, 10, 15, 20... 100, counting by 5s
for number in range(5, 101, 5):
	print(number)

# Print the numbers counting down from 5 to 1
for i in range(5,0,-1):
	print(i)
print("Blastoff!")
```

<aside>

📺 Watch this video to learn more about Loops.

</aside>

<div style="position: relative; padding-bottom: 56.25%; height: 0;"><iframe width="590" height="475" src="https://edpuzzle.com/embed/assignments/6637fd3138020389ce662e4c/watch" frameborder="0" allowfullscreen></iframe></iframe></div>


## Range Practice

<aside>

🎯 Practice writing `for` loops that use `range`.

- Print the numbers from 4 to 14
- Print the numbers from -10 to 10
- Print the numbers from 1 to 20, counting by 2s
- Print the numbers from 1000 to 500, counting backwards by 100s
</aside>

<div style="position: relative; padding-bottom: 56.25%; height: 0;"><iframe src="https://replit.com/team/tk12-fpwp/W33-Range-Practice" frameborder="0" webkitallowfullscreen mozallowfullscreen allowfullscreen style="position: absolute; top: 0; left: 0; width: 100%; height: 100%;"></iframe></div>
