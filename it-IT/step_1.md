Lo scopo di un ciclo **while** è ripetere il codice più volte mentre una condizione è `True`. Questo è il motivo per cui i cicli while sono a volte indicati come cicli **condition-controlled**.

L'esempio qui sotto è un ciclo While che funzionerà per sempre - un ciclo infinito. Il ciclo verrà eseguito per sempre perché la condizione è sempre `True`.

```python
while True:
    print("Hello world")
```

Nota: La linea `while` dichiara la **condizione** del ciclo. La riga di codice `print` è leggermente più a destra. Questo è chiamato __indentazione__ - la linea è indentata per mostrare che è all'interno del ciclo. Qualsiasi codice all'interno del ciclo verrà ripetuto.

Un ciclo infinito è utile in situazioni in cui si desidera eseguire le stesse azioni più e più volte, ad esempio il controllo del valore di un sensore. Un ciclo infinito come questo continuerà a funzionare per sempre il che significa che qualsiasi riga di codice scritto dopo il ciclo non verrà mai eseguita. Questo è noto come **blocking** - cioè un programma che **blocca** l'esecuzione di qualsiasi altro codice.
