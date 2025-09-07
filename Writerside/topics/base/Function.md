# Fonction

Les fonctions sont des blocks de code pouvant être appelé n'importe où dans le code (sauf pour les [méthodes](types/Object.md#methode)).
Elles ont pour but d'éviter les répétitions et de structurer le code.

#### Arguments {id="args"}
---
Les fonctions peuvent être appelées avec des arguments. Ceux-ci ont pour but de modifier le comportement de la fonction ou la valeur retournée par celle-ci.

Les arguments ont un type et un nom et se comporte telles des variables dans le contenu de la fonction.

De plus, ils ne sont pas accessibles en dehors de la fonction.

> Les arguments sont définis pour la fonction après son nom entre parenthèses et séparés par des virgules entre eux.
{style="note"}

> Il est également possible qu'une fonction n'ait pas d'argument.

#### Return {id="return"}
---
`return` est le mot clef permettant de renvoyer une valuer à la fin d'une fonction.

> La valeur retournée doit être du même type que le type de retour de la fonction ! 
{style="warning"}

Le mot clef s'utilise s'utilise donc comme ceci : ``return val;``.

#### `void` {id="void"}
---
`void` est un type de retour particulier. Il représente le fait que la fonction ne retourne rien.

Il est donc possible d'écrire `return;` pour terminer la fonction ou même ne rien mettre.

#### Définition
---
Une fonction se définie grâce au mot clef `fnct`, à un type de retour et d'une valeur de retour du même type, à un nom et à des arguments comme ci-dessous :
```base
fnct TYPE name(TYPE0 arg0, TYPE1 arg1, ..., TYPEN argN) {
    // TODO
    return val; // TYPE val = ...;
}
```

> Le type de retour peut aussi être un [objet](Object.md).
{style="note"}


#### Fonctions par défaut {id="default"}
---
| Type retour | Fonction           | Description                      |
|-------------|--------------------|----------------------------------|
| `void`      | `asm(char[] code)` | Execute le code assembleur donné |
