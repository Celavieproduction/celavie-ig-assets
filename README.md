# celavie-ig-assets

Hébergement public des images publiées automatiquement sur l'Instagram **Cëlavie Production**.

Ce repo est public uniquement pour que l'API Instagram (Content Publishing API) puisse télécharger les images via leur URL `raw.githubusercontent.com`. Il ne contient **que des médias destinés à être publiés** — aucune donnée sensible.

## Organisation
Une image par post, rangée par mois :
```
2026-06/mon-image.jpg
2026-07/...
```

## URL à utiliser dans une fiche post
Champ `image_url:` de la fiche (vault celavie-os) :
```
https://raw.githubusercontent.com/Celavieproduction/celavie-ig-assets/main/2026-06/mon-image.jpg
```

## Contraintes image Instagram
- Format **JPEG**
- Largeur recommandée **1080 px**
- Ratio entre **4:5** (portrait) et **1.91:1** (paysage)
- Poids max ~8 Mo

Système d'autopost : voir `casquettes/marketing/campagnes/instagram/` dans le vault Cëlavie OS.
