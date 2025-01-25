# String

### Étend
---
- `Char[]` ([`Array`](Array.md))

### Description
---
L'objet (String.md) représente une chaîne de caractère. C'est un [`Array`](Array.md) de taille infixe de [`Char`](Char.md) (`Char[]`).
Le mot clef `string` fait référence à cet objet.

### Méthodes
---

|        Nom         |               Arguments                |            Type renvoyé             | Description                                                                                                |
| :----------------: |:--------------------------------------:|:-----------------------------------:| ---------------------------------------------------------------------------------------------------------- |
|   `toUpperCase`    |                 aucun                  |      [`String`](#description)       | Renvoie la chaîne de caractère en majuscules.                                                              |
|   `toLowerCase`    |                 aucun                  |      [`String`](#description)       | Renvoie la chaîne de caractère en minuscules.                                                              |
|      `split`       | `separator` ([`String`](#description)) |       [`String[]`](Array.md)        | Renvoie le tableau des parties de la chaîne de caractère séparés par `separator`.                          |
| `equalsIgnoreCase` |     `other_string` ([`String`](#description))     |      [`Boolean`](Boolean.md)       | Renvoie si la chaîne de caractère et `other_string` sont égaux sans prendre en compte la casse d'écriture. |


