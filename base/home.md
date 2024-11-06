
### Identification
---
Nom: Base

Paradigmes: Fonctionnel et Orienté Objet

Compile vers: ASM -> Binaire (pour commencer) ; Binaire (quand le système fonctionnera)
### Mots Clefs
---

|      Mot       | Utilité                                                                     |
| :------------: | :-------------------------------------------------------------------------- |
|      `if`      | condition                                                                   |
|     `else`     | non respect condition                                                       |
|   `else-if`    | condition si non respect condition précédente                               |
|    `while`     | boucle tant que                                                             |
|   `function`   | mot définition fonction                                                     |
|    `public`    | accessibilité de fonction ou variable (globale) de partout                  |
|   `private`    | accessibilité de fonction ou variable (globale) dans même classe uniquement |
|    `switch`    | bloc "multiconditionnel"                                                    |
|    `return`    | déclaration finale d'une fonction renvoyant une objet ou rien               |
|     `null`     | objet nul (sans existance)                                                  |
|   `(` & `)`    | ouverture et fermeture d'arguments, de conditions et de priorité            |
|   `{` & `}`    | ouverture et fermeture de bloc de code                                      |
|      `=`       | assignation                                                                 |
|      `+`       | addition                                                                    |
|      `-`       | soustraction                                                                |
|      `*`       | multiplication                                                              |
|      `/`       | division                                                                    |
|      `%`       | reste division euclidienne                                                  |
|      `**`      | exposant                                                                    |
|      `&&`      | et (conditonnel)                                                            |
| &brvbar&brvbar | ou (conditionnel)                                                           |
|      `!`       | non                                                                         |
|      `&`       | et (binaire)                                                                |
|    &brvbar     | ou (binaire)                                                                |
|      `^`       | ou exclusif (binaire)                                                       |
|      `<<`      | décalage binaire vers la gauche                                             |
|      `>>`      | décalage binaire vers la droite                                             |
|      `==`      | égal (conditionnel)                                                         |
|      `<`       | inférieur (conditionnel)                                                    |
|      `>`       | supérieur (conditionnel)                                                    |
|      `<=`      | inférieur ou égal (conditionnel)                                            |
|      `>=`      | supérieur ou égal (conditionnel)                                            |
|      `!=`      | non égal / différent (conditionnel)                                         |
|      `!<`      | non inférieur (conditionnel)                                                |
|      `!>`      | non supérieur (conditionnel)                                                |
|      `;`       | fin d'instruction                                                           |
|    `string`    | référence au type [`String`](./objects/String.md)                           |
|     `int`      | référence au type [`Integer`](./objects/Integer.md)                         |
|    `float`     | référence au type [`Float`](./objects/Float.md)                             |
|     `bool`     | référence au type [`Boolean`](./objects/Boolean.md)                         |
|     `char`     | référence au type [`Char`](./objects/Char.md)                               |
|      `//`      | début commentaire en ligne                                                  |
|      `/*`      | début commentaire multi-lignes                                              |
|      `*/`      | fin commentaire multi-lignes                                                |


### Objets par défaut
---

|               Nom               | Description              |
| :-----------------------------: | ------------------------ |
|  [Object](./objects/Object.md)  | Base de tous les objets  |
| [Integer](./objects/Integer.md) | Nombres entiers relatifs |
|   [Float](./objects/Float.md)   | Nombres à virgule        |
| [Boolean](./objects/Boolean.md) | booléens                 |
|    [Char](./objects/Char.md)    | Caractère                |
|  [String](./objects/String.md)  | Chaîne de caractères     |
|   [Array](./objects/Array.md)   | Tableau d'objets         |
