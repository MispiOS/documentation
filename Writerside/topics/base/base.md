# Base

### Présentation

**Base** est un langage de programmation bas niveau créé par des étudiants de l'USMB afin de développer MispiOS. Il a avant tout un but ludique.

### Mots Clefs
---

|              Mot              | Description                                                                     |
|:-----------------------------:|:--------------------------------------------------------------------------------|
|           `import`            | permet d'importer un autre fichier de code base                                 |
|             `if`              | condition                                                                       |
|            `else`             | non respect condition                                                           |
|            `while`            | boucle tant que                                                                 |
|            `fnct`             | définition d'une fonction                                                       |
|            `break`            | permet de sortir d'une boucle                                                   |
|           `return`            | déclaration finale d'une fonction renvoyant une objet ou rien                   |
|            `null`             | pointeur vide                                                                   |
|             `asm`             | fonction pour écrire du code en assembleur                                      |
|     [`object`](Object.md)     | définition d'un objet                                                           |
|   [`init`](Object.md#init)    | fonction(s) d'initialisation d'un objet                                         |
|   [`self`](Object.md#self)    | représente l'objet dans son contenu                                             |
| [`op==`](Object.md#operators) | surcharge de l'opérateur conditionnel `==` pour les objets (en fonction)        |
| [`op<`](Object.md#operators)  | surcharge de l'opérateur conditionnel `<` pour les objets (en fonction)         |
| [`op>`](Object.md#operators)  | surcharge de l'opérateur conditionnel `>` pour les objets (en fonction)         |
| [`op<=`](Object.md#operators) | surcharge de l'opérateur conditionnel `=<` pour les objets (en fonction)        |
| [`op>=`](Object.md#operators) | surcharge de l'opérateur conditionnel `=>` pour les objets (en fonction)        |
| [`op+`](Object.md#operators)  | surcharge de l'opérateur `+` pour les objets (en fonction)                      |
| [`op-`](Object.md#operators)  | surcharge de l'opérateur `-` pour les objets (en fonction)                      |
| [`op*`](Object.md#operators)  | surcharge de l'opérateur `*` pour les objets (en fonction)                      |
| [`op/`](Object.md#operators)  | surcharge de l'opérateur `/` pour les objets (en fonction)                      |
| [`op%`](Object.md#operators)  | surcharge de l'opérateur `%` pour les objets (en fonction)                      |
| [`op**`](Object.md#operators) | surcharge de l'opérateur `**` pour les objets (en fonction)                     |
| [`op+=`](Object.md#operators) | surcharge de l'opérateur `+=` pour les objets (en fonction)                     |
| [`op-=`](Object.md#operators) | surcharge de l'opérateur `-=` pour les objets (en fonction)                     |
| [`op[]`](Object.md#operators) | surcharge du sélecteur d'indice d'itérable (en fonction)                        |
|            `void`             | type de retour d'une fonction lorsqu'elle ne retourne rien                      |
|      [`int`](Integer.md)      | référence au type [`Integer`](Integer.md)                                       |
|      [`float`](Float.md)      | référence au type [`Float`](Float.md)                                           |
|       [`char`](Char.md)       | référence au type [`Char`](Char.md)                                             |
|           `(` & `)`           | ouverture et fermeture d'arguments, de conditions et de priorités arithmétiques |
|           `{` & `}`           | ouverture et fermeture de bloc de code                                          |
|           `[` & `]`           | ouverture et fermeture du sélecteur d'indice d'un itérable                      |
|              `=`              | assignation                                                                     |
|              `+`              | addition                                                                        |
|              `-`              | soustraction                                                                    |
|              `*`              | multiplication                                                                  |
|              `/`              | division décimale                                                               |
|              `%`              | reste division euclidienne                                                      |
|             `**`              | exposant                                                                        |
|             `+=`              | réassignation via addition                                                      |
|             `-=`              | réassignation via soustraction                                                  |
|             `&&`              | et (conditionnel)                                                               |
|   <code>&#124;&#124;</code>   | ou (conditionnel)                                                               |
|              `!`              | non                                                                             |
|              `&`              | et (binaire)                                                                    |
|      <code>&#124;</code>      | ou (binaire)                                                                    |
|              `^`              | ou exclusif (binaire)                                                           |
|             `<<`              | décalage binaire vers la gauche                                                 |
|             `>>`              | décalage binaire vers la droite                                                 |
|             `==`              | égal (conditionnel)                                                             |
|              `<`              | inférieur (conditionnel)                                                        |
|              `>`              | supérieur (conditionnel)                                                        |
|             `<=`              | inférieur ou égal (conditionnel)                                                |
|             `>=`              | supérieur ou égal (conditionnel)                                                |
|             `!=`              | non égal / différent (conditionnel)                                             |
|             `!<`              | non inférieur (conditionnel) (eq: `>=`)                                         |
|             `!>`              | non supérieur (conditionnel) (eq: `<=`)                                         |
|              `;`              | fin d'instruction                                                               |
|             `//`              | début commentaire en ligne                                                      |
|             `/*`              | début commentaire multi-lignes                                                  |
|             `*/`              | fin commentaire multi-lignes                                                    |
|              `$`              | récupère le pointeur d'une variable                                             |
|              `&`              | récupère la variable d'un pointeur                                              |

### Types primaires
---

|        Nom        | Description              |
|:-----------------:|--------------------------|
| [int](Integer.md) | Nombres entiers relatifs |
| [float](Float.md) | Nombres à virgule        |
|  [char](Char.md)  | Caractères               |

### Fonctions par défaut
---

| Expression                 | Description                          |
|----------------------------|--------------------------------------|
| `asm(char[] assemblyCode)` | Permet d'exécuter du code assembleur |
