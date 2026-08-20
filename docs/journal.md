---
layout: default
nav_order: 7
title: Documentation continue 
---
## Jeudi 20 août 2026

Présentation du projet

Découverte de la documentation technique

Création du repo GitHub : [https://github.com/Zacak/catapulte](https://github.com/Zacak/catapulte)

Mise en place du journal de bord sur le site

Analyse du cahier des charges : [Documentation MakerSpace](https://doc.makerspace-amiens.fr/workshops/medieval-challenge/concepts/medieval-challenge/informations/)

Recherche des différents phénomènes physiques et formules

### Loi de Hooke

La force exercée par le ressort dépend de son allongement :

$$
F = k \Delta x
$$

Avec :

- $F$ : force exercée par le ressort en newtons (N)
- $k$ : raideur du ressort en N/m
- $\Delta x$ : allongement du ressort en mètres (m)

Plus le ressort est étiré, plus la force exercée est importante.

### Énergie potentielle élastique

Lorsque le ressort est tendu, il stocke de l'énergie :

$$
E = \frac{1}{2} k (\Delta x)^2
$$

Avec :

- $E$ : énergie stockée en joules (J)
- $k$ : raideur du ressort
- $\Delta x$ : allongement du ressort

Cette énergie est libérée lors du déclenchement de la catapulte.

### Rotation du bras

La force du ressort provoque la rotation du bras autour de son axe.

Le couple mécanique peut être représenté par :

$$
\tau = F \times d
$$

Avec :

- $\tau$ : couple en N·m
- $F$ : force exercée par le ressort
- $d$ : distance entre l'axe et le point d'application de la force

### Mouvement du projectile

Lorsque la balle quitte le bras, elle possède une vitesse initiale et un angle de lancement.

Le mouvement horizontal est :

$$
x(t) = v_0 \cos(\theta)t
$$

Le mouvement vertical est :

$$
y(t) = h_0 + v_0 \sin(\theta)t - \frac{1}{2}gt^2
$$

Avec :

- $v_0$ : vitesse initiale de la balle
- $\theta$ : angle de lancement
- $t$ : temps
- $h_0$ : hauteur de départ
- $g$ : accélération de la pesanteur, environ 9,81 m/s²

La trajectoire obtenue est approximativement parabolique.

Premier croquis effectué

![Premier croquis de la catapulte](images/croquisv1.png)

Approximations des dimensions pour la catapulte

Base : 170 × 170 × 5 mm

Bras : 150 mm

Distance de l’axe à la balle : 125 mm

Hauteur de l’axe : 45 mm

Support : 55 mm

Réflexion sur le choix du système de propulsion (ressort) et du mécanisme de déclenchement
