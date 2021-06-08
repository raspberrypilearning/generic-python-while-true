The purpose of a **while** loop is to repeat code over and over while a condition is `True`. This is why while loops are sometimes referred to as **condition-controlled** loops.

The example below is a while loop that will run forever - an infinite loop. 因它的「檢查條件」永遠都是 `True`。

```python
while True:
    print("Hello world")
```

Note: The `while` line states the loop **condition**. The `print` line of code below it is slightly further to the right. This is called __indentation__ - the line is indented to show that it is inside the loop. 在循環內的任何程式碼都將會重複執行。

An infinite loop is useful in situations where you want to perform the same actions over and over again, for example checking the value of a sensor. An infinite loop like this will continue to run forever meaning that any lines of code written after the loop will never happen. This is known as **blocking** - whereby a program **blocks** the execution of any other code.
