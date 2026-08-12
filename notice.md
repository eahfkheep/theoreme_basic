============================================================
                 HELP MATHEMATIQUES
============================================================

CALCUL DIRECT
------------------------------------------------------------

Tu peux directement écrire :

    5+2*4

Résultat :

    13


PARENTHESES
------------------------------------------------------------

    (5+2)*4

Résultat :

    28


OPERATIONS
------------------------------------------------------------

    math_addition5+2
    math_soustraction10-3
    math_multiplication5*4
    math_division20/4
    math_puissance2**8
    math_modulo10%3
    math_division_entiere10//3


FONCTIONS DE BASE
------------------------------------------------------------

    math_abs(-10)
    math_sqrt(25)
    math_cbrt(27)
    math_pow(2,8)


LOGARITHMES
------------------------------------------------------------

    math_exp(2)
    math_log(10)
    math_log10(100)
    math_log2(8)


TRIGONOMETRIE
------------------------------------------------------------

    math_sin(0)
    math_cos(0)
    math_tan(0)

    math_asin(1)
    math_acos(1)
    math_atan(1)
    math_atan2(1,1)


HYPERBOLIQUE
------------------------------------------------------------

    math_sinh(1)
    math_cosh(1)
    math_tanh(1)

    math_asinh(1)
    math_acosh(1)
    math_atanh(0.5)


ARRONDIS
------------------------------------------------------------

    math_floor(4.9)
    math_ceil(4.1)
    math_trunc(4.9)
    math_fabs(-10.5)


NOMBRES
------------------------------------------------------------

    math_factorial(5)
    math_pgcd(12,18)
    math_ppcm(4,6)


MIN / MAX
------------------------------------------------------------

    math_min(5,2,8)
    math_max(5,2,8)


STATISTIQUES
------------------------------------------------------------

    math_moyenne(10,20,30)
    math_mediane(10,20,30)
    math_mode(1,2,2,3)
    math_variance(10,20,30)
    math_ecart_type(10,20,30)


CONSTANTES
------------------------------------------------------------

    math_PI
    math_E
    math_TAU
    math_INF


============================================================
                 FONCTIONS COMPOSEES
============================================================

Les fonctions peuvent être combinées entre elles.

Exemple :

    math_sqrt(math_pow(3,2)+math_pow(4,2))

Résultat :

    5.0


Exemple :

    math_sqrt(
        math_pow(3,2)
        + math_pow(4,2)
        + math_factorial(3)
        + math_abs(-10)
    )


Exemple :

    math_max(
        math_sqrt(16),
        math_factorial(5),
        math_pow(2,8),
        math_abs(-500)
    )


============================================================
             CALCULS COMPLETEMENT LIBRES
============================================================

Tu n'es pas obligé d'utiliser math_.

Tu peux écrire :

    5+2*4

    (5+2)*4

    10/2+3

    2**8

    10%3


Tu peux également mélanger les deux :

    5+math_sqrt(25)*2

    math_factorial(5)+2**8

    math_sqrt(3**2+4**2)


============================================================
