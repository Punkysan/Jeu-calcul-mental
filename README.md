# Calculomon — Le RPG du calcul mental 🐱⚡

Un jeu dans le style **Pokémon / Pokéclicker** où l'on bat des créatures en résolvant des **calculs mentaux de niveau CP**.

Plus tu réponds vite, plus ton attaque est puissante — et en dessous de 1,5 seconde, tu as 35 % de chance de porter un **coup critique** (dégâts ×2,5) 💥

## 🎮 Comment jouer

1. Ouvre simplement `index.html` dans un navigateur — aucune installation ni dépendance.
2. Une créature apparaît avec un calcul (ex. `7 + 8 = ?`).
3. Tape ta réponse et appuie sur **Entrée** (ou clique sur *Attaquer !*).
4. **Vitesse = puissance** :
   - Réponse instantanée → dégâts max
   - Réponse lente → dégâts faibles
   - **< 1,5 s** → chance de coup critique 💥
5. Une mauvaise réponse ou un dépassement des 6 secondes → tu perds des PV.
6. Tous les 3 monstres vaincus, tu montes de niveau et récupères des PV.

## 🗺️ Zones

| Zone | Calculs |
|------|----------|
| Prairie des Additions | additions simples (1–9) |
| Forêt des Soustractions | additions jusqu'à 15, soustractions |
| Grotte des Multiplications | soustractions jusqu'à 20, petites tables |
| Sommet des Grands Calculs | tables de multiplication (2–5 × 2–9) |

## 🧠 Péda

Conçu pour s'entraîner au calcul mental en s'amusant :
- additions et soustractions **sans et avec passage de dizaine**,
- premières **tables de multiplication**,
- la pression du chrono motive l'**automatisation** du calcul,
- la série de bonnes réponses consécutives augmente les dégâts (bonus de régularité).

## 🛠️ Technique

Fichier unique `index.html` : HTML + CSS + JavaScript vanilla, aucune dépendance, fonctionne hors-ligne.
