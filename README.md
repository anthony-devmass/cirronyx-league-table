# Cirronyx League Table

Interface responsive de classement de football réalisée en HTML5 et CSS3 pour la tâche 1 de Cirronyx.

## Ouvrir le projet

1. Ouvrir le dossier `cirronyx-league-table` dans Visual Studio Code.
2. Ouvrir `index.html` dans un navigateur ou avec l’extension Live Server.
3. Redimensionner la fenêtre pour vérifier les trois paliers responsive : desktop, tablette et mobile.

## Responsive

- **Desktop** : le tableau conserve sa présentation classique avec toutes ses colonnes.
- **Tablette (701 à 1024 px)** : les colonnes restent visibles dans la largeur disponible, les espacements et les logos sont réduits, et les noms longs peuvent revenir à la ligne.
- **Mobile (jusqu’à 700 px)** : chaque club devient une fiche compacte. Les statistiques `MP`, `W`, `D`, `L`, `GF`, `GA`, `GD`, `PTS` et `Form` restent visibles sans défilement horizontal.

La version conforme au cahier des charges utilise `assets/css/style-pdf.css`. Cette feuille est indépendante de `style.css` et regroupe les styles desktop, tablette et mobile, avec défilement horizontal du tableau sur petit écran comme demandé dans le PDF.

## Structure

```text
index.html
README.md
assets/ (css/style.css, js/app.js, images/clubs/)
```

Cette première version est une interface statique : aucun calcul JavaScript, PHP, framework, base de données ou intégration WordPress n’est utilisé.
