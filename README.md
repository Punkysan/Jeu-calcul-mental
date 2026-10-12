# Calculomon — Le RPG du calcul mental 🐱⚡

Un jeu web dans le style **Pokémon / Pokéclicker** où l'on bat des créatures en résolvant des **calculs mentaux**, du CP au CE1 (extensible jusqu'au CM2).

Basé sur les programmes et repères de progression officiels : mémorisation et **automatisation des faits numériques**, restitution quasi instantanée pour soulager la mémoire de travail.

## 🎮 Comment jouer

1. Ouvre `index.html` dans un navigateur (TBI, tablette ou ordinateur) — aucune installation, fonctionne hors-ligne.
2. Choisis une zone sur la **carte du monde** (catégories débloquées progressivement).
3. Résous le calcul affiché : tape au clavier ou utilise le **pavé numérique tactile**.
4. **Vitesse = puissance** :
   - réponse < 3 s → **coup critique** (×2,5 dégâts)
   - réponse lente mais correcte → dégâts réduits, mais **jamais de pénalité** sur les PV
5. En cas d'erreur : ton Calculomon perd quelques PV (2) et le jeu affiche **la procédure efficace attendue** (ex. « pour 7 + 5 : va d'abord à la dizaine... »), pas seulement le résultat. Le fait échoué **revient plus souvent** (répétition espacée) jusqu'à maîtrise.
6. Bouton **📈 Progrès** : fluence (égalités/minute) par catégorie, taux de réussite, progrès visibles par l'élève.

## 📚 Catégories (progression CP → CE1)

### 📘 CP (dès le début)
| Zone | Contenu |
|------|---------|
| 💧 Compléments à 10 | `3 + ? = 10` |
| 🏔️ Doubles | doubles ≤ 10 et dizaines entières (jusqu'à 50) |
| 🌗 Moitiés | moitiés des nombres pairs ≤ 20 (déblocage : 3 victoires) |
| 🧩 Décompositions ≤ 10 | `4 + ? = 9` (déblocage : 5 victoires) |
| ➕ Tables d'addition | tables des nombres < 10, avec passage de dizaine (déblocage : 7 victoires) |

### 📗 CE1 (déblocage progressif)
| Zone | Contenu |
|------|---------|
| 🔁 Additions 2 sens | résultat inconnu **et** égalité à trou (cible : ~12 ég./min) |
| ✌️ Table de ×2 | dans les deux sens |
| 🖐️ Table de ×5 | dans les deux sens |
| 🔟 Table de ×10 | dans les deux sens |
| 📚 Dizaines entières | ajouter/retrancher des dizaines |

Chaque catégorie propose les calculs **dans les deux sens** : résultat inconnu (`7 × 8 = ?`) et égalité à trou (`7 × ? = 42`, `4 + ? = 12`).

## 🧠 Principes pédagogiques

- **Rétroaction immédiate** : en cas d'erreur, affichage de la **procédure** efficace (aller à la dizaine, décomposition...), pas seulement le résultat.
- **Répétition espacée** : un fait numérique échoué revient prioritairement jusqu'à maîtrise.
- **Fluence mesurée** : égalités correctes par minute, suivie par catégorie, visible par l'élève (écran Progrès).
- **Climat serein** : pas de classement, pas d'échec bloquant — défaite = réessai, pénalités douces.
- **Deux sens systématiques** : résultat inconnu et égalité à trou.

## 🔒 Données

Aucune donnée personnelle collectée. La progression est stockée **localement** dans le navigateur (`localStorage`).

## 🗺️ Feuille de route

- [x] Structure CP + CE1 (10 catégories)
- [x] Fluence + écran de progrès + répétition espacée
- [ ] CE2 : fluence renforcée (15 ég./min), tables de multiplication complètes, × 10 / 100 / 1000
- [ ] CM1 : procédures ±9/±19/±29/±39, ×4/×8 (double du double), distributivité, numération de position
- [ ] CM2 : multiplication/division par 10/100/1000 sur décimaux, division mentale
- [ ] Mode oral (questions lues à voix haute)

## 🛠️ Technique

Fichier unique `index.html` : HTML + CSS + JavaScript vanilla, aucune dépendance, aucune API, responsive (TBI/tablette/ordinateur).
