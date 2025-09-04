# object

Le mot clef `object` permet de représenter le concept d'objet dans le langage. Un objet peut contenir des variables (attributs) et des fonctions (méthodes).

#### Méthode `init` {id="init"}
---
La méthode `init` est la méthode appelée lors de la création de l'objet. Elle sert à initialiser les valeurs des attributs de l'objet et n'a pas de type de retour.

Celle-ci peut prendre autant d'argument de n'importe quel type (et de n'importe quel objet).

Il peut y avoir plusieurs méthodes `init` mais elles doivent avoir des types d'arguments différents.

#### `self` {id="self"}
---
Le mot clef `self` est uniquement présent dans les objets et permet d'identifier l'objet lui même.
Il est utile afin de ne pas confondre un attribut avec une variable dans une méthode (entre autre).

#### Méthodes de surcharge d'opérateurs {id="operators"}
---
La surcharge d'opérateur permet d'utiliser les opérateurs habituels sur des objets. Ils commencent tous par `op` et continuent par l'opérateur à surcharger (ex : `op==` surcharge l'opérateur conditionnel `==`).

Les méthodes de surcharge prennent uniquement un argument, cependant il peut être de n'importe quel type. De plus chaque méthode doit renvoyer un résultat (donc retour `void` impossible).

> Il n'est pas possible de surcharger deux fois le même opérateur avec le même type d'argument
{style="warning"}

> Il est uniquement possible de surcharger les opérateurs `==`, `<`, `>`, `<=`, `>=`, `+`, `-`, `*`, `/`, `%`, `**`, `+=`, `-=` et `[]`.
{style="note"}

#### Exemple
---
```base
object Vector {
    int x;
    int y;
    
    fnct init() {
        x = 0;
        y = 0;
    }
    
    fnct init(int x, int y) {
        self.x = x;
        self.y = y;
    }
    
    fnct Vector op*(int lambda) {
        return Vector(x * lambda, y * lambda);
    }
    
    fnct int op*(Vector v) {
        return x * v.x + y * v.y;
    }
}
```