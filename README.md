# Stats indiv Nissa Rugby – Espoirs

Page staff des statistiques individuelles : rapports de match, saison, comparaison de joueurs (protégée par un code), export PDF.

## Contenu

- `index.html` : la page complète (code, polices, logo Nissa et données de départ inclus).
- `donnees.json` : les matchs, les logos adverses, le mot de passe administrateur et le code de la fiche comparaison (enregistrés sous forme chiffrée). La page le lit à chaque ouverture.

## Mise en ligne

1. Crée un dépôt et ajoute `index.html`, `donnees.json` et ce `README.md`.
2. Dans le dépôt : **Settings → Pages → Deploy from a branch → main / (root) → Save**.
3. La page est disponible à l'adresse `https://<compte>.github.io/<depot>/`.

## Première configuration (une seule fois)

1. Ouvre `https://<compte>.github.io/<depot>/#admin` et choisis un mot de passe administrateur (6 caractères minimum).
2. Va dans « Comparer deux joueurs » et définis le code d'accès de la fiche en bas de la page.
3. Clique sur **Télécharger donnees.json**, puis remplace `donnees.json` dans le dépôt (Add file → Upload files → Commit changes).

## Ajouter un match

1. Ouvre la page en mode administrateur (`…/#admin` si tu n'es plus connecté).
2. **Importer un match** et dépose le fichier XML ou CSV.
3. **Télécharger donnees.json** puis remplace-le dans le dépôt.

## Qui voit quoi

- Visiteurs : rapports, vue saison, et fiche comparaison seulement avec le code. Pas d'import ni d'export PDF.
- Administrateur : tout, y compris l'import, l'export PDF et le changement de code.
- `…/#lecteur` déconnecte le mode administrateur sur l'appareil.

## Bon à savoir

- La page est publique : toute personne qui a le lien peut la consulter. Le code et le mot de passe empêchent l'accès par la page, mais ne chiffrent pas les données de `donnees.json`.
- L'export PDF charge deux bibliothèques depuis cdnjs.cloudflare.com : il faut une connexion internet.
