<h1 align="center">🤖 Tic-Tac-Toe with AI</h1>

<p align="center"><em>Un morpion contre l'ordinateur, à quatre niveaux, du tirage au sort jusqu'à l'algorithme Minimax.</em></p>

<p align="center">
  <img src="https://img.shields.io/badge/Python-3-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python 3" />
  <img src="https://img.shields.io/badge/d%C3%A9pendances-aucune-success?style=for-the-badge" alt="Aucune dépendance" />
  <img src="https://img.shields.io/badge/projet%20d%27apprentissage-ff69b4?style=for-the-badge" alt="Projet d'apprentissage" />
</p>

---

## ✨ Pourquoi tu vas l'adorer

- **Quatre niveaux** : de l'IA qui joue au hasard jusqu'à celle qui calcule ses coups.
- **Mode spectateur** : fais s'affronter deux IA, par exemple avec `start easy hard`.
- **Minimax** : le niveau `hard` s'appuie sur l'algorithme classique des jeux à deux joueurs.

## 🎮 Commandes

| Commande | Effet |
|---|---|
| `start <joueur1> <joueur2>` | Lance une partie, par exemple `start user hard` |
| `exit` | Quitte le programme |

Chaque joueur peut être `user` (toi), `easy`, `medium` ou `hard`.

## 🧠 Les niveaux

| Niveau | Comportement |
|---|---|
| `user` | Toi, au clavier, en saisissant `colonne ligne` |
| `easy` | Joue une case au hasard |
| `medium` | Joue un coup gagnant ou bloque celui de l'adversaire, sinon au hasard |
| `hard` | Utilise Minimax, et joue le centre en premier |

## 🚀 Lancer

```bash
python3 Code_Python_Tic_Tac_Toe_with_AI
```

## 🕹️ Exemple

```text
Input command:start user easy
---------
|       |
|       |
|       |
---------
Enter the coordinates:2 2
Making move level "easy"
```

## 🧠 Sous le capot

- `check_win()` interprète le plateau : victoire, match nul ou partie en cours.
- `empty_coordinates_list()` liste les cases libres, que les IA utilisent pour choisir leur coup.
- `minimax()` explore récursivement les coups possibles et remonte le meilleur score.

## 🔭 Pistes d'évolution

- Faire évoluer le Minimax : alterner les symboles à chaque coup simulé et distinguer victoire et défaite, pour un niveau réellement imbattable.
- Ajouter l'élagage alpha-bêta pour accélérer la recherche.

---

<p align="center"><sub>Fait avec ❤️ et Python par DSKarim</sub></p>
