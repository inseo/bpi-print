#bpi-print
Le dépôt bpi-print regroupe les styles d'impression détaillés dans le livre [Intégration web - les bonnes pratiques](http://www.eyrolles.com/Informatique/Livre/integration-web-les-bonnes-pratiques-9782212133707) publié aux Éditions Eyrolles.

##Styles d'impression
Le fichier `print.css` comprend des styles génériques applicables à tous les projets et des styles spécifiques –&nbsp;commentés par défaut&nbsp;– qui peuvent être utilisés au cas par cas selon les besoins.

###Styles génériques
Les styles génériques sont réutilisables tel quel.
Ils servent à :

* Normaliser la couleur du texte.
* Réinitialiser les dimensions du `<body>`.
* Prévenir les changements de page disgracieux.
* Rétablir le soulignement des liens.
* Renseigner l'URL des liens (à l'exception des ancres nommées).
* Indiquer la signification des abréviations.
* Restreindre la largeur des images à la largeur de la page.

###Styles spécifiques
Les styles spécifiques sont à adapter au projet en cours. 
Ils permettent de :

* Masquer les éléments superflus.
* Réinitialiser les dimensions du conteneur principal.
* Linéariser le contenu.
* Remplacer les couleurs d'arrière-plan par une bordure.
* Afficher une description détaillée en lieu et place de son image.

##Utilisation
Suivant le nombre et l'importance des règles destinées au média `print`, les instructions peuvent être incluses dans la feuille de styles générale ou regroupée dans un fichier distinct.