# Classes

Une classe est une structure de donnés permettant de représenter une idée et de la réutiliser facilement.

Une classe peut contenir des méthodes (fonctions) et des attributs (variables) publiques ou privées.

### Méthode

La méthode `construct` est une méthode par défaut des classes, elle n'a pas de type de retour.
Elle permet de créer une instance de la classe grâce aux arguments donnés.

Il peut il y avoir plusieurs méthodes `construct` dans la même classe, et celles-ci peuvent être publiques ou privées.
Cependant, elles ne peuvent pas avoir les mêmes types d'argument dans le même ordre.

### Abstract

Les classes abstraites permettent de créer une classe ayant des méthodes non définies.
Celles-ci sont définie avec le mot clef `abstract` et n'ont pas de contenu.

Lorsqu'une classe normale est étendu (mot clef `extends`) d'une classe abstraite, il faut définir en elles les méthodes abstraites de la classe qui étend.

Si la classe qui est étendue est aussi abstraite, alors il n'est pas obligatoire de définir les méthodes abstraites de la classe qui étend.
Si les méthodes abstraites ne sont pas définie, c'est au tour de la classe qui est étendu par la seconde abstraite de définir les méthodes abstraites.

Il n'est possible d'intégrer qu'une unique 

Il est impossible de créer une instance d'une classe abstraite. Pour le faire, il faut qu'elle soit étendue dans une autre classe.

```base
abstract class Foo {
    public construct(Object o) {
        // TODO
    }
    
    private abstract void abstractMethod();
}
```

### Extends

Une classe peut étendre une autre classe en ajoutant lors de sa création le mot clef `extends` suivit du nom de la classe qui étend.

La classe étendue devra, si nécessaire, intégrer une méthode `construct` qui permet de créer l'instance de la classe intégrée grâce à la fonction clef `super`.

La classe étendue est une instance de la classe qui étend. Une classe ne peut faire qu'une extension.

```base
class Bar extends Foo {
    public construct(Object o1, Object o2, Object o3) {
        super(o1);
        // TODO
    }
    
    private void abstractMethod() {
        // TODO
    }
}
```

Les méthodes publiques de la classe qui étend sont accessibles par la classe étendue.

### Implements

Une classe peut en implémenter une ou plusieurs interfaces grâce au mot clef `implements` suivit du nom de la classe à implémenter ou des classes séparées par des virgules s'il y en a plusieurs.

Lorsqu'une interface est implémentée, ses méthodes doivent être définies dans la classe l'implémentant avec la même visibilité.

La classe implémentant est une instance de l'interface.

```base
class Foo implements IFirst, ISecond {
    private String firstInterfaceMethod(Object o) {
        // TODO
    }
    
    public void secondInterfaceMethod(Object o1, Object o2) {
        // TODO
    }
}
```

### Autre

Une classe ne peut être définie dans une autre classe