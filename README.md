# Calculateurs BeGlorious - version BÊTA

Version de travail, non publique. Ne pas confondre avec la version en ligne actuelle
(https://gloricharles.github.io/coaching-tools/calculateurs-beglorious.html), qui reste inchangée
tant que cette bêta n'est pas finalisée.

## Fichiers
- `index.html` - le hub complet (Allures / Outils course / Erg / RM). Sert de page d'accueil si GitHub Pages est activé.
- `calculateurs-beglorious.html` - strictement identique à index.html, sous le nom de production (pour tester l'URL finale).

Les deux fichiers sont autonomes (HTML/CSS/JS en un seul fichier, aucune dépendance à installer).

## Tester
- En local : double-clic sur `index.html` (ou ouvrir dans un navigateur). Tout marche hors-ligne sauf les polices Google Fonts.
- Via un lien bêta : activer GitHub Pages (voir ci-dessous).

## Créer le dépôt (sans ligne de commande)
1. github.com → New repository. Nom au choix (ex. `coaching-tools-beta`). Coche **Private**.
2. Sur la page du dépôt vide : "uploading an existing file" → glisse-dépose `index.html`, `calculateurs-beglorious.html` et ce `README.md`. Commit.

## Activer un lien bêta (optionnel)
Settings → Pages → Source : branche `main`, dossier `/ (root)` → Save.
Le lien sera `https://<ton-compte>.github.io/<nom-du-repo>/`.

⚠️ Un dépôt privé ne rend PAS le lien privé : la page GitHub Pages est servie en public
(URL non référencée, mais techniquement accessible). Si tu veux zéro lien public, n'active pas Pages et teste en local.

## Une fois finalisée
Copier le contenu finalisé vers le dépôt de production (`coaching-tools`), aux noms
`calculateurs-beglorious.html` (et `index.html` si tu veux que la racine serve le hub), puis vérifier
les 4 onglets sur l'URL publique.

## Nouveautés de cette bêta (vs version en ligne)
- Machine "Tapis Woodway" dans l'onglet Erg (calories ACSM = méthode console Woodway, pente 0-15 %, vitesse 0-20 km/h).
- Équivalences tapis avec les autres machines (par la distance) + mode "Égaler des calories" (base Calories / Distance / Temps, comparatif pentes 0/5/10/15).
- Calories tapis dans la grille d'équivalence (vitesse/pente au choix, repliées par défaut).
- Poids optionnel discret (70 kg par défaut, comme la console).
- Footer mis à jour (perf récente + test physiologique).

Documentation de référence complète du projet : voir le doc de transmission dans le Project Claude "calculateur".
