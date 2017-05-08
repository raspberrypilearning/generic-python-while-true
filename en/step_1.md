### Python - while loop

The purpose of a **while loop** is to repeat code until a condition becomes True.

#### Infinite loop
Here is an example of a **while loop** which will run forever - this is called an infinite loop. The loop will run forever because the condition is always True.

```python
while True:
    print("Hello world")
```

Notice that the `print` line of code is slightly further to the right. This is called __indentation__ - the line is __indented__ to show that it is inside the loop. Any lines of code inside the loop will be repeated.

An infinite loop is useful in situations where you want to perform the same actions over and over again, for example checking the value of a sensor. An infinite loop like this will **block** - this means that any lines of code written after the loop will never happen.

#### Loop based on a boolean value

In this example, the condition is a boolean variable `keep_looping` which starts off `True`. It is possible for the condition in this loop to become False. When it does, the loop will stop.

```python
keep_looping = True

while keep_looping:
    print("I am in a loop")
    command = input("Shall I keep looping?")
    if command == "no":
        keep_looping = False
```

This kind of loop is useful in situations where you want to repeat code until a specific event happens, for example in a menu where you want the program to continue working until someone types quit.

#### Loop based on a counter

Sometimes while loops are written to repeat a specified number of times:

```python
counter = 0
while counter < 10:
    print("Counting...")
    counter += 1
```
In this example, the condition is `counter < 10` and since we add 1 to `counter` each time the loop runs, the loop will run 10 times. While loops are sometimes referred to as **condition controlled loops** because the loop will continue running until the condition becomes `True`. 
