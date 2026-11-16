# AGENTS.md — charte de code de `Severance-fan-page`

Ce fichier est lu par l'IA (et par moi) avant toute modification. Il décrit la façon dont ce dépôt est écrit.

## Statut
Projet de cours **figé** : on le garde lisible, on ne le fait pas évoluer.

## Structure
- `index.html` : la page principale.
- `CSS/` : les feuilles de style.
- `IMG/` : les images.
- `Style-test.html`, `htmlmnd.html`, `text.html` : essais d'apprentissage, à ne pas supprimer sans accord.
Un fichier, un rôle.

## Écriture du code
- Nouveau code : noms de variables, de fonctions, de classes et de composants en anglais.
- Commentaires en français, qui expliquent le *pourquoi* plutôt que le *quoi*.
- Ne pas réécrire le projet : on corrige ou on étend, on ne remplace pas ce qui existe.

## Git
- Une idée = une branche = une pull request. Jamais de commit direct sur `main`.
- Commits courts, une notion par commit, préfixés d'un gitmoji.
- Tout commit écrit avec l'IA porte la mention `Co-Authored-By`.

## Qualité
- Ouvrir `index.html` dans un navigateur : toutes les images et tous les liens doivent s'afficher.
- Ne pas ajouter de dépendance ni d'outil de construction.

## Dépendances
Aucune : le projet n'utilise ni gestionnaire de paquets ni bibliothèque installée.

## Secrets
- Aucun fichier `.env` versionné. Si une clé devient nécessaire : un `.env.example` sans valeur.
