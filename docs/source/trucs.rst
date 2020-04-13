.. _trucs:

**************
Quelques trucs
**************


Configuration des raccourcis
============================

Les boutons
-----------

Pour assigner une fonction à un bouton, il faut **maintenir appuyé le bouton
"disp/back"**.
Il y a ensuite possibilité de configurer 8 boutons et de leur donner la
fonction de note choix.

Le menu Quick
-------------

Pour ajouter d'autres fonctions dans le menu Quick, il faut maintenir appuyer le
bouton "Q". 
Il est préférable de ne paramétrer que ce dont à besoin pour éviter de
surcharger ce menu et de s'y perdre.

Carte mémoire
=============

Formatter la carte mémoire
--------------------------

Quand on insère une nouvelle carte mémoire, il est conseillé de la formatter.
Pour ce faire, maintenir appuyé la touche "Poubelle" pendant 3 secondes,
et au bout de 3 secondes, appuyer sur la mollette.


Obturateur électronique
=======================

Obturateur mécanique
--------------------

L'obturateur mécanique fonctionne comme un rideau qui se lève pour laisser
entrer la lumière vers le capteur. En vittesse 1/125, le rideau se lève donc
d'1/125 de secondes.

Fonctionnement de l'obturateur électronique
-------------------------------------------

Il n'y a pas de rideau avec l'obturateur électronique.
Le capteur est divisé en bandes horizontales et l'appareil photo va prendre
plusieurs sous-photo (pour chaque bande) et assembler ces sous-photos en une
photo complète.
Ces sous-photos ne sont pas prises en même temps, mais successivement.
En vitesse 1/125, l'appareil va prendre la première bande en 1/125, puis la
deuxième bande en 1/125, etc.
On peut donc voir ça un petit peu comme une photo panoramique.

Avantages
---------

- Il est **silencieux**:
  L'obturateur électronique ne fait pas de "clac clac clac", ce qui peut
  être utile pour faire des photos dans des endroits où il faut être discret.


Limitations
-----------

- **Exit le flash**:
  Le flash ne s'illumine qu'un instant donc toutes les bandes ne seront pas
  illuminées de la même manière. Le flash sera allumé pour certaines bandes
  et éteint pour d'autres.
  La photo finale aurait donc différents niveaux de luminosité.
  Il peut aussi y avoir des problèmes avec un éclairage aux néons par exemple.

- **Flou de bougé**:
  Si le sujet bouge, il y aura forcément un flou de bougé puisque le sujet aura
  eu le temps de se déplacer pendant les prises successives de sous-photos.
  Le mouvement ne peut pas être figé.


Autofocus
==========

AF-S ou AF-C
------------

Le mode AF-S (S pour "single") ne fait l'autofocus qu'une seule fois.
C'est le mode **par défaut** pour des paysages ou pour des portraits de sujets qui
ne bougent pas.
Si il faut refaire la mise au point, il faut enlever son doigt du déclencheur
et réappuyer dessus une 2e fois.

Le mode AF-C (C pour "continuous") fait la mise au point en continu.
C'est le mode par défaut pour des **sujets qui bougent**.
Il faut juste garder le sujet dans le collimateur.

En conditions difficiles, le choix de l'AF-S et l'AF-C peut aussi être
important.
Par exemple quand on baisse l'ouverture pour avoir une plus grande pronfondeur
de champs.
En AF-C, le diaphragme sera déjà mis à sa valeur pendant l'AF, alors qu'en AF-S,
le diaphragme reste ouvert pendant l'AF et ne se ferme qu'au moment de la prise
de la photo. L'AF-S sera donc bien meilleur en condition de **basse luminosité**.

Détection de contraste vs détection de phase
--------------------------------------------

L'autofocus peut se faire via deux méthodes.
En détection de contraste (petits points sur les côtés), l'AF va essayer plein
de possibilités différentes et va choisir la zone aveec le meilleur contraste.
C'est une technique précise mais aussi très lente.
D'ailleurs, on va entendre l'AF faire tous ses tests (effet de pompage).
En détection de contraste, l'AF se fait immédiatement. La seule contrainte est
d'avoir assez de lumière.
Ce mode ne fonctionnera donc pas bien en basse luminosité.
C'est pour ça que le collimateur en détection de phase est limité au centre de
l'image car les bords sont souvent moins lumineux.
Par ailleurs, en mode rafale hot (rapide), la détection de contraste n'est pas
permise car c'est trop lent.
Ca veut donc dire aussi qu'il faut suffisament de lumière pour pouvoir faire des
rafales rapides.

Les modes d'autofocus
---------------------

Il y a plusieurs mode d'AF à utiliser en fonction des situations.

Single-point AF
C'est le mode **par défaut**. Il y a un collimateur unique (la taille du collimateur
est variable). A utiliser par exemple pour **un portrait ou un paysage**.
C'est un mode assez exigent pour l'AF puisqu'il doit être très précis pour
parvenir à faire le focus sur un point précis.
Le mode single-point est compatible avec l'AF-S et l'AF-C.

Mode zone
C'est une extension du point unique, mais plus facile pour l'AF de faire le
focus, et donc c'est plus rapide que le single-point.
Le mode est disponible en 3x3, 5x5 ou 7x7. 
Le 3x3 est le plus recommendé pour le mode zone. 
Ce mode est utile **en rafale en AF-C en basse lumière, ou avec des éléments
qui bougent un peu**, type animaux (ex. oiseau sur une branche)
Le mode zone est compatible avec l'AF-S et l'AF-C.

Mode wide/tracking
Ce mode ne fonctionne **qu'avec l'AF-C**.
C'est utilisé pour des sujets qui bougent et où on essaie de suivre le sujet.
Il faut d'abord mettre le sujet dans la zone du collimateur puis appuyer
à mi-course sur le déclencheur, et l'appareil photo va suivre le sujet qui est
dans la cible.
Il y a plusieurs sous-modes de tracking (apparition soudaine,
ignorer les obstacles, accélération, etc.)


Exposition
==========

Mode de mesure de la lumière: mode multi / central / central pondéré / moyenne
------------------------------------------------------------------------------
La mode de mesure de la lumière est un paramètre essentiel à choisir avant de
prendre une photo. Chez Fuji, le paramétrage se fait dans "Photométrie".

Le mode multi est le mode par défaut.
L'image est coupée en 256 zones et la moyenne de toutes les zones doit donner
un gris moyen.

Le mode central n'utilise que les 2% du centre (du collimateur?) pour mesurer la
lumière. Le reste de l'image est ignoré.
C'est très utile en **contre-jour** par exemple.
En mode mutli en contre-jour, le sujet sera noir et le fond sera blanc.
La photo est inutilisable.
En mode central, l'exposition ne se fera que sur le centre, et la luminosité
sera jolie sur le sujet quite à avoir un fond blanc.

Le mode central pondéré utilise plus le centre et moins les bords pour faire
l' exposition. C'est un peu intermédiare entre le mode multi et le mode central.
Pas le plus facile à utiliser.

Le mode moyenne est à utiliser si on fait des **rafales** pour que l'exposition ne
change pas d'une photo à l'autre.

Dans tous les modes, la recherche d'exposition vise à avoir une lumière moyenne
grise. Ca veut dire que si on prend un mur blanc en photo, il va apparaître gris.
Idem si on prend un mur noir.
Pour palier à ça, il faut utiliser la correction d'exposition.
Si on prend un sujet blanc, selon les recommendations, il faut faire une
correction de +1.
Si on prend un sujet noir, il faut faire une correction de -2/3 toujours selon
les recommendations.


Stabilisation
=============

Sans stabilisation
------------------

En désactivant la stabilisation de l'objectif et en prenant une photo à main
levée, il y a une règle sur la vitesse minimale pour éviter d'avoir un
flou de bougé.

``vitesse minimale = 1 / focale en équivalent full frame
= 1 / (1.5 * focale Fuji)``

Par exemple, avec une focale à 50mm, la vitesse minimale sera de
``1 / (1.5 * 50) = 1/75``

Sur le XT2, la vitesse minimale disponible sera de 1/125.

Avec stabilisation
------------------

La stabilisation permet de gagner 3 stops.
Donc dans l'exemple ci-dessus, on pourra descendre à une vitesse de 1/15.
Attention, la stabilisation ne fonctionne que pour des **sujets fixes**.
La stabilisation permet donc de pouvoir prendre une photo en plus basse
luminosité sans devoir monter dans les ISO.

Quand et comment utiliser la stabilisation?
-------------------------------------------

Dans la majorité des cas, il faut **désactiver la stabilisation** parce que la
vitesse sera suffisamment rapide.
De même lorsqu'on utilise un trépied, il faut absolument désactiver la
stabilisation car le moteur de stabilisation produit de léger mouvement qui dans
ce cas entraîne l'effet inverse, c'est-à-dire d'introduire du flou.

Il y a deux modes de stabilisation: le mode 1 est actif tout le temps, et le
mode 2 ne s'active qu'au moment de la photo.
Le mode 1 est utile quand on utilise une longue focale pour y voir clair dans le
viseur. 
Dans les autres cas, le mode 2 est préférable.




