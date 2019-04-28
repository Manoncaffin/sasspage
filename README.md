# Site Onepage et SCSS
Cet exercice consiste à construire une interface web de type onepage, puis à convertir les styles CSS créés afin de les présenter en exploitant les avantages de SCSS.

---

## Consignes

**Préparation de l’environnement de travail**

1- Créez un dossier racine local pour stocker la totalité des fichiers de l’exercice.
2- Clonez le projet sur Github en ligne de commande dans votre dossier local

**Fichiers de travail**

1- Créez un dossier css dans le dossier racine.
2- Créez un nouveau fichier styles.css dans le dossier css.
3- Liez le fichier styles.css à la page web page.html.

**Mise en forme en CSS**

1- Choisissez deux couleurs de base ou utilisez les mêmes que le modèle : #00c1db et #008da0.
2- Reproduisez la mise en forme illustrée ci-dessous via CSS.

<iframe height="420" style="width: 100%;" scrolling="no" title="SassPage" src="//codepen.io/PedroIdmkr/fullembedgrid/axMyJY/?type=embed&animations=run" frameborder="no" allowtransparency="true" allowfullscreen="true"></iframe>

**Mise en place de SASS**

1- Créez un dossier scss dans le dossier racine de votre projet.
2- Créez un nouveau fichier styles.scss dans le dossier scss.
3- Copiez / collez le contenu du fichier style.css dans votre fichier style.scss.
4- Paramétrez votre projet afin de compiler automatiquement le fichier styles.scss sous le nom styles.css dans le dossier css.

**Conversion en SCSS**

1- Reprenez tout le code CSS pour imbriquer les éléments qui peuvent l’être.
2- Créez des variables pour chacune des couleurs de la page. Le nombre de couleur doit être limité aux deux couleurs de base associées au noir et au blanc. Pour les autres couleurs (formulaire ou pied de page), utilisez les fonctions darken() et lighten().
3- Isolez toutes les variables de couleur dans un fichier partiel enregistré dans un sous-dossier scss/partials.
4- Créez un mixin pour gérer le dégradé à partir de deux couleurs passées en paramètres.
5- Isolez votre mixin dans un nouveau fichier partiel.
