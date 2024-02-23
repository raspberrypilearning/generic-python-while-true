Scopul unei bucle **while** este de a repeta codul de mai multe ori cât timp o condiție este `True` (n. trad. adevărată). Acesta este motivul pentru care buclele while sunt uneori numite bucle ** controlate de condiție**.

Exemplul de mai jos este o buclă while care se va executa pentru totdeauna - o buclă infinită. Bucla se va executa la infinit deoarece condiția este întotdeauna `True`.

```python
while True:
    print ("Hello world")
```

Notă: Linia cu `while` arată **condiția** execuției buclei. Linia de cod `print` de mai jos este puțin mai la dreapta. Aceasta se numește __indentare__ - linia este indentată pentru a arăta că este în interiorul buclei. Orice cod din interiorul buclei va fi repetat.

O buclă infinită este utilă în situațiile în care dorești să efectuezi aceleași acțiuni în mod repetat, de exemplu, verificarea valorii unui senzor. O buclă infinită ca aceasta va continua să ruleze la nesfârșit, însemnând că orice linii de cod scrise după buclă nu vor fi executate niciodată. Aceasta este cunoscută sub numele de **blocare** - prin care un program **blochează** executarea oricărui alt cod.
