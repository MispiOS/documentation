# Switch

Le switch est une simplification de l'arbre `if-else`.

```base
switch(obj) {
    case a:
        // TODO-a
        break;
    case b:
        // TODO-b
        break;
    default:
        // TODO-default
        break;
}
```

Le code ci-dessus revient à celui-ci :
```base
if(obj == a) {
    // TODO-a
} else-if(obj == b) {
    // TODO-b
} else {
    // TODO-default
}
```

Sachant que `a` et `b` sont du même type que `obj`.