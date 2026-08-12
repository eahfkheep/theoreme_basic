ChatGPT a dit :
NOTICE COMPLÈTE — Bibliothèque theoremes_mathematiques
1. Présentation

theoremes_mathematiques est une bibliothèque Python permettant d'exécuter des théorèmes, formules et relations mathématiques à partir d'une expression textuelle.

Elle permet notamment de travailler avec :

    la géométrie ;
    les triangles ;
    la trigonométrie ;
    les aires ;
    les volumes ;
    l'algèbre ;
    les équations du second degré ;
    les identités remarquables ;
    les suites ;
    les probabilités ;
    la théorie des nombres ;
    certains théorèmes classiques.

La bibliothèque utilise une syntaxe simple :

theoreme_nom(parametre1,parametre2,...)

2. Utilisation générale

Une commande peut être envoyée directement au système :

theoreme_pythagore(3,4)

Résultat :

5.0

Autre exemple :

theoreme_aire_cercle(5)

Résultat :

78.53981633974483

3. Géométrie
Théorème de Pythagore

theoreme_pythagore(a,b)

Calcule l'hypoténuse d'un triangle rectangle :

c = √(a² + b²)

Exemple :

theoreme_pythagore(3,4)

Résultat :

5.0

Réciproque de Pythagore

theoreme_pythagore_inverse(a,b,c)

Détermine si un triangle est rectangle.

Exemple :

theoreme_pythagore_inverse(3,4,5)

Résultat :

True

Théorème de Thalès

theoreme_thales(a,b,c)

Utilise une proportion :

a / b = c / x

et calcule :

x = (b × c) / a

Exemple :

theoreme_thales(2,4,6)

Distance entre deux points

theoreme_distance(x1,y1,x2,y2)

Formule :

d = √((x2-x1)² + (y2-y1)²)

Exemple :

theoreme_distance(0,0,3,4)

Résultat :

5.0

Milieu d'un segment

theoreme_milieu(x1,y1,x2,y2)

Formule :

M = ((x1+x2)/2 , (y1+y2)/2)

Exemple :

theoreme_milieu(0,0,4,6)

Résultat :

(2.0,3.0)

Pente d'une droite

theoreme_pente(x1,y1,x2,y2)

Formule :

m = (y2-y1)/(x2-x1)

Exemple :

theoreme_pente(0,0,2,4)

Résultat :

2.0

Équation d'une droite

theoreme_equation_droite(x1,y1,x2,y2)

Détermine les coefficients m et p de :

y = mx + p

Exemple :

theoreme_equation_droite(0,2,2,6)

Résultat :

(2.0,2.0)

4. Triangle
Formule de Héron

theoreme_heron(a,b,c)

Calcule l'aire d'un triangle à partir de ses trois côtés.

s = (a+b+c)/2

A = √(s(s-a)(s-b)(s-c))

Exemple :

theoreme_heron(3,4,5)

Résultat :

6.0

Loi des cosinus

theoreme_loi_cosinus(a,b,angle)

Formule :

c² = a² + b² - 2ab cos(C)

L'angle est donné en degrés.

Exemple :

theoreme_loi_cosinus(3,4,90)

Résultat :

5.0

Loi des sinus

theoreme_loi_sinus(a,angle_a,angle_b)

Utilise :

a/sin(A) = b/sin(B)

Exemple :

theoreme_loi_sinus(10,30,45)

5. Aires
Triangle

theoreme_aire_triangle(base,hauteur)

Formule :

A = (base × hauteur) / 2

Carré

theoreme_aire_carre(cote)

Formule :

A = cote²

Rectangle

theoreme_aire_rectangle(longueur,largeur)

Formule :

A = longueur × largeur

Cercle

theoreme_aire_cercle(rayon)

Formule :

A = πr²

Exemple :

theoreme_aire_cercle(5)

Circonférence

theoreme_circonference_cercle(rayon)

Formule :

C = 2πr

6. Volumes
Cube

theoreme_volume_cube(cote)

Formule :

V = cote³

Pavé droit

theoreme_volume_pave(longueur,largeur,hauteur)

Formule :

V = longueur × largeur × hauteur

Cylindre

theoreme_volume_cylindre(rayon,hauteur)

Formule :

V = πr²h

Sphère

theoreme_volume_sphere(rayon)

Formule :

V = 4/3 πr³

7. Algèbre
Équation du second degré

theoreme_second_degre(a,b,c)

Résout :

ax² + bx + c = 0

Exemple :

theoreme_second_degre(1,-3,2)

Résultat :

(1.0,2.0)

Discriminant

theoreme_discriminant(a,b,c)

Formule :

Δ = b² - 4ac

Exemple :

theoreme_discriminant(1,-3,2)

Résultat :

1.0

Somme des racines

theoreme_somme_racines(a,b)

Formule :

x1 + x2 = -b/a

Produit des racines

theoreme_produit_racines(a,c)

Formule :

x1 × x2 = c/a

8. Identités remarquables
Carré d'une somme

theoreme_carre_somme(a,b)

Formule :

(a+b)² = a² + 2ab + b²

Carré d'une différence

theoreme_carre_difference(a,b)

Formule :

(a-b)² = a² - 2ab + b²

Différence de deux carrés

theoreme_difference_carres(a,b)

Formule :

a²-b²

9. Suites
Suite arithmétique

theoreme_suite_arithmetique(u0,r,n)

Formule :

un = u0 + nr

Exemple :

theoreme_suite_arithmetique(2,3,5)

Résultat :

17.0

Somme arithmétique

theoreme_somme_arithmetique(premier,dernier,n)

Formule :

S = n(premier + dernier)/2

Suite géométrique

theoreme_suite_geometrique(u0,q,n)

Formule :

un = u0 × qⁿ

Somme géométrique

theoreme_somme_geometrique(u0,q,n)

Formule :

S = u0(1-qⁿ)/(1-q)

pour q ≠ 1.
10. Probabilités
Probabilité conditionnelle

theoreme_probabilite_conditionnelle(intersection,probabilite)

Formule :

P(A|B) = P(A∩B)/P(B)

Formule de Bayes

theoreme_bayes(p_b_sachant_a,p_a,p_b)

Formule :

P(A|B) = P(B|A)P(A)/P(B)

Probabilité totale

theoreme_probabilite_totale(...)

Additionne plusieurs probabilités pondérées.

Exemple :

theoreme_probabilite_totale(
    0.2*0.5,
    0.3*0.5
)

11. Moyenne pondérée

theoreme_moyenne_ponderee(valeur1,poids1,...)

Exemple :

theoreme_moyenne_ponderee(
    10,2,
    20,3
)

Correspond à :

(10×2 + 20×3)/(2+3)

Résultat :

16.0

12. Théorie des nombres
PGCD

theoreme_pgcd(a,b)

Exemple :

theoreme_pgcd(24,36)

Résultat :

12

PPCM

theoreme_ppcm(a,b)

Exemple :

theoreme_ppcm(4,6)

Résultat :

12

Nombre premier

theoreme_nombre_premier(n)

Exemple :

theoreme_nombre_premier(17)

Résultat :

True

Petit théorème de Fermat

theoreme_fermat_petit(a,p)

Utilise :

a^(p-1) ≡ 1 mod p

lorsque p est premier et que a et p sont premiers entre eux.

Exemple :

theoreme_fermat_petit(2,7)

13. Identité d'Euler

theoreme_identite_euler()

Évalue l'expression :

e^(iπ) + 1

qui est théoriquement égale à :

0

14. Composition des théorèmes

Les théorèmes peuvent être imbriqués.

Exemple :

theoreme_aire_cercle(
    theoreme_pythagore(3,4)
)

Le système calcule d'abord :

theoreme_pythagore(3,4)

puis utilise le résultat comme rayon du cercle.

Autre exemple :

theoreme_heron(
    3,
    4,
    theoreme_pythagore(3,4)
)

15. Combinaison avec les opérations

Les expressions peuvent également combiner les théorèmes avec les opérateurs mathématiques :

theoreme_pythagore(3,4) + 10

theoreme_aire_cercle(5) * 2

theoreme_pythagore(3+2,4*2)

Les opérateurs pris en charge sont :

+
-
*
/
**
%
//

ainsi que les signes unaires :

-5
+5

16. Constantes

Les constantes disponibles sont :

PI
E
TAU

Elles peuvent être utilisées dans les expressions.

Exemple :

theoreme_aire_cercle(5)

utilise automatiquement PI.
17. Sécurité

Le calculateur utilise le module Python ast avec une liste blanche des opérations et des théorèmes autorisés.

Les éléments suivants sont notamment refusés :

__import__(...)

os.system(...)

objet.fonction(...)

fonction_inconnue(...)

Les arguments nommés sont également interdits.

La bibliothèque n'exécute donc pas directement l'expression avec eval().
18. Format des erreurs

Quelques erreurs possibles :

Erreur : division par zéro

Erreur : expression invalide

Erreur : arguments invalides

Erreur : syntaxe invalide

Erreur : nombre trop grand

19. Exemples de tests

Pour tester rapidement la bibliothèque :

theoreme_pythagore(3,4)

theoreme_pythagore_inverse(3,4,5)

theoreme_distance(0,0,3,4)

theoreme_heron(3,4,5)

theoreme_aire_cercle(5)

theoreme_volume_sphere(3)

theoreme_discriminant(1,-5,6)

theoreme_second_degre(1,-5,6)

theoreme_pgcd(48,18)

theoreme_ppcm(12,18)

theoreme_nombre_premier(97)

theoreme_suite_arithmetique(2,3,10)

theoreme_suite_geometrique(2,3,5)

Résumé

La bibliothèque fonctionne selon le principe :

Prompt
   ↓
Identification du théorème
   ↓
Conversion de l'expression
   ↓
Analyse AST sécurisée
   ↓
Vérification des fonctions autorisées
   ↓
Calcul du théorème
   ↓
Résultat

Syntaxe générale :

theoreme_nom(parametres)