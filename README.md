# 🎮 Jeu procédural sans nom avec un renard

> _Ce jeu  est un jeu mobile de type "Rogue Like" inspiré du jeu mobile Archero. L'emplacement des pièces est généré procéduralement_

---

## 🧩 Fonctionnalités

### ✅ Fonctionnalités actuelles

- [x] Système de déplacement
- [x] Ennemis avec IA de base
- [x] Interface utilisateur (UI)
- [x] Scène Menu
- [x] Post-Process
- [x] Animation de course et d'attaque
- [x] Génération procédural de la carte
- [x] Code extensible (ex. configuration de ennemis / salles contenues dans des scriptables objects)

### 🔮 Fonctionnalités prévues

- [ ] Amélioration du personanage au fil de la partie
- [ ] Autres type d'ennemis
- [ ] Autres monde (ex. neige, obscur etc...)
- [ ] Boss avec mécaniques avancées
- [ ] Ajout du son
- [ ] Menu Pause
- [ ] Système de défaite 
- [ ] Pouvoir relancer une partie lorsque l'on gagné / perdu


---

## 🐞 Bugs connus

- 🔹 Bug de collision, lorsque le personnage rentre en collision avec certaines entités (ex. ennemis, murs) il se met à tourner sur lui même
- 🔹 Bugs lors de la création de la map de temps en temps (le jeu ne vous téléportera pas sur la carte mais vous laissera dans le vide) 
`IndexOutOfRangeException: Index was outside the bounds of the array.
Map3DGenerator.Generate3DMap () (at Assets/Scripts/Map/Map3DGenerator.cs:81)
Map3DGenerator.Start () (at Assets/Scripts/Map/Map3DGenerator.cs:33)`
- 🔹 Problèmes particules sur Android

--- 