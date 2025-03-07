# Fonction

Une fonction est un bloc de code qui peut être appellé dans une partie du code.

Elle sert généralement à réduire le nombre de répétitions ainsi qu'à structurer le code.

Elle se construit grâce au mot clef `function` suivit du type de retour, du nom de la fonction et des paramètres entre parenthèses.

Si le type de retour est différent de `void`, la fonction doit se terminer par le retour d'une valeur du même type grâce au mot clef `return`.

```base
function void myFunction(Object arg1, Object arg2) {
    // TODO
}

function int myIntFunction() {
    // TODO
    return -1;
}
```

Si une fonction ne retourne rien, il est tout de même possible d'utiliser le `return` mais sans élément à la suite afin d'interrompre l'exécution de la fonction.