El propósito de un bucle **while** es repetir código una y otra vez, mientras que una condición sea `Verdadera`. Esta es la razón por la que los bucles while a veces se denominan bucles **controlados por condiciones**.

El siguiente ejemplo es un bucle while que se ejecutará por siempre - un bucle infinito. El bucle se ejecutará para siempre porque la condición es siempre `Verdadera`.

```python
while True:
    print("Hola mundo")
```

Nota: la linea de código con el `while` indica la **condición** del bucle. La línea de código de debajo con el `print` está un poco más hacia la derecha. Esto se llama __sangría__ (Nota: también puedes verlo como identación) - la línea está sangrada para mostrar que está dentro del bucle. Cualquier código que está dentro del bucle será repetido.

Un bucle infinito es útil en situaciones en las que deseas realizar las mismas acciones una y otra vez, por ejemplo comprobar el valor de un sensor. Un bucle infinito como este continuará ejecutándose para siempre lo que significa que cualquier línea de código escrita después del bucle nunca se ejecutará. Esto se conoce como **bloqueo** - por el cual un programa **bloquea** La ejecución de cualquier otro código.
