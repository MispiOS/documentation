# Base

### Identification
---
Nom : Base

Paradigmes : Fonctionnel et Orienté Objet

Compile vers : ASM -> Binaire (pour commencer) ; Binaire (quand le système fonctionnera)
### Mots Clefs
---

|            Mot            | Utilité                                                                                                               |
|:-------------------------:|:----------------------------------------------------------------------------------------------------------------------|
|           `if`            | condition                                                                                                             |
|          `else`           | non respect condition                                                                                                 |
|         `else-if`         | condition si non respect condition précédente                                                                         |
|          `while`          | boucle tant que                                                                                                       |
|        `function`         | mot définition fonction                                                                                               |
|         `public`          | accessibilité de fonction ou variable (globale) de partout                                                            |
|         `private`         | accessibilité de fonction ou variable (globale) dans même classe uniquement                                           |
|         `switch`          | bloc "multiconditionnel"                                                                                              |
|          `case`           | sélecteur de cas pour le switch                                                                                       |
|          `break`          | permet de sortir d'une boucle ou d'un switch                                                                          |
|         `return`          | déclaration finale d'une fonction renvoyant une objet ou rien                                                         |
|          `null`           | objet nul (sans existance)                                                                                            |
|           `void`           | type de retour d'une fonction lorsqu'elle ne retourne rien                                                               |
|         `(` & `)`         | ouverture et fermeture d'arguments, de conditions et de priorité                                                      |
|         `{` & `}`         | ouverture et fermeture de bloc de code                                                                                |
|            `=`            | assignation                                                                                                           |
|            `+`            | addition                                                                                                              |
|            `-`            | soustraction                                                                                                          |
|            `*`            | multiplication                                                                                                        |
|            `/`            | division                                                                                                              |
|            `%`            | reste division euclidienne                                                                                            |
|           `**`            | exposant                                                                                                              |
|           `&&`            | et (conditionnel)                                                                                                     |
| <code>&#124;&#124;</code> | ou (conditionnel)                                                                                                     |
|            `!`            | non                                                                                                                   |
|            `&`            | et (binaire)                                                                                                          |
|    <code>&#124;</code>    | ou (binaire)                                                                                                          |
|            `^`            | ou exclusif (binaire)                                                                                                 |
|           `<<`            | décalage binaire vers la gauche                                                                                       |
|           `>>`            | décalage binaire vers la droite                                                                                       |
|           `==`            | égal (conditionnel)                                                                                                   |
|            `<`            | inférieur (conditionnel)                                                                                              |
|            `>`            | supérieur (conditionnel)                                                                                              |
|           `<=`            | inférieur ou égal (conditionnel)                                                                                      |
|           `>=`            | supérieur ou égal (conditionnel)                                                                                      |
|           `!=`            | non égal / différent (conditionnel)                                                                                   |
|           `!<`            | non inférieur (conditionnel)                                                                                          |
|           `!>`            | non supérieur (conditionnel)                                                                                          |
|            `;`            | fin d'instruction                                                                                                     |
|         `string`          | référence au type [`String`](String.md)                                                                               |
|           `int`           | référence au type [`Integer`](Integer.md)                                                                             |
|          `float`          | référence au type [`Float`](Float.md)                                                                                 |
|          `bool`           | référence au type [`Boolean`](Boolean.md)                                                                             |
|          `char`           | référence au type [`Char`](Char.md)                                                                                   |
|           `//`            | début commentaire en ligne                                                                                            |
|           `/*`            | début commentaire multi-lignes                                                                                        |
|           `*/`            | fin commentaire multi-lignes                                                                                          |
|         `default`         | cas par défaut du switch                                                                                              |
|          `class`          | définition d'une classe d'objet                                                                                       |
|        `interface`        | définition d'une interface                                                                                            |
|        `abstract`         | mot clef qui se combine avec le `class` pour créer une classe abstraite ou devant une fonction d'une classe abstraite |
|         `extends`         | permet d'étendre une classe (à l'aide) d'une classe abstraite                                                         |
|       `implements`        | permet d'implémenter à une classe une seconde classe                                                                  |
|         `import`          | importe un fichier de code pour travailler avec                                                                       |
|         `static`          | Rend une méthode ou un attribut accessible depuis partout selon sa visibilité                                         |


### Objets par défaut
---

|            Nom            | Description              |
|:-------------------------:|--------------------------|
|    [Object](Object.md)    | Base de tous les objets  |
|   [Integer](Integer.md)   | Nombres entiers relatifs |
|     [Float](Float.md)     | Nombres à virgule        |
|   [Boolean](Boolean.md)   | booléens                 |
|      [Char](Char.md)      | Caractère                |
|    [String](String.md)    | Chaîne de caractères     |
|     [Array](Array.md)     | Tableau d'objets         |
