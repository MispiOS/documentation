# Base

### Présentation

**Base** est un langage de programmation bas niveau créé par des étudiants de l'USMB (Université Savoie Mont-Blanc) afin de développer MispiOS.
Il a avant tout un but ludique.

Tout le code de **Base** se trouve dans des [fonctions](Function.md) ou des [objets](Object.md).

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
|            [`=`](Operator.md#asign)            | assignation                                                                                            |
|           [`+`](Operator.md#arithm)            | addition                                                                                               |
|           [`-`](Operator.md#arithm)            | soustraction                                                                                           |
|           [`*`](Operator.md#arithm)            | multiplication                                                                                         |
|           [`/`](Operator.md#arithm)            | division                                                                                               |
|           [`%`](Operator.md#arithm)            | reste de la division euclidienne / modulo                                                              |
|           [`**`](Operator.md#arithm)           | exposant                                                                                               |
|        [`+=`](Operator.md#arithm-asign)        | réassignation via addition                                                                             |
|        [`-=`](Operator.md#arithm-asign)        | réassignation via soustraction                                                                         |
|        [`*=`](Operator.md#arithm-asign)        | réassignation via multiplication                                                                       |
|        [`/=`](Operator.md#arithm-asign)        | réassignation via division                                                                             |
|        [`%=`](Operator.md#arithm-asign)        | réassignation via modulo                                                                               |
|       [`**=`](Operator.md#arithm-asign)        | réassignation via exposant                                                                             |
|             [`&`](BitOperator.md)              | et (binaire)                                                                                           |
|     [<code>&#124;</code>](BitOperator.md)      | ou (binaire)                                                                                           |
|             [`^`](BitOperator.md)              | ou exclusif (binaire)                                                                                  |
|             [`<<`](BitOperator.md)             | décalage binaire vers la gauche                                                                        |
|             [`>>`](BitOperator.md)             | décalage binaire vers la droite                                                                        |
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
