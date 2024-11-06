### Description
---
L'objet `Array` permet de représenter un tableau d'objet de même type.
Cet objet est spéciale car il est utilisable sur tous les types d'objets.

### Définition
---
On créé un [`Array`](./Array.md) de taille infixe de la façon suivante:
```base
new Object[];
```

On créé un [`Array`](./Array.md) de taille fixe de la façon suivante:
```base
new Object[Integer]
```

Avec un [`Integer`](./Integer.md) strictement positif.

Le non respect de cette condition entraîne une erreur.

### Utilisation
___
On pose `objectArray`, un [`Array`](./Array.md).

#### Opération toujours possible
Pour `i` un [`Integer`](./Integer.md) strictement positif et strictement inférieur à la taille de `objectArray`.

Récupérer un objet à l'indice `i`:
```base
objectArray[i];
```

Placer l'objet `obj` (respectant le type de `objectArray`) à l'indice `i`:
```base
objectArray[i] = obj;
```

Pour combiner `objectArray` et `objectArray2`, un [`Array`](./Array.md) du même type que `objectArray`:
```base
objectArray + objectArray2;
```
On aura les valeurs de `objectArray` avant celles de `objectArray2` et la taille de l'[`Array`](./Array.md) formé par cette opération est fixe et est égale à la somme des tailles des deux [`Array`](./Array.md).
#### Opération uniquement possible pour un [`Array`](./Array.md) de taille infixe
Ajouter l'objet `obj` (respectant le type de `objectArray`) à la fin de `objectArray`:
```base
objectArray.add(obj);
```

Retirer (et récupérer) le dernier élément de `objectArray`:
```base
objectArray.pop();
```

### Attributs
---

|   Nom    |            Type             | Description                   |
| :------: | :-------------------------: | :---------------------------- |
| ``fixe`` | [``Boolean``](./Boolean.md) | indique si la taille est fixe |
|  `size`  |  [`Integer`](./Integer.md)  | taille du tableau             |

### Méthodes
---

|     Nom     |         Arguments          |        Type renvoyé         | Description                                          |
| :---------: | :------------------------: | :-------------------------: | ---------------------------------------------------- |
|   ``add``   | `object` (Type de l'Array) |          ``void``           | Ajoute `object` à la fin de l'Array                  |
|   ``pop``   |           aucun            |       Type de l'Array       | Supprime le dernier élément de l'Array et le renvoie |
| ``getSize`` |           aucun            | [``Integer``](./Integer.md) | Renvoie la taille de l'Array                         |
|  `isFixed`  |           aucun            |  [`Boolean`](./Boolean.md)  | Renvoie la valeur de `fixe`                          |
