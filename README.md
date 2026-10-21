# Panneau admin Boomers Crooners — remplacement

Cette archive remplace uniquement le panneau d'administration `admin.html`. Elle ne remplace pas `index.html`, `styles.css` ni `site-data.json`.

## Installation

1. Décompresse `boomers-crooners-admin-rebuild.zip`.
2. Ouvre le dépôt GitHub `pika18385-maker/Bommers-crooners`.
3. Ouvre `admin.html`, puis choisis **Edit** (ou téléverse le nouveau fichier pour remplacer l'ancien).
4. Remplace entièrement le contenu de `admin.html` par celui de l'archive, puis commit les changements sur `main`.
5. Attends que GitHub Pages publie la mise à jour, puis ouvre : `https://pika18385-maker.github.io/Bommers-crooners/admin.html`.
6. Si l'ancienne version apparaît encore, actualise la page ou ouvre-la dans un onglet privé.

## Jeton GitHub

Crée un jeton à granularité fine limité au dépôt `pika18385-maker/Bommers-crooners` avec :

- **Contents** : Read and write
- **Pull requests** : Read and write

Le jeton est saisi dans le panneau et conservé uniquement en mémoire dans cet onglet. Il n'est pas enregistré dans les fichiers. Ne le partage pas et ne l'ajoute jamais au dépôt. Révoque-le dans les paramètres GitHub si tu penses qu'il a été exposé.

## Ce qui change

- Affiche l'étape précise de l'opération qui échoue et le détail renvoyé par GitHub.
- Si la branche est créée mais que la Pull Request échoue, propose un lien vers la branche et un lien pour comparer `main` avec cette branche afin de créer la PR manuellement.
- Vérifie que `site-data.json` n'a pas changé pendant que le panneau était ouvert pour éviter d'écraser une mise à jour concurrente.
- Les images JPG, PNG et WebP jusqu'à 3 Mo peuvent être téléversées. Le téléversement peut rester dans la branche si une étape ultérieure échoue ; vérifie la branche avant de recommencer.
- Rien n'est fusionné automatiquement dans `main`.
