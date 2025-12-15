# Structures conditionnelles

Les structures conditionnelles permettent de séparer dans un bloc une partie du code qui ne doit être executée que lorsqu'une condition est remplie.

Les conditions sont en réalité des entiers. Si l'entier est `0` alors la condition est fausse, tandis que si l'entier est différent de `0`, alors la condition est vraie.

#### Opérateurs conditionnels {id="op"}
---
Bien qu'en réalité des entiers, les conditions peuvent s'exprimer à l'aide d'opérateurs conditionnels (`==` [égal], `<` [inférieur à], `>` [supérieur à], `<=` [inférieur ou égal à], `>=` [supérieur ou égal]),
de connecteurs logiques (`&&` [et], `||` [ou]) et de la négation (`!` [non]).

> Les opérateurs conditionnels et les connecteurs logiques nécessitent deux membres pour effectuer une opération.
{style="note"}

La négation se fait sur l'intégralité des conditions et non pas sur les opérateurs conditionnels.
Exemple : `!(1 == 2)`

Faire une négation sur un nombre différent de `0` donne `0` et faire une négation sur `0` donne `1`.

#### `if` et `else` {id="if-else"}
---
`if` et `else` sont les structures conditionnelles de base. Avec celles-ci, il est possible de recréer les suivantes.

Elles s'utilisent de la manière suivante :
```base
if(statement) {
    // TODO TRUE
} else {
    // TODO FALSE
}
```

Cependant, si nous voulons rajouter une seconde condition avant le `else`, on pourrait naïvement être amené à écrire ceci :
```base
if(statement1) {
    // TODO TRUE 1
} else {
    if(statement2) {
        // TODO TRUE 2
    } else {
        // TODO FALSE
    }
}
```
Mais il est possible d'effectuer la même chose de manière plus élégante :
```base
if(statement1) {
    // TODO TRUE 1
} else if(statement2) {
    // TODO TRUE 2
} else {
    // TODO FALSE
}
```

#### while {id="while"}
---
La boucle while permet d'exécuter un bloc de code en boucle le temps qu'une condition est vérifiée.

Elle a la forme suivante :
```base
while(statement) {
    // TODO
}
```

Cependant, il est parfois nécessaire d'exécuter cette suite d'instruction au minimum une fois.
Il est donc possible d'utiliser à la place une boucle `do while`.

Celle-ci s'écrit de la manière suivante :
```base
do {
    // TODO
} while(statement);
```

Il est possible de vouloir quitter la boucle en plein milieu de celle-ci.
Pour se faire, il suffit d'utiliser l'instruction `break` à l'endroit désiré.

Il est aussi possible de vouloir passer les étapes qui suivent dans une boucle et d'aller directement à la condition pour exécuter la boucle à nouveau.
Pour réaliser cela, il est possible d'utiliser l'instruction `continue` au moment voulu.