El propósito de un bucle **while** es repetir el código una y otra vez, mientras que una condición es `True` o verdadera. Esta es la razón por la que los bucles while a veces se conocen como bucles **controlados por condiciones**.

El siguiente ejemplo es un bucle while que se ejecutará para siempre - un bucle infinito. El bucle se ejecutará infinitamente porque la condición es siempre `True` o verdadera.

```python
while True:
    print("Hola mundo")
```

Nota: La línea `while` indica la **condición** del bucle. La línea de código abajo `print` se encuentra un poco más a la derecha. Esto es llamado __indentación__ - la línea está indentada para indicar que se encuentra dentro del bucle. Cualquier código dentro del bucle será repetido.

Un bucle infinito es útil en situaciones en las que desea realizar las mismas acciones una y otra vez. Por ejemplo, comprobando el valor de un sensor. Un bucle infinito como éste continuará ejecutándose para siempre. Esto significa que cualquier línea de código escrita después del bucle nunca ocurrirá. Esto se conoce como **bloqueo** - por lo que un programa **bloquea** la ejecución de cualquier otro código.
