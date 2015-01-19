# FDFv2
FDFv2 est un logiciel qui consiste à créer graphiquement la representation schématique d’un terrain en reliant différents points par des droites. Les coordonnées du terrain sont stockées dans un fichier passé en paramètre, dont voici un exemple :

<img src="http://i.imgur.com/wZQjNSb.png" align="center"/>

- Ce logiciel à été optimisé dans le but de recevoir des terrains similaire a ceux proposés graçe au lien ci contre :
https://github.com/jgigault/42MapGenerator
- Il peut bien evidemment afficher d'autres maps dites plus "basiques" sans problèmes.

## Paramètres géré :
1. Zoom / Dézoom
2. Déplacement
3. Augmentation / Diminution de la graduation
4. Remise à 0 des paramètres
5. Initialisation de la map a la taille de l'ecran (approximatif)
6. Initialisation de la map au centre de l'ecran (approximatif)
7. Coloration en fonction de la hauteur (optimisé suivant: cf lien)
8. Affichage / Non affichage du menu
9. Quitter le programme

## Rendu obtenu :

<img src="http://i.imgur.com/JWHNfpD.jpg" width="50%" align="left"  />
<img src="http://i.imgur.com/UhGn7dK.jpg" width="50%" height="20" align="rigth" />

## Points à améliorer / ajouter :
- Vitesse (comme souvent)
- Optimisation en memoire (qui ralentirais l'execution, donc à voir)
- Changement de palette de couleur
- Améliorer l'initialisation de la map, taille et centrage
- Gérer d'autres vue
- Gérer les faces cachées (risque de ralentir enormement les performances, à voir)


> Ps : Avoir un code qui marche c'est bien, le comprendre c'est mieux ! ;)
