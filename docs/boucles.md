# 4. Boucles

Pour faire votre carré, vous avez dû répéter 4 fois la même opération : "avance de 100 et tourne à gauche de 90°".

Pour simplifier le code, on va créer une boucle : on indique à la machine qu'elle va répéter n fois la même suite d'opérations.

En Python, comme dans la plupart des langages de programmation, la boucle la plus commune est la boucle "Pour", en anglais "For".

Essayez le code suivant :
```python
for _ in range(10):
    print("Hello!")
```
Dans le cas de notre carré, nous aurons ceci :
```python
for _ in range(4):
    franklin.forward(100)
    franklin.left(90)
```

Description : 
- "for" = début de la boucle "pour"
- le symbole "_" signifie qu'on n'a pas besoin d'utiliser le compteur
- range(4) : on utilise un ensemble de 4 éléments, donc on effectuera 4 tours
- notez les ":" à la fin de la ligne
- les lignes suivantes sont décalées par une indentation : c'est un bloc d'instructions
- toutes les lignes décalées (indentées) seront répétées dans la boucle. Dès qu'une ligne n'est plus indentée, on sera sorti de la boucle.

## Défi

1. À l'aide d'une boucle, créer un triangle équilatéral (attention aux angles)
2. Modifier le code pour créer un pentagone régulier
3. En utilisant une variable "n" contenant le nombre de côtés de notre figure, modifier le programme afin de dessiner un polygone régulier à n côtés