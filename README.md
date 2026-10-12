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
5. Une mauvaise réponse (−4 PV) ou un dépassement des 6 secondes (−5 PV) → tu perds des PV.
6. Après chaque victoire, tu récupères 3 PV, et les créatures deviennent un peu plus fortes.
7. Le bouton **🗺️ Changer de zone** permet de retourner au choix des zones à tout moment.

## 🗺️ Zones

Au démarrage (et via le bouton *Changer de zone*), le joueur choisit sa zone d'entraînement :

### ➕ Tables d'addition (9 zones)
| Zone | Calculs |
|------|----------|
| Table de +1 | 1 + 1 → 1 + 9 |
| Table de +2 | 2 + 1 → 2 + 9 |
| ... | ... |
| Table de +9 | 9 + 1 → 9 + 9 |

### ⭐ Zones spéciales
| Zone | Calculs |
|------|----------|
| Vallée des Doubles | les doubles (a + a, jusqu'à 10 + 10) |
| Lac des Compléments à 10 | a + ? = 10 |
| Forêt des Soustractions | soustractions jusqu'à 20 |
| Grotte des Multiplications | tables (2–5 × 2–9) |

Plus la zone choisie est difficile (table élevée, multiplications...), plus les créatures rencontrées sont costaudes.

## 🧠 Péda

Conçu pour s'entraîner au calcul mental en s'amusant :
- additions et soustractions **sans et avec passage de dizaine**,
- premières **tables de multiplication**,
- la pression du chrono motive l'**automatisation** du calcul,
- la série de bonnes réponses consécutives augmente les dégâts (bonus de régularité).

## 🛠️ Technique

Fichier unique `index.html` : HTML + CSS + JavaScript vanilla, aucune dépendance, fonctionne hors-ligne.
