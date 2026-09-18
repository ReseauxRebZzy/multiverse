# MULTIVERSE

Portail web statique en HTML, CSS et JavaScript, prévu pour GitHub Pages.

## Contenu
- Écran d'accueil plein écran personnalisable depuis l'admin.
- Bascule avec F8 (et bouton d'entrée).
- Grille de jeux configurables, ajout/suppression et lancement en iframe.
- Applications du collège personnalisables.
- Sauvegarde locale via `localStorage`.

## Tester sur son PC
1. Télécharge et décompresse le projet.
2. Ouvre `index.html` dans un navigateur récent.
3. Appuie sur **F8** pour basculer entre l'accueil et le portail.
4. Clique sur ⚙ pour ouvrir l'administration.

Pour un test plus fidèle, ouvre le dossier dans VS Code puis utilise l'extension **Live Server**.

## Publier sur GitHub Pages
1. Crée un dépôt GitHub, par exemple `multiverse`.
2. Envoie `index.html`, `style.css`, `app.js` et `README.md` à la racine du dépôt.
3. Dans GitHub : **Settings → Pages**.
4. Dans **Build and deployment**, choisis **Deploy from a branch**.
5. Sélectionne la branche `main` et le dossier `/ (root)`, puis **Save**.
6. Attends la publication. L'adresse affichée dans Settings → Pages sera ton lien.

## Personnalisation
- Ouvre l'admin avec ⚙.
- Onglet **Apparence** : colle une URL d'image ou choisis un fichier (conseillé : moins de 2,5 Mo), puis enregistre.
- Onglet **Jeux** : ajoute des cartes avec nom, URL, catégorie, description et image facultative.
- Onglet **Collège** : ajoute les liens utiles de ton établissement.

## Limites à connaître
- La sauvegarde est propre au navigateur et à l'appareil. Elle ne modifie pas les fichiers du dépôt et n'est pas partagée avec les visiteurs.
- L'admin est accessible côté client et n'est pas protégée par un vrai compte. Ne l'utilise pas pour des données privées.
- Certains sites interdisent l'affichage dans une iframe. Le bouton **Ouvrir dans un onglet** permet d'essayer le jeu séparément.
- Les raccourcis de navigateur ou du système peuvent parfois intercepter F8.
- Les URL d'exemple de Pronote/ENT sont à remplacer par celles de ton établissement.
