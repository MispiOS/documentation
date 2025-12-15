# Opérateur binaire

Les opérateurs de bits permettent d'effectuer des opérations basiques sur les bits.

Ils contiennent les opérateurs ET (`&`), OU (`|`), et OU-EXCLUSIF / XOR (`^`) ansi que les décalages binaires vers la gauche (`<<`) et les décalages binaires vers la droite (`>>`).

Les opérateurs ET, OU et XOR s'utilisent entre deux valeurs binaires (exemple : `5 & 3` donne `1`).

Les décalages binaires s'effectuent sur une seule valeur binaire et grâce à un entier qui représente le nombre de colonnes pour le décalage
(exemple : `5 << 2` donne `20`).

> Décaler les bits de `1` colonne vers la gauche revient à multiplier la valeur binaire par `2`,
> tandis que décaler de `1` colonne vers la droite revient à diviser la valeur binaire par `2`.
{style="note"}