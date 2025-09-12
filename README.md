<p align="center">
    <img src="media/98d62c5a-f856-4b1f-ae9f-d92fc780aa8a_MASTER.png" alt="Roll-a-Ball Banner"/>
</p>


# Roll-a-Ball

Un projet Unity basé sur le tutoriel officiel **Roll-a-Ball**.  
L’objectif est de contrôler une sphère pour collecter des objets sur une scène en utilisant les contrôles clavier.

---

## 🎮 Fonctionnalités
- Contrôle du joueur avec les touches directionnelles ou ZQSD.
- Caméra suivant automatiquement le joueur.
- Collecte d’objets (Pickups).
- Affichage du score en temps réel.
- Condition de victoire lorsque tous les objets sont ramassés.

---

## 🛠️ Prérequis
- [Unity Hub](https://unity.com/download)
- Unity **2021.3 LTS** ou version ultérieure recommandée
- .NET SDK (inclus avec Unity)

---

## 🚀 Installation et exécution
1. Cloner le dépôt :
   ```bash
   git clone https://github.com/utilisateur/roll-a-ball.git
   ```
2. Ouvrir Unity Hub et ajouter le dossier du projet.
3. Ouvrir la scène principale :
   - `Assets/Scenes/MiniGame.unity`
4. Lancer le jeu dans l’éditeur avec le bouton **Play**.

---

## 🎯 Contrôles
- **Flèches directionnelles** ou **ZQSD** : déplacer la sphère
- **Échap** : quitter l’application (build standalone)

---

## 📂 Structure du projet
```
Roll-a-Ball/
├── Assets/
│   ├── Input/          # Configuration des entrées
│   ├── Scenes/         # Scène principale
│   ├── Scripts/        # Scripts C#
│   ├── Prefabs/        # Objets réutilisables
│   └── Materials/      # Textures et couleurs
├── ProjectSettings/    # Configuration Unity
└── README.md
```

---

## 📌 Améliorations possibles
- Ajout de niveaux multiples.
- Power-ups (bonus de vitesse, ralentissement).
- Interface utilisateur améliorée.
- Gestion des scores élevés (Highscore).

---

## 📖 Références
- Tutoriel Unity officiel : [Roll-a-Ball](https://learn.unity.com/project/roll-a-ball)
- Documentation Unity : [https://docs.unity3d.com](https://docs.unity3d.com)
