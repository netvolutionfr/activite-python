# 3. Variables

On appelle "variable" une donnée enregistrée en mémoire dans le programme, à laquelle on donne un nom.

Exemple :

```python
longueur = 100
```

Ici, on a enregistré la valeur "100" dans la variable "longueur".

On peut ensuite réutiliser cette donnée dans notre programme :

```python
franklin.forward(longeur)
```

L'intérêt : si on veut choisir la longueur du côté de notre carré, on enregistre cette longueur à un seul endroit dans notre programme, et la réutilise à plusieurs endroits. Certes, notre code est court, mais dans le cas d'un code plus complexe, vous comprenez l'intérêt !

## Exercice

Modifier le code du carré pour donner une variable "longueur" pour la longueur du côté du carré.

**Pro tip** : Je peux bien sûr créer plusieurs variables :
```python
longueur = 100
largeur = 50
```
et je peux même les assigner en une seule ligne :
```python
longueur, largeur = 100, 50
```