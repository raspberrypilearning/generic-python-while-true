The purpose of a **while** loop is to repeat code over and over while a condition is `True`. This is why while loops are sometimes referred to as **condition-controlled** loops.

The example below is a while loop that will run forever - an infinite loop. The loop will run forever because the condition is always `True`.

```python
while True:
    print("Hello world")
```

Note: The `while` line states the loop **condition**. The `print` line of code below it is slightly further to the right. This is called __indentation__ - the line is indented to show that it is inside the loop. Any code inside the loop will be repeated.

An infinite loop is useful in situations where you want to perform the same actions over and over again, for example checking the value of a sensor. An infinite loop like this will **block** - this means that any lines of code written after the loop will never happen.
