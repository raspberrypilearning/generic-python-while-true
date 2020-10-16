Celem pętli **while** jest powtarzanie kodu w kółko, dopóki warunek jest prawdziwy czyli ma wartość `True`. To dlatego pętle while są czasami określane jako pętle **sterowane warunkowo**.

Poniższy przykład to pętla while, która będzie działać wiecznie - nieskończona pętla. Pętla nie przestanie działać, ponieważ warunkiem jest zawsze `True`.

```python
while True:
    print ("Witaj świecie")
```

Zauważ, że linia z `while` zawiera również **warunek** pętli. Polecenie `print` znajdujące się poniżej jest przesunięte nieco dalej w prawo. Nazywa się to __wcięciem__ - linia jest wcięta, aby pokazać, że znajduje się w pętli. Cały kod znajdujący się w pętli zostanie powtórzony.

Nieskończona pętla jest przydatna w sytuacjach, w których chcesz wykonywać te same czynności w kółko, na przykład sprawdzając wartość zmierzoną przez czujnik. Taka nieskończona pętla będzie działać wiecznie, co oznacza, że żadne wiersze kodu napisane po pętli nigdy się nie zostaną wykonane. Nazywane jest to **blokowaniem** - program **blokuje** wykonanie dowolnego innego kodu.
