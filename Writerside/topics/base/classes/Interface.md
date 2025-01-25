# Interfaces 

Les interfaces sont des sortes de classes. Cependant, les interfaces ne sont qu'un squelette d'une classes.
En effet, les méthodes des interfaces n'ont pas de contenu. De plus, les interfaces n'ont pas de constructeur.

Les méthodes des interfaces doivent être implémentées dans la classe qui l'implémente (mot clef `implements`).

```base
interface Foo {
    public void bar(Object o);
    
    private Object fooBar();
}
```