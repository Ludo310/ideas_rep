## Projet 1 — **Game Map Converter IDE**

### Concept
Développer un **IDE complet** capable de convertir des cartes d’un jeu vers un autre, même si les formats, les moteurs ou les assets diffèrent.

### Objectif principal
Créer un outil permettant de **reproduire automatiquement ou semi-automatiquement** une carte existante dans un autre jeu, en remplaçant les objets d’origine par leurs équivalents ou par des assets personnalisés.

### Fonctionnalités envisagées
- Importation de cartes depuis différents jeux (formats propriétaires ou ouverts).
- Analyse et extraction des données de la map :
  - Topographie  
  - Objets, bâtiments, végétation  
  - Textures et matériaux
- Système de correspondance (« mapping ») entre les assets du jeu source et ceux du jeu cible.
- Interface visuelle pour vérifier, corriger et ajuster les éléments convertis.
- Exportation vers le format natif du jeu cible.

### Exemple d’application
Recréer la carte **Altis** d’Arma 3 dans **Arma Reforger**, en convertissant automatiquement les structures, terrains et objets vers leurs équivalents dans Reforger.

### Défis identifiés
- Gestion de formats propriétaires et de leurs limitations.
- Différences techniques entre moteurs de jeu (géométrie, shaders, unités, collisions).
- Nécessité d’un système flexible pour associer ou remplacer les assets manquants.
- Garantir une conversion fidèle tout en respectant les contraintes du jeu cible.

---
