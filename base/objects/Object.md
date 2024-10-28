### Description
---
L'objet `Object` contient ce que tous les autres objets intègrent par défaut.

Ce qui est ajouté dans `Object` est automatiquement ajouté à tous les autres objets définis.

### Attributs
---

|     Nom     |    Type     | Description                |
| :---------: | :---------: | :------------------------- |
| ``pointer`` | ``Integer`` | adresse mémoire de l'objet |

### Fonctions
---

|      Nom       |         Arguments         | Type renvoyé | Description                                                       |
| :------------: | :-----------------------: | :----------: | ----------------------------------------------------------------- |
| ``getPointer`` |           aucun           | ``Integer``  | Renvoie le pointer de l'objet                                     |
| ``setPointer`` | ``pointer`` (``Integer``) |   ``void``   | Définie le pointer de l'objet                                     |
|   ``equals``   |  ``objet`` (``Object``)   | ``Boolean``  | Renvoie si l'objet de référence et l'objet comparé sont les mêmes |
