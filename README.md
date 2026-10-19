# Le Royaume des Lanternes

Une aventure en pixel art pour Elissa : dialogues, choix, carnet d'indices et révélation finale.
Jeu mobile (390×844) jouable aussi au clavier (flèches ou ZQSD, E ou Entrée).

## Fichiers

- `index.html` : page du jeu
- `style.css` : styles
- `game.js` : logique du jeu (images pixel art intégrées en base64)
- `.nojekyll` : demande à GitHub Pages de servir les fichiers tels quels

## Publier sur GitHub Pages

1. Crée un dépôt sur GitHub et envoie-y tous ces fichiers à la racine.
2. Dans le dépôt : **Settings → Pages → Build and deployment**.
3. Source : **Deploy from a branch**, branche `main`, dossier `/ (root)`, puis **Save**.
4. Après une minute, le jeu est en ligne sur `https://<ton-pseudo>.github.io/<nom-du-depot>/`.

## Tester en local

```
python3 -m http.server 8000
```

puis ouvre http://localhost:8000
