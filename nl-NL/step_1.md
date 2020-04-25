Het doel van een **while**-lus is om code te blijven herhalen zolang een voorwaarde `True` is. Dit is de reden waarom while-lussen soms **conditie-gecontroleerde** lussen worden genoemd.

Het onderstaande voorbeeld is een while-lus die voor altijd loopt - een oneindige lus. De lus loopt voor altijd omdat de voorwaarde altijd `True` is.

```python
while True:
    print("Hallo wereld")
```

Opmerking: de `while` regel geeft de lus-**conditie**. De `print` regel code eronder begint iets verder naar rechts. Dit wordt __inspringen__ genoemd - de regel is ingesprongen om aan te geven dat deze zich binnen de lus bevindt. Alle code in de lus wordt herhaald.

Een oneindige lus is handig in situaties waarin je steeds opnieuw dezelfde acties wilt uitvoeren, bijvoorbeeld door de waarde van een sensor te controleren. Een oneindige lus als deze zal voor altijd blijven lopen, wat betekent dat alle regels code die na de lus worden geschreven, nooit zullen gebeuren. Dit staat bekend als **blokkeren** - waarbij een programma de uitvoering van iedere andere code **blokkeert**.
