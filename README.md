# 🕹️ Cub3D

## 📖 Présentation
**Cub3D** est un projet de l’école 42 qui consiste à développer un **moteur 3D minimaliste** en utilisant la technique du **raycasting**, inspirée du jeu *Wolfenstein 3D*.  
L’objectif est de plonger dans les bases de la programmation graphique, de comprendre le fonctionnement d’un moteur de rendu 3D et de gérer les interactions de l’utilisateur en temps réel.  

Ce projet a été réalisé en **binôme avec [Bibickette](https://github.com/Bibickette)**.

Ce projet permet de se familiariser avec :  
- La manipulation des fenêtres et événements via la bibliothèque **MiniLibX**.  
- Les mathématiques du **raycasting** (vecteurs, distances, angles).  
- La gestion du **mouvement du joueur** et des collisions.  
- Le parsing d’un fichier de configuration décrivant la carte, les textures et les couleurs.  

---

## 🎯 Objectifs et Contraintes
- Implémenter un rendu 3D basé sur le raycasting.  
- Lire et valider une **map** décrite dans un fichier `.cub`.  
- Afficher :  
  - Les murs avec textures.  
  - Le sol et le plafond avec les couleurs spécifiées en rgb.  
- Gérer les déplacements du joueur :  
  - Avancer, reculer, tourner à gauche et à droite.  
- Gérer les erreurs (fichier invalide, texture manquante, map incorrecte).  
- Le code doit respecter les normes de l’école 42.  

---

## 🚀 Utilisation

### 1️⃣ Compilation
Pour la version de base :  
```bash
git clone git@github.com:42paris/minilibx-linux.git
make
```
Génère l’exécutable :
```bash
cub3D  
```

Pour la version avec **bonus** : 
```bash
make bonus
```  

Génère l’exécutable :  
```bash
cub3D_bonus  
```

### 2️⃣ Lancement du programme
Exécuter une map depuis le dossier `maps/` : 
```bash
./cub3D maps/example.cub  
```

Pour la version bonus :  
```bash
./cub3D_bonus maps/example.cub  
```
### 3️⃣ Contrôles
- **Z / W** : avancer  
- **S** : reculer  
- **A / Q** : strafe gauche  
- **D** : strafe droite  
- **Flèche gauche** : tourner à gauche  
- **Flèche droite** : tourner à droite  
- **E** : interagir avec les portes (ouvrir/fermer)  
- **ECHAP** : quitter le jeu  

---

## ⭐ Bonus
Les fonctionnalités bonus incluent :  

- **Wall collisions** : empêche le joueur de traverser les murs.  
- **Minimap system** : affichage en temps réel d’une mini-carte 2D de l’environnement.  
- **Doors** : portes interactives que le joueur peut ouvrir et fermer avec la touche **E**.  
- **Animated sprites** : gestion de sprites animés pour plus de réalisme (ex : torches, ennemis).  

