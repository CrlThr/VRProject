# Project Mini Game VR

## Description

Ce projet est une expérience **VR développée avec Unity**, composée de **quatre mini-jeux** utilisant différentes mécaniques d’interaction propres à la réalité virtuelle. Chaque mini-jeux se partageant une même scène afin de complémenter l'immersion propre à la réalité virtuelle.

L'objectif du projet est de **démontrer et expérimenter plusieurs types d'interactions VR**, telles que la manipulation d'objets et les interactions physiques.

---

## 🛠 Technologies utilisées

- **Moteur :** Unity (Version : 5.6)
- **Casque VR :** Oculus Quest
- **Plateforme cible :** PCVR

---

# Mini-jeux

## Mini-jeu 1 — *Fruit Ninja*

**Description**

Un katana est mis à dispostion du joueur, aprés sa prise en main plusieurs objet commencerons à aparaitre devant le joueur. Celui-ci sera alors capable de détruire les objets en les frappant à l'aide du katana

---

## Mini-jeu 2 — *Tir à l'arc*

**Description**

De façcon similaire au premier mini jeu, un arc sera mis à disposition du joueur. Il pourra alors simuler la prise en main de la corde afin de bander celui-ci et charger son tir afin de détruire les cibles face à lui.

---

## Mini-jeu 3 — *Dessin*

**Description**

Dans ce jeu, un canvas blanc est mis en place pour permettre au joueur de dessiner, outils etant un crayon et une gomme, possibilité de tout effacer.

---

## Mini-jeu 4 — *Labyrinthe*

**Description**

Dans ce dernier mini-jeu, le joueur sera amené à parcourir un dédale sombre avec seulement une lampe torche. Celle-ci pourra s'éteindre de manière indépendante de temps à autre forçantle joueur à la rallumr manuellement afin de ne pas se perdre. Pour atteindre la fin, en plus de la sortie, le joueur devra trouver un bouton et appuyer dessus. 

---

# Contrôles

| Action | Contrôle |
|------|------|
| Menu | B button |
| Grab objet | Grip |
| Mouvement | Stick droit / téléportation |
| Caméra | Stick gauche |
| Tirer corde | Grip -> Tirer contrôleur |
| Allumer lampe | Secouer le contrôleur |

> Les contrôles peuvent varier selon le casque VR utilisé.

---

# Structure du projet

Main - Structure VR par défaut
PaintGame - Contient les blueprint du mini-jeu de dessin
ArcheryGame - Contient les blueprint du mini-jeu de tir à l'arc
FruitNinja - Contient les blueprint du mini-jeu type fruit ninja
Labyrinth - Contient les blueprint du mini-jeu labyrinthe
Merged_Labirinth_fruitN - Mergin branche afin de créer une scène commune
