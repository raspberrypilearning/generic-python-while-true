### Python - while loop

The purpose of a **while** loop is to repeat code over and over while a condition is `True`. This is why while loops are sometimes referred to as **condition-controlled** loops.

#### Infinite loops
The example below is a while loop that will run forever - an infinite loop. The loop will run forever because the condition is always `True`.

```python
while True:
    print("Hello world")
```

Note: The `while` line states the loop **condition**. The `print` line of code below it is slightly further to the right. This is called __indentation__ - the line is indented to show that it is inside the loop. Any code inside the loop will be repeated.

An infinite loop is useful in situations where you want to perform the same actions over and over again, for example checking the value of a sensor. An infinite loop like this will **block** - this means that any lines of code written after the loop will never happen.

#### Loops based on a boolean variable

In this example, the condition is a boolean variable we gave the name `keep_looping`. It's value is set as `True` at the top. The value can become `False`, which will make the condition of the while loop `False`. When this happens, the loop stops running.

```python
keep_looping = True

while keep_looping:
    print("I am in a loop")
    command = input("Shall I keep looping?")
    if command == "no":
        keep_looping = False
```

This kind of loop is useful in situations where you want to repeat code until a specific event happens. For example, you may want a program to continue running until someone types something to tell it to quit.

#### Loops based on a counter

Sometimes while loops are written to repeat a specified number of times:

```python
counter = 0
while counter < 10:
    print("Counting...")
    counter += 1
```
In this example, the condition is `counter < 10`. Since we add `1` to `counter` each time the loop runs, the loop will run 10 times.
