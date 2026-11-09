Site racine de joffrayda.github.io. Il ne sert qu'à deux choses :
- `.well-known/assetlinks.json` : prouve à Android que l'app Café Frimousse (`io.github.joffrayda.cafefrimousse`) et le site https://joffrayda.github.io/renards/ vont ensemble (sinon l'app affiche une barre d'adresse Chrome) ;
- `index.html` : renvoie vers le jeu.
`.nojekyll` est obligatoire, sinon GitHub Pages ignore le dossier `.well-known`.
