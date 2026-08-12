============================================================
                 HELP — THÉORÈMES MATHÉMATIQUES
============================================================

Le module permet d'utiliser des théorèmes et formules
mathématiques directement depuis le prompt.

Syntaxe générale :

    theorem_nom(...)

ou avec ton système :

    math_theorem_nom(...)


============================================================
                    GÉOMÉTRIE
============================================================

THÉORÈME DE PYTHAGORE
------------------------------------------------------------

    pythagore(a, b)

Calcule l'hypoténuse d'un triangle rectangle :

    c = sqrt(a² + b²)

Exemple :

    pythagore(3,4)

Résultat :

    5


PYTHAGORE — CÔTÉ
------------------------------------------------------------

    pythagore_cote(c, a)

Calcule le deuxième côté :

    b = sqrt(c² - a²)


DISTANCE ENTRE DEUX POINTS
------------------------------------------------------------

    distance_points(x1,y1,x2,y2)

Formule :

    d = sqrt((x2-x1)² + (y2-y1)²)

Exemple :

    distance_points(0,0,3,4)

Résultat :

    5


MILIEU D'UN SEGMENT
------------------------------------------------------------

    milieu_segment(x1,y1,x2,y2)

Formule :

    M = ((x1+x2)/2, (y1+y2)/2)


PENTE D'UNE DROITE
------------------------------------------------------------

    pente(x1,y1,x2,y2)

Formule :

    m = (y2-y1)/(x2-x1)


ÉQUATION D'UNE DROITE
------------------------------------------------------------

    droite(x1,y1,x2,y2)

Retourne l'équation de la droite passant
par deux points.


============================================================
                    TRIANGLES
============================================================

AIRE D'UN TRIANGLE
------------------------------------------------------------

    aire_triangle(base, hauteur)

Formule :

    A = (base × hauteur) / 2


FORMULE DE HÉRON
------------------------------------------------------------

    heron(a,b,c)

Calcule l'aire d'un triangle à partir
de ses trois côtés.

    s = (a+b+c)/2

    A = sqrt(s(s-a)(s-b)(s-c))


THÉORÈME DES COSINUS
------------------------------------------------------------

    cosinus(a,b,C)

Formule :

    c² = a² + b² - 2ab cos(C)


THÉORÈME DES SINUS
------------------------------------------------------------

    sinus_loi(a,A,b)

Formule :

    a/sin(A) = b/sin(B)


============================================================
                    CERCLES
============================================================

AIRE D'UN CERCLE
------------------------------------------------------------

    aire_cercle(r)

Formule :

    A = πr²


CIRCONFÉRENCE
------------------------------------------------------------

    circonference(r)

Formule :

    C = 2πr


DIAMÈTRE
------------------------------------------------------------

    diametre(r)

Formule :

    d = 2r


RAYON
------------------------------------------------------------

    rayon(d)

Formule :

    r = d/2


============================================================
                    RECTANGLE
============================================================

AIRE
------------------------------------------------------------

    aire_rectangle(longueur, largeur)

    A = L × l


PÉRIMÈTRE
------------------------------------------------------------

    perimetre_rectangle(longueur, largeur)

    P = 2(L+l)


============================================================
                     CARRÉ
============================================================

AIRE
------------------------------------------------------------

    aire_carre(cote)

    A = côté²


PÉRIMÈTRE
------------------------------------------------------------

    perimetre_carre(cote)

    P = 4 × côté


DIAGONALE
------------------------------------------------------------

    diagonale_carre(cote)

    d = côté × sqrt(2)


============================================================
                    VOLUMES
============================================================

CUBE
------------------------------------------------------------

    volume_cube(cote)

    V = côté³


PAVÉ DROIT
------------------------------------------------------------

    volume_pave(longueur, largeur, hauteur)

    V = L × l × h


CYLINDRE
------------------------------------------------------------

    volume_cylindre(rayon, hauteur)

    V = πr²h


CÔNE
------------------------------------------------------------

    volume_cone(rayon, hauteur)

    V = (πr²h)/3


SPHÈRE
------------------------------------------------------------

    volume_sphere(rayon)

    V = (4πr³)/3


AIRE SPHÈRE
------------------------------------------------------------

    aire_sphere(rayon)

    A = 4πr²


============================================================
                ALGÈBRE
============================================================

IDENTITÉS REMARQUABLES
------------------------------------------------------------

    identite_carre_plus(a,b)

    (a+b)² = a² + 2ab + b²


    identite_carre_moins(a,b)

    (a-b)² = a² - 2ab + b²


    difference_carres(a,b)

    a²-b² = (a-b)(a+b)


CUBE D'UNE SOMME
------------------------------------------------------------

    cube_somme(a,b)

    (a+b)³ =
    a³ + 3a²b + 3ab² + b³


CUBE D'UNE DIFFÉRENCE
------------------------------------------------------------

    cube_difference(a,b)

    (a-b)³ =
    a³ - 3a²b + 3ab² - b³


============================================================
             ÉQUATIONS DU SECOND DEGRÉ
============================================================

DISCRIMINANT
------------------------------------------------------------

    discriminant(a,b,c)

Formule :

    Δ = b² - 4ac


RÉSOLUTION DU SECOND DEGRÉ
------------------------------------------------------------

    second_degre(a,b,c)

Équation :

    ax² + bx + c = 0

Solutions :

    x = (-b ± sqrt(Δ))/(2a)


============================================================
                 PROPORTIONNALITÉ
============================================================

PRODUIT EN CROIX
------------------------------------------------------------

    produit_croise(a,b,c)

Si :

    a/b = c/x

alors :

    x = (b×c)/a


POURCENTAGE
------------------------------------------------------------

    pourcentage(valeur, pourcent)

Formule :

    résultat = valeur × pourcent / 100


AUGMENTATION
------------------------------------------------------------

    augmentation(valeur, pourcent)

Formule :

    résultat = valeur × (1 + pourcent/100)


DIMINUTION
------------------------------------------------------------

    diminution(valeur, pourcent)

Formule :

    résultat = valeur × (1 - pourcent/100)


============================================================
                 SUITES
============================================================

SUITE ARITHMÉTIQUE
------------------------------------------------------------

    suite_arithmetique(u0,r,n)

Formule :

    un = u0 + nr


SOMME SUITE ARITHMÉTIQUE
------------------------------------------------------------

    somme_arithmetique(u0,r,n)

Formule :

    S = (n+1)(u0+un)/2


SUITE GÉOMÉTRIQUE
------------------------------------------------------------

    suite_geometrique(u0,q,n)

Formule :

    un = u0 × qⁿ


SOMME SUITE GÉOMÉTRIQUE
------------------------------------------------------------

    somme_geometrique(u0,q,n)

Formule :

    S = u0(1-qⁿ)/(1-q)


============================================================
                  PROBABILITÉS
============================================================

PROBABILITÉ SIMPLE
------------------------------------------------------------

    probabilite(cas_favorables, cas_possibles)

Formule :

    P = cas_favorables / cas_possibles


PROBABILITÉ CONDITIONNELLE
------------------------------------------------------------

    probabilite_conditionnelle(A_et_B,B)

Formule :

    P(A|B) = P(A∩B)/P(B)


FORMULE DE BAYES
------------------------------------------------------------

    bayes(A,B)

Formule :

    P(A|B) = P(B|A)P(A)/P(B)


============================================================
                  STATISTIQUES
============================================================

MOYENNE
------------------------------------------------------------

    moyenne(...)


MÉDIANE
------------------------------------------------------------

    mediane(...)


MODE
------------------------------------------------------------

    mode(...)


VARIANCE
------------------------------------------------------------

    variance(...)


ÉCART-TYPE
------------------------------------------------------------

    ecart_type(...)


============================================================
                 LOGARITHMES
============================================================

PROPRIÉTÉ DU PRODUIT
------------------------------------------------------------

    log_produit(a,b)

    log(ab) = log(a) + log(b)


PROPRIÉTÉ DU QUOTIENT
------------------------------------------------------------

    log_quotient(a,b)

    log(a/b) = log(a) - log(b)


PROPRIÉTÉ DE LA PUISSANCE
------------------------------------------------------------

    log_puissance(a,n)

    log(aⁿ) = n log(a)


============================================================
                  EXPONENTIELLES
============================================================

EXPONENTIELLE D'UNE SOMME
------------------------------------------------------------

    exp_somme(a,b)

    e^(a+b) = e^a × e^b


EXPONENTIELLE D'UNE DIFFÉRENCE
------------------------------------------------------------

    exp_difference(a,b)

    e^(a-b) = e^a / e^b


============================================================
                TRIGONOMÉTRIE
============================================================

IDENTITÉ FONDAMENTALE
------------------------------------------------------------

    identite_trigonometrique(x)

    sin²(x) + cos²(x) = 1


TANGENTE
------------------------------------------------------------

    tangente(sin_x, cos_x)

    tan(x) = sin(x)/cos(x)


============================================================
                 COMPLEXES
============================================================

MODULE D'UN COMPLEXE
------------------------------------------------------------

    module_complexe(a,b)

Pour :

    z = a + bi

Alors :

    |z| = sqrt(a²+b²)


CONJUGUÉ
------------------------------------------------------------

    conjugue(a,b)

Pour :

    z = a + bi

Le conjugué est :

    z̄ = a - bi


============================================================
                  FACTORIELLE
============================================================

FACTORIELLE
------------------------------------------------------------

    factorielle(n)

    n! = n × (n-1) × ... × 1


============================================================
              COMBINAISONS
============================================================

COMBINAISON
------------------------------------------------------------

    combinaison(n,k)

Formule :

    C(n,k) = n! / (k!(n-k)!)


ARRANGEMENT
------------------------------------------------------------

    arrangement(n,k)

Formule :

    A(n,k) = n! / (n-k)!


============================================================
              CONSTANTES IMPORTANTES
============================================================

    PI
    E
    TAU
    INF


============================================================
             THÉORÈMES CLASSIQUES
============================================================

Pythagore
    pythagore(...)

Théorème des cosinus
    cosinus(...)

Théorème des sinus
    sinus_loi(...)

Formule de Héron
    heron(...)

Théorème de Thalès
    thales(...)

Théorème de Bayes
    bayes(...)

Identités remarquables
    identite_carre_plus(...)
    identite_carre_moins(...)
    difference_carres(...)

============================================================
             FONCTIONS COMPOSABLES
============================================================

Les théorèmes peuvent être combinés avec
les fonctions mathématiques.

Exemple :

    pythagore(3,4)

    sqrt(3**2+4**2)

Même résultat :

    5


Exemple complexe :

    sqrt(
        pythagore(3,4)**2
        + 10**2
    )


Exemple :

    aire_cercle(
        pythagore(3,4)
    )


============================================================
                  CALCUL DIRECT
============================================================

Le système accepte également directement :

    5+2*4

    (5+2)*4

    2**10

    sqrt(25)+5

    sin(PI/2)

    sqrt(3**2+4**2)


============================================================