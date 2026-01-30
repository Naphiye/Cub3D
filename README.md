# 🕹️ Cub3D — Moteur 3D minimaliste en C

**Cub3D** est un moteur 3D minimaliste implémenté en **C**, basé sur la technique du **raycasting** (inspirée de *Wolfenstein 3D*).  
Le projet met l’accent sur la **programmation graphique bas niveau**, la **gestion de la mémoire**, et la **structuration d’un moteur de rendu temps réel**.

Le développement a été réalisé en binôme avec [Bibickette](https://github.com/Bibickette).

---

## Enjeux

- Implémentation complète d’un moteur de rendu 3D par **raycasting**
- Calculs géométriques (angles, distances, projection)
- Gestion du mouvement du joueur et des collisions
- Rendu temps réel avec contraintes de performance
- Séparation claire des responsabilités (parsing, rendu, inputs)

---

## Aspects techniques

- Programmation graphique en **C** avec la **MiniLibX**
- Moteur de raycasting (DDA)
- Parsing et validation robuste de fichiers `.cub`
- Gestion explicite de la mémoire (allocations, libérations)
- Gestion des événements clavier en temps réel

---

## Fonctionnalités

- Rendu 3D des murs avec textures
- Affichage du sol et du plafond (RGB)
- Déplacements du joueur (avancer, reculer, rotation, strafe)
- Gestion complète des erreurs (map invalide, textures manquantes, format incorrect)

---

## Bonus

- **Collisions murales** empêchant le passage à travers les murs
- **Mini-map 2D** rendue en temps réel à partir des données du moteur
- **Portes interactives** avec gestion d’état (ouvert / fermé)
- **Sprites animés** (ex :coeur)

---

## Qualité et robustesse

- Validation stricte des entrées utilisateur
- Gestion des cas limites (maps ouvertes, caractères invalides)
- Respect des normes de codage
- Code modulaire et maintenable

---

## Utilisation

### Compilation
```bash
make
```
Lancement
```
./cub3D maps/example.cub
```
