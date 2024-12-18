# Base

### Identification
---
Nom: Base

Paradigmes: Fonctionnel et Orienté Objet

Compile vers: ASM -> Binaire (pour commencer) ; Binaire (quand le système fonctionnera)
### Mots Clefs
---

|                            Mot                             | Utilité                                                                     |
|:----------------------------------------------------------:|:----------------------------------------------------------------------------|
|                            `if`                            | condition                                                                   |
|                           `else`                           | non respect condition                                                       |
|                         `else-if`                          | condition si non respect condition précédente                               |
|                          `while`                           | boucle tant que                                                             |
|                         `function`                         | mot définition fonction                                                     |
|                          `public`                          | accessibilité de fonction ou variable (globale) de partout                  |
|                         `private`                          | accessibilité de fonction ou variable (globale) dans même classe uniquement |
|                          `switch`                          | bloc "multiconditionnel"                                                    |
|                          `return`                          | déclaration finale d'une fonction renvoyant une objet ou rien               |
|                           `null`                           | objet nul (sans existance)                                                  |
|                         `(` & `)`                          | ouverture et fermeture d'arguments, de conditions et de priorité            |
|                         `{` & `}`                          | ouverture et fermeture de bloc de code                                      |
|                            `=`                             | assignation                                                                 |
|                            `+`                             | addition                                                                    |
|                            `-`                             | soustraction                                                                |
|                            `*`                             | multiplication                                                              |
|                            `/`                             | division                                                                    |
|                            `%`                             | reste division euclidienne                                                  |
|                            `**`                            | exposant                                                                    |
|                            `&&`                            | et (conditonnel)                                                            |
|                 <code>&#124;&#124;</code>                  | ou (conditionnel)                                                           |
|                            `!`                             | non                                                                         |
|                            `&`                             | et (binaire)                                                                |
|                    <code>&#124;</code>                     | ou (binaire)                                                                |
|                            `^`                             | ou exclusif (binaire)                                                       |
|                            `<<`                            | décalage binaire vers la gauche                                             |
|                            `>>`                            | décalage binaire vers la droite                                             |
|                            `==`                            | égal (conditionnel)                                                         |
|                            `<`                             | inférieur (conditionnel)                                                    |
|                            `>`                             | supérieur (conditionnel)                                                    |
|                            `<=`                            | inférieur ou égal (conditionnel)                                            |
|                            `>=`                            | supérieur ou égal (conditionnel)                                            |
|                            `!=`                            | non égal / différent (conditionnel)                                         |
|                            `!<`                            | non inférieur (conditionnel)                                                |
|                            `!>`                            | non supérieur (conditionnel)                                                |
|                            `;`                             | fin d'instruction                                                           |
|                          `string`                          | référence au type [`String`](String.md)                                     |
|                           `int`                            | référence au type [`Integer`](Integer.md)                                   |
|                          `float`                           | référence au type [`Float`](Float.md)                                       |
|                           `bool`                           | référence au type [`Boolean`](Boolean.md)                                   |
|                           `char`                           | référence au type [`Char`](Char.md)                                         |
|                            `//`                            | début commentaire en ligne                                                  |
|                            `/*`                            | début commentaire multi-lignes                                              |
|                            `*/`                            | fin commentaire multi-lignes                                                |


### Objets par défaut
---

|            Nom            | Description              |
|:-------------------------:| ------------------------ |
|    [Object](Object.md)    | Base de tous les objets  |
|   [Integer](Integer.md)   | Nombres entiers relatifs |
|     [Float](Float.md)     | Nombres à virgule        |
|   [Boolean](Boolean.md)   | booléens                 |
|      [Char](Char.md)      | Caractère                |
|    [String](String.md)    | Chaîne de caractères     |
|     [Array](Array.md)     | Tableau d'objets         |
