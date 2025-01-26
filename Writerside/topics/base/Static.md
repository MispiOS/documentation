# Static

Le mot clef `static` permet de rendre une méthode ou un attribut dans toutes les classes sans avoir besoin de créer une instance de la classe dans lequel il se trouve.

Une méthode `static` ne peut accéder à un attribut de sa classe que s'il est aussi `static`.

```base
class Foo {
    public static Object bar() {
        // TODO
    }
}

class Bar {
    public void func() {
        Foo.bar();
    }
}
```