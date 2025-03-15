# Array

### Description
---
L'objet `Array` permet de représenter un tableau d'objet de même type.
Cet objet est spécial, car il est utilisable sur tous les types d'objets.

### Définition
---
On crée un `Array` de la façon suivante :
```base
new Object[Integer size]
```

Ou en plaçant directement les objets dedans :
```base
Object[] objectArray = [o1, o2, o3, o4, ...];
```


Avec un [`Integer`](Integer.md) strictement positif.

Le non-respect de cette condition entraîne une erreur.

En utilisant la première méthode, le tableau est remplie d'élément ayant des valeurs aléatoires, il faut donc penser à les initialiser.

#### Exception
Un `Array` de [`Char`](Char.md) peut se créer en mettant une suite de caractères entre guillemets.
```base
char[] myCharArray = "I am a char array";
```

Sa taille est d'un de plus que le nombre de caractères dans les guillemets. En effet, dans le cas de la construction d'un `Array` de [`Char`](Char.md) par des guillemets.


### Utilisation
___
On pose `objectArray`, un `Array`.

Pour `i` un [`Integer`](Integer.md) strictement positif et strictement inférieur à la taille de `objectArray`.

Récupérer un objet à l'indice `i` :
```base
objectArray[i];
```

Placer l'objet `obj` (respectant le type de `objectArray`) à l'indice `i`:
```base
objectArray[i] = obj;
```

### Attributs
---

|  Nom   |          Type           | Description       |
|:------:|:-----------------------:|:------------------|
| `size` | [`Integer`](Integer.md) | taille du tableau |

### Méthodes
---

|      Nom      |            Type renvoyé             | Description                                          |
|:-------------:|:-----------------------------------:|------------------------------------------------------|
| ``getSize()`` |      [``Integer``](Integer.md)      | Renvoie la taille de l'Array                         |


### Mémoire
---

L'emplacement mémoire d'un `Array` commence par un [](Integer.md) décrivant la taille de l'`Array`, les éléments de l'`Array` se suivent directement après.