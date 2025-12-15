# Operateur

Les opérateurs sont différentes actions permettant de faire des calculs entre deux variables (littérales ou définies).

#### Assignation {id="asign"}
---
L'assignation (notée `=`) est un opérateur permettant de donner une valeur à une variable lors de sa définition ou pour la réassigner.

Exemples : 
```base
int x = 0;
x = 5;
```

On assigne d'abord `x` à `0` avant de le réassigner à `5`.

> Il ne faut pas confondre l'assignation (`=`) et l'[opérateur conditionnel d'égalité (`==`)](Conditional.md#op)
{style="warning"}

#### Arithmétique {id="arithm"}
---
Les opérateurs arithmétiques permettent de faire des calculs mathématiques "simple".

Ils contiennent l'addition (`+`), la soustraction (`-`), la multiplication (`*`), la division (`/`),
le reste de la division euclidienne / le modulo (`%`), et l'exposant (`**`).

> La division est entière lorsqu'on la fait avec deux entiers ([`int`](Integer.md) ou [`char`](Char.md)).
> Cependant, celle-ci est décimale si au moins l'un des membres est un [nombre flottant](Float.md).
{style="warning"}


#### Arithmético-assignatoire {id="arithm-asign"}
---
Il existe aussi des opérateurs mélangeant l'opérateur d'assignation (`=`) et les opérateurs arithmétiques.
Ceux-ci sont simplement les opérateurs arithmétiques après lesquelles on fait suivre l'opérateur d'assignation.

On obtient donc les opérateurs suivants : `+=`, `-=`, `*=`, `/=`, `%=` et `**=`.
Ils effectuent les mêmes actions que les opérateurs arithmétiques d'origines, mais avec une syntaxe un peu différente :
```base
int x = 0;
x += 5;
x **= 2;
```

On définit `x` à `0`, ajoute `5` à `x` (`x = 5`), met `x` à la puissance `2` (donc `x = 25`).