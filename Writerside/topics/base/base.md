# Base

### Présentation

**Base** est un langage de programmation bas niveau créé par des étudiants de l'USMB (Université Savoie Mont-Blanc) afin de développer MispiOS.
Il a avant tout un but ludique.

### Mots Clefs
---

|                      Mot                       | Description                                                                                            |
|:----------------------------------------------:|:-------------------------------------------------------------------------------------------------------|
|             [`import`](Import.md)              | permet d'importer un autre fichier de code base                                                        |
|         [`if`](Conditional.md#if-else)         | condition                                                                                              |
|        [`else`](Conditional.md#if-else)        | non respect condition                                                                                  |
|        [`while`](Conditional.md#while)         | boucle tant que                                                                                        |
|          [`do`](Conditional.md#while)          | mot clef de boucle `do while`                                                                          |
|        [`break`](Conditional.md#while)         | permet de sortir de la boucle                                                                          |
|       [`continue`](Conditional.md#while)       | permet de revenir au début de la boucle à partir de la condition                                       |
|             [`fnct`](Function.md)              | définition d'une fonction                                                                              |
|         [`return`](Function.md#return)         | déclaration finale d'une fonction renvoyant une objet ou rien                                          |
|          [`asm`](Function.md#default)          | fonction pour écrire du code en assembleur                                                             |
|             [`object`](Object.md)              | définition d'un objet                                                                                  |
|            [`init`](Object.md#init)            | fonction(s) d'initialisation d'un objet                                                                |
|            [`self`](Object.md#self)            | représente l'objet dans son contenu                                                                    |
|         [`op==`](Object.md#operators)          | surcharge de l'opérateur conditionnel `==` pour les objets (en fonction)                               |
|          [`op<`](Object.md#operators)          | surcharge de l'opérateur conditionnel `<` pour les objets (en fonction)                                |
|          [`op>`](Object.md#operators)          | surcharge de l'opérateur conditionnel `>` pour les objets (en fonction)                                |
|         [`op<=`](Object.md#operators)          | surcharge de l'opérateur conditionnel `=<` pour les objets (en fonction)                               |
|         [`op>=`](Object.md#operators)          | surcharge de l'opérateur conditionnel `=>` pour les objets (en fonction)                               |
|          [`op+`](Object.md#operators)          | surcharge de l'opérateur `+` pour les objets (en fonction)                                             |
|          [`op-`](Object.md#operators)          | surcharge de l'opérateur `-` pour les objets (en fonction)                                             |
|          [`op*`](Object.md#operators)          | surcharge de l'opérateur `*` pour les objets (en fonction)                                             |
|          [`op/`](Object.md#operators)          | surcharge de l'opérateur `/` pour les objets (en fonction)                                             |
|          [`op%`](Object.md#operators)          | surcharge de l'opérateur `%` pour les objets (en fonction)                                             |
|         [`op**`](Object.md#operators)          | surcharge de l'opérateur `**` pour les objets (en fonction)                                            |
|         [`op+=`](Object.md#operators)          | surcharge de l'opérateur `+=` pour les objets (en fonction)                                            |
|         [`op-=`](Object.md#operators)          | surcharge de l'opérateur `-=` pour les objets (en fonction)                                            |
|         [`op[]`](Object.md#operators)          | surcharge du sélecteur d'indice d'itérable (en fonction)                                               |
|           [`void`](Function.md#void)           | type de retour d'une fonction lorsqu'elle ne retourne rien                                             |
|              [`int`](Integer.md)               | référence au type [`Integer`](Integer.md)                                                              |
|              [`float`](Float.md)               | référence au type [`Float`](Float.md)                                                                  |
|               [`char`](Char.md)                | référence au type [`Char`](Char.md)                                                                    |
|                   `(` & `)`                    | ouverture et fermeture d'arguments, de conditions et de priorités arithmétiques                        |
|                   `{` & `}`                    | ouverture et fermeture de bloc de code                                                                 |
|                   `[` & `]`                    | ouverture et fermeture du sélecteur d'indice d'un itérable                                             |
|                      `"`                       | ouverture et fermeture pour un caractère alphanumérique (`char`) ou une chaîne de caractère (`char[]`) |
|                      `'`                       | ouverture et fermeture pour un caractère alphanumérique (`char`)                                       |
|                      `=`                       | assignation                                                                                            |
|                      `+`                       | addition                                                                                               |
|                      `-`                       | soustraction                                                                                           |
|                      `*`                       | multiplication                                                                                         |
|                      `/`                       | division décimale                                                                                      |
|                      `%`                       | reste division euclidienne                                                                             |
|                      `**`                      | exposant                                                                                               |
|                      `+=`                      | réassignation via addition                                                                             |
|                      `-=`                      | réassignation via soustraction                                                                         |
|                      `&`                       | et (binaire)                                                                                           |
|              <code>&#124;</code>               | ou (binaire)                                                                                           |
|                      `^`                       | ou exclusif (binaire)                                                                                  |
|                      `<<`                      | décalage binaire vers la gauche                                                                        |
|                      `>>`                      | décalage binaire vers la droite                                                                        |
|           [`&&`](Conditional.md#op)            | et (conditionnel)                                                                                      |
| [<code>&#124;&#124;</code>](Conditional.md#op) | ou (conditionnel)                                                                                      |
|            [`!`](Conditional.md#op)            | non (conditionnel)                                                                                     |
|           [`==`](Conditional.md#op)            | égal (conditionnel)                                                                                    |
|            [`<`](Conditional.md#op)            | inférieur (conditionnel)                                                                               |
|            [`>`](Conditional.md#op)            | supérieur (conditionnel)                                                                               |
|           [`<=`](Conditional.md#op)            | inférieur ou égal (conditionnel)                                                                       |
|           [`>=`](Conditional.md#op)            | supérieur ou égal (conditionnel)                                                                       |
|                      `;`                       | fin d'instruction                                                                                      |
|                      `//`                      | début commentaire en ligne                                                                             |
|                      `/*`                      | début commentaire multi-lignes                                                                         |
|                      `*/`                      | fin commentaire multi-lignes                                                                           |
|                      `$`                       | récupère le pointeur d'une variable                                                                    |
|                      `&`                       | récupère la variable d'un pointeur                                                                     |

### Structures
---

| Nom     | Description                                                           |
|---------|-----------------------------------------------------------------------|
| `array` | Tableau d'une taille donnée ne contenant qu'un unique type de données |
