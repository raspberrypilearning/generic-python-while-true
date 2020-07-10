O objetivo de um laço **while** é repetir o código várias vezes enquanto uma condição for `True` (verdadeira). É por isso que laços while por vezes são referidos como laços **controlados por condição**.

O exemplo abaixo é um laço while que será executado para sempre - um laço infinito. O laço será executado para sempre porque a condição é sempre `True` (verdadeira).

```python
while True:
    print("Olá mundo")
```

Nota: A linha `while` indica a **condição** do laço. A linha de código `print` abaixo é um pouco mais à direita. Chama-se isso de __indentação__ - a linha está recuada para mostrar que está dentro do laço. Qualquer código dentro do laço será repetido.

Um laço infinito é útil em situações onde você deseja executar as mesmas ações várias vezes. Por exemplo, verificando o valor de um sensor. Um laço infinito como este continuará a ser executado para sempre, o que significa que quaisquer linhas de código escritas após o laço nunca acontecerão. Isto é conhecido como **bloqueio** - em que um programa **bloqueia** a execução de qualquer outro código.
