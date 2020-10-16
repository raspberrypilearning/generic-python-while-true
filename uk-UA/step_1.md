Мета циклу **while** — повторювати код знову і знову, поки умова є `True`, тобто умова істинна. Ось чому цикли while інколи називають циклами, **які контролюються умовою**.

Наведений нижче приклад є цикл while, який буде виконуватись завжди — нескінченний цикл. Цикл працюватиме завжди, тому що умова завжди істинна (`True`).

```python
while True:
    print("Привіт, світ")
```

Примітка: рядок коду `while` визначає **умову** циклу. Рядок коду із `print` дещо зміщений вправо. Це називається __відступ__ — цей рядок має відступ, щоб показати, що він знаходиться всередині циклу. Будь-який код всередині циклу буде повторений.

Нескінченний цикл корисний у ситуаціях, коли ти хочеш, щоб виконувались одні й ті ж дії знову і знову, наприклад, перевіряючи значення датчика. Такий нескінченний цикл буде продовжувати виконуватись завжди, тобто будь-які рядки коду, написані після циклу, ніколи не виконаються. Це називається **блокування**, за допомогою чого програма **блокує** виконання будь-якого іншого коду.