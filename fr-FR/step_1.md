Le but d'une boucle **while** est de répéter le code encore et encore pendant qu'une condition est `Vraie` (True). C'est pourquoi les boucles « while » sont parfois appelées boucles **contrôlées par condition**.

L'exemple ci-dessous est une boucle « while » qui s'exécutera indéfiniment - une boucle infinie. La boucle s'exécutera indéfiniment parce que la condition est toujours `Vraie`.

```python
while True:
    print("Bonjour le monde")
```

Remarque : la ligne `while` indique la **condition** de la boucle. La ligne de code `print` ci-dessous est légèrement plus à droite. Cela s'appelle __indentation__ - la ligne est indentée pour montrer qu'elle est à l'intérieur de la boucle. Tout code à l'intérieur de la boucle sera répété.

Une boucle infinie est utile dans les situations où tu veux effectuer les mêmes actions encore et encore par exemple en vérifiant la valeur d'un capteur. Une boucle infinie comme celle-ci continuera à s'exécuter indéfiniment, ce qui signifie que toutes les lignes de code écrites après la boucle ne seront jamais exécutées. Ceci est connu sous le nom de **blocage** - par lequel un programme **bloque** l'exécution de tout autre code.
