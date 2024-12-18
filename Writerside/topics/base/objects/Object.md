# Object

### Description
---
L'objet `Object` contient ce que tous les autres objets intègrent par défaut.

Ce qui est ajouté dans `Object` est automatiquement ajouté à tous les autres objets définis.

### Attributs
---

|     Nom     |           Type            | Description                |
| :---------: |:-------------------------:| :------------------------- |
| ``pointer`` | [``Integer``](Integer.md) | adresse mémoire de l'objet |


### Fonctions
---

|      Nom       |                Arguments                |        Type renvoyé         | Description                                                       |
| :------------: |:---------------------------------------:|:---------------------------:| ----------------------------------------------------------------- |
| ``getPointer`` |                  aucun                  |  [``Integer``](Integer.md)  | Renvoie le pointer de l'objet                                     |
| ``setPointer`` | ``pointer`` ([``Integer``](Integer.md)) |          ``void``           | Définie le pointer de l'objet                                     |
|   ``equals``   |       ``objet`` ([``Object``](#description))       | [``Boolean``](Boolean.md) | Renvoie si l'objet de référence et l'objet comparé sont les mêmes |
