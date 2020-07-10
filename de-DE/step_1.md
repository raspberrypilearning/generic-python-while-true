Der Zweck einer **while**-Schleife ist es, den Code immer und immer wieder zu wiederholen, bis eine Bedingung `True` (Wahr) ist. Aus diesem Grund werden While-Schleifen manchmal als **Bedingungs-gesteuerte** Schleifen bezeichnet.

Das folgende Beispiel ist eine While-Schleife, die für immer läuft - eine Endlosschleife. Die Schleife wird für immer laufen, weil die Bedingung immer `True` (wahr) ist.

```python
while True:
    print("Hallo Welt")
```

Hinweis: Die `while`-Zeile gibt die **Bedingung** für die Schleife an. Die `print`-Codezeile beginnt etwas weiter rechts. Dies wird __Einrückung__ genannt - die Zeile ist eingerückt, um zu zeigen, dass sie innerhalb der Schleife ist. Jeder Code innerhalb der Schleife wird wiederholt.

Eine Endlosschleife ist in Situationen nützlich, in denen du dieselben Aktionen immer und immer wieder ausführen möchtest, zum Beispiel um den Wert eines Sensors zu überprüfen. Eine Endlosschleife wie diese läuft für immer weiter, was bedeutet, dass alle Codezeilen, die nach der Schleife geschrieben werden, niemals passieren werden. Das wird als **blockieren** bezeichnet - wobei ein Programm die Ausführung eines anderen Codes **blockiert**.
