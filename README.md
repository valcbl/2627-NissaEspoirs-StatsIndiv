# Stats indiv Nissa Rugby – Espoirs

Page staff des statistiques individuelles (rapports de match, saison, comparaison de joueurs, export PDF).

## Contenu

- `index.html` : la page complète (code, polices, logo Nissa et données de départ inclus).
- `donnees.json` : les matchs et les logos adverses. La page le lit au chargement quand elle est servie par GitHub Pages.

## Mise en ligne

1. Crée un dépôt et ajoute `index.html`, `donnees.json` et ce `README.md`.
2. Dans le dépôt : **Settings → Pages → Branch : main / (root) → Save**.
3. La page est disponible à l'adresse indiquée par GitHub (`https://<compte>.github.io/<depot>/`).

## Ajouter un match

1. Sur la page, clique sur **Importer un match** et dépose l'export XML ou CSV.
2. Le match est enregistré dans ton navigateur uniquement.
3. Clique sur **Télécharger donnees.json**, puis remplace `donnees.json` dans le dépôt (Add file → Upload files).
4. Après quelques minutes, tout le staff voit le nouveau match.

Les logos ajoutés avec le bouton « + Logo » suivent le même chemin.

## Bon à savoir

- Ouvrir `index.html` directement depuis l'ordinateur fonctionne aussi, avec les données intégrées au fichier.
- L'export PDF charge deux bibliothèques depuis cdnjs.cloudflare.com : il faut une connexion internet.
- Sur un dépôt public, n'importe qui peut lire les stats des joueurs.
