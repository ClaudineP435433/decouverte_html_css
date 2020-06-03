# Jour 1

### <a href="https://github.com/Joz84/ten-hours-of-html-css" target="_blank">Retour au menu principal</a>

## Le lien vers la <a href="https://joz84.github.io/day-a.github.io/" target="_blanck">démo</a>

## Les autres liens utiles
Les diapositives du 1er cours sont disponibles à l'adresse suivante :
<a href="https://docs.google.com/presentation/d/e/2PACX-1vTG02S_mq5pnkXvMSj36VNTqjMDypUAf-ql2YGz7HisuWGakCtsWRAQy0ajBHMnjC1S6y6WOJfqfuoa/pub?start=false&loop=false&delayms=60000" target="_blanck">
Cours 1</a>

La structure du code peut être retrouvée dans le fichier <a href="https://github.com/Joz84/day-a.github.io/blob/master/index.html" target="_blanck">index.html<a>.
  
Et l'ensemble des propriétés dans le fichier <a href="https://github.com/Joz84/day-a.github.io/blob/master/style.css" target="_blanck">style.css<a>

## Les outils
<img src="images-readme/tools-logos.png" alt="tools">

### Chrome
<img src="images-readme/chrome-logo.png" alt="chrome-logo" width="100px">
Chrome est un navigateur. C'est un logiciel qui permet de visualiser une page web. 

Chaque logiciel attend un certain type de fichier avec une extension bien particulière. Par exemple :

* Le tableur Excel attend des fichiers du type "tableau.xls".
* Le lecteur vidéo VLC attend des fichiers du type "video.mp4".
* Le navigateur Chrome attend des fichiers du type "index.html" et "style.css".

<kbd>
  <img src="images-readme/extensions.png" alt="extensions">
</kbd>

### Sublime Text
<img src="images-readme/st-logo.png" alt="st-logo" width="100px">
Sublime Text est un éditeur de text qui permet d'écrire des fichiers textes et de les sauvegarder au format choisi. Dans notre cas nous l'utiliserons pour écrire les fichiers "index.html" et "style.css".

C'est le seul logiciel qu'il est nécessaire d'installer pour suivre ce cours. Voici le lien :
<a href="https://www.sublimetext.com/3" target="_blanck">Télécharger Sublime Text</a>

### GitHub
<img src="images-readme/github-logo.png" alt="github-logo" width="100px">
GitHub est une plateforme web qui permet stocker et de partager son travail en ligne et héberger des sites statiques. Dans ce cours nous utiliserons cette plateforme à la fois pour partager les supports de cours et héberger le site web que nous allos produire. Pour pouvoir suivre ce cours il est donc nécessaire de se créer un compte. Voici le lien : 
<a href="https://github.com/" target="_blanck">S'incrire sur GitHub</a>

## Présentation rapide des langages
### Le langage HTML
<img src="images-readme/html.png" alt="html" width="100px">
Le langage HTML (Hypertext Markup Language) a été créé par Tim Berners-Lee en 1989. 

C'est un Langage balisé qui permet d'écrire le contenu et structure d'un page web.

Exemple de rendu HTML sans CSS :
<kbd>
  <img src="images-readme/html-screenshot.png" alt="html-screenshot">
</kbd>


### Le langage CSS
<img src="images-readme/css.png" alt="css" width="100px">
Le langage CSS (Cascading Style Sheets) a aussi été créé par Tim Berners-Lee en 1990.

C'est un langage qui permet de définir la présentation et mise en page d'une page web.

Exemple de rendu HTML avec CSS :
<kbd>
  <img src="images-readme/css-screenshot.png" alt="css-screenshot">
</kbd>

## Commencer une page web

### Créer le dossier "code" contenant le projet
* Créer un dossier "code".
* Ouvrir le logiciel Sublime Text et faire glisser le dossier "code" à l'interieur.
<img src="images-readme/init-a.png" alt="init-a">

### Créer le fichier HTML
* Créer un nouveau fichier en tapant clique droit sur le dossier "code" apparent sur la partie gauche dans Sublime Text puis cliquer sur "new file".
<img src="images-readme/init-b.png" alt="init-b">

* Sauvegarder le fichier en cliquant sur "File" puis "Save". 
<img src="images-readme/init-c.png" alt="init-c">

* Taper le nom du fichier "index.html" (attention, petite liste des erreurs classiques : "index.html" est sans "I" majuscule, sans "e" à la fin et l'extenstion est bien "html" et pas "htlm"). Assurer vous d'être bien dans le dossier "code" avant de sauvegarder.  
<img src="images-readme/init-d.png" alt="init-d">

### Visualiser le résultat dans le navigateur
* Ne pas oublier de sauvegarder tous les fichiers ouverts dans Sublime Text.
* Ouvrir le dossier "code" en cliquant dessus.
* Taper clique droit sur le fichier "index.html", puis "Ouvrir avec" et choisir le navigateur Chrome. 
<img src="images-readme/init-e.png" alt="init-e">

* Automatiquement le navigateur s'ouvre avec et présente la page web
<img src="images-readme/init-f.png" alt="init-f">

## Le fichier HTML
<img src="images-readme/html.png" alt="html" width="100px">

### Le squelette
Le squelette de la page HTML comprend deux parties. 
  * Une partie "HEAD" pour les informations nécéssaires mais non visibles (comme par exemple autoriser les carractères avec accent).
  * Une partie "BODY" qui contient tout le contenu visible de page.
Pour générer automatiquement le squelette taper ```html``` dans le fichier index.html puis la touche "tabulations".

```html
<!DOCTYPE html>
<html>
<head>
  <title></title>
</head>
<body>

</body>
</html>
```

Pour pouvoir utiliser des carractères avec accent il faut rajouter la la ligne ```<meta charset="UTF-8">``` dans la partie "HEAD" :

```html
<head>
  <meta charset="UTF-8">
  <title></title>
</head>
...
```

Pour personnaliser le nom présent dans l'onglet du navigateur on doit spécifier un "title"

```html
<head>
  <meta charset="UTF-8">
  <title>Jour 1</title>
</head>
```

### Le titre principal

Pour écrire un titre dans la page il faut utiliser la balise "h1" (header 1).

```html
<body>
  <h1>Les Muffins de Grand Mère</h1>
</body>
```
### Les sous-titres
De la même manière, si l'on souhaite ajouter un sous-titre on utilise la balise "h2" (header 2).
Ils existent 6 niveaux de sous-titres.

```html
<body>
  <h1>Les Muffins de Grand Mère</h1>
  <h2>Fondants et croustillants</h2>
</body>
```
### Les paragraphes
On peut également ajouter un paragraphe grâce à la balise "p".

```html
<h3>Présentation</h3>
<p>Les muffins sont de petits gâteaux individuels s'apparentant aux madeleines. Apparus au pays de Galles aux alentours du XIe siècle, ils sont très répandus dans les pays anglo-saxons, principalement aux États-Unis. Le principe caractéristique de fabrication des muffins consiste à préparer le mélange des ingrédients liquides et celui des ingrédients secs séparément, puis à mélanger rapidement et grossièrement les deux préparations. Contrairement aux cupcakes, les muffins n’ont jamais de glaçage.
  Les muffins sont traditionnellement sucrés. On peut les retrouver au chocolat (avec des pépites de chocolat) ou nature, mais il existe de nombreuses autres variétés : fraise, banane, framboise, orange, vanille, myrtille ou bleuets, etc.
  Il existe également des muffins salés, les English muffins ou muffins anglais, ressemblant à des sortes de petites crêpes très épaisses, faits à partir de pâte levée. Ces muffins salés sont quelquefois faits avec de la farine complète. Ils sont notamment employés comme base de la préparation des "œufs Bénédicte".
</p>
```

### Les listes non-ordonnées (Unordered List)

La balise pour créer une liste non ordonnée est la balise "ul". Une liste est composée de plusieurs items, il faut donc créer un balise "li" (List Item) par item.

```html
<h4>Ingredients</h4>

<ul>
  <li>280 g de farine</li>
  <li>2 oeufs</li>
  <li>100 g de sucre</li>
  <li>150 ml de lait</li>
  <li>80 g de beurre (ou 8 cuillères à soupe d'huile)</li>
  <li>1 sachet de levure chimique</li>
  <li>1 sachet de sucre vanillé</li>
  <li>1 pincée de sel</li>
  <li>Cannelle</li>
  <li>Extrait de vanille</li>
</ul>
```
### Les listes ordonnées (Ordered List)

Ils existent aussi des listes ordonnées. La balise associée est la balise "ol".

```html
<h4>Préparation</h4>

<ol>
  <li>Etape 1 : Dans un premier saladier : mélanger la farine, le sucre, le sel, le sucre vanillé et la levure.</li>
  <li>Etape 2 : Dans un deuxième saladier : mélanger le lait, l'huile(ou beurre fondu) et les oeufs.</li>
  <li>Etape 3 : Verser le contenu du second saladier dans le premier et remuer jusqu'à obtenir une pâte plutôt lisse. Laissez tout de même quelques petits grumeaux.</li>
  <li>Etape 4 : Mettre au four 15 min à 180°C (thermostat 6)</li>
</ol>
```
### La structure d'une balise 

Une balise peut être constituée de 4 parties :
* Le tag (ex: h1)
* Les attributs (ex: width)
* La valeur associée (ex: 200px)
* Le text apparent

```html
<tag attribut="valeur">text apparent à l'écran</tag>
```

### Les liens de page en page

La balise pour lier deux pages est la balise "a".

```html
<a href="https://www.marmiton.org/recettes/recette_muffins-tres-simples_166385.aspx" target="blank">En savoir plus</a>
```
### Les images

* Créer un dossier nommé "images".

* Télécharger une image d'un site de photo libre de droits, de qualité et gratuite.
Exemples: 
  * https://flickr.com
  * https://www.pexels.com

<img src="images-readme/pexels.png" alt="pexels">

* Ranger la photo dans le dossier "images".

* Renommer l'image avec un nom simple, sans accent et sans espace (ex: "muffin.jpg").

La balise pour insérer une image est la balise "img", elle contient au moins un attribut, l'attribut "src" ( pour "source"). La valeur de cet attribut doit être le chemin relatif de l'image. Dans notre exemple cela est "images/muffin.jpg". 

```html
<img src="images/muffin.jpg" alt="muffin">
```
On peut egalement ajouter l'attribut "alt" ( pour "alternative"). la valeur de cet attribut est un text décrivant au mieux l'image. Dans notre exemple "muffin". l'attribut "alt" a trois applications :
* Le text s'affiche sur la page si le navigateur ne trouve pas l'image.
* Les applications pour aveugles qui lisent la page HTML notifiront qu'il y a une image et ce quelle représente.
* Mettre une description pertinante améliore le référencement.

### Mise en page du texte

Pour mettre une partie du texte en gras, on peut utiliser deux balises : 
* La balise ```<b>```
* La balise ```<strong>``` qui, en plus de mettre le texte en gras, permet de faire en sorte que se texte soit pris en compte pour améliorer le référencement.

Pour mettre le texte en italique on peut utiliser la balise ```<i>```.

Voic un exemple de paragraphe avec les différentes balises de mise en page :

```html
<p><strong>Les muffins</strong> sont de petits gâteaux individuels s'apparentant aux <b>madeleines</b>. Apparus au pays de Galles aux alentours du XIe siècle, ils sont très répandus dans les pays anglo-saxons, principalement aux États-Unis. Le principe caractéristique de fabrication des muffins consiste à préparer le mélange des ingrédients liquides et celui des ingrédients secs séparément, puis à mélanger rapidement et grossièrement les deux préparations. Contrairement aux cupcakes, les muffins n’ont jamais de glaçage.
<br>
Les muffins sont traditionnellement sucrés. On peut les retrouver au chocolat (avec des pépites de chocolat) ou nature, mais il existe de nombreuses autres variétés : fraise, banane, framboise, orange, vanille, myrtille ou bleuets, etc.
<br>
Il existe également des muffins salés, les English muffins ou muffins anglais, ressemblant à des sortes de petites crêpes très épaisses, faits à partir de pâte levée. Ces muffins salés sont quelquefois faits avec de la farine complète. Ils sont notamment employés comme base de la préparation des 
<i>"œufs Bénédicte"</i>.
</p>
```

```html
<br>
<a href="https://www.marmiton.org/recettes/recette_muffins-tres-simples_166385.aspx" target="blank">
```

## Rendu final du fichier HTML

<kbd>
  <img src="images-readme/html-screenshot.png" alt="html-screenshot">
</kbd>

## Créer et lier le fichier CSS

### Créer le fichier CSS
* Créer un nouveau fichier en tapant clique droit sur le dossier "code" apparent sur la partie gauche dans Sublime Text puis cliquer sur "new file".
<img src="images-readme/init-b.png" alt="init-b">

* Sauvegarder le fichier en cliquant sur "File" puis "Save". 
<img src="images-readme/init-c.png" alt="init-c">

* Taper le nom du fichier "style.css" (attention, petite liste des erreurs classiques : "style.css" est sans "S" majuscule et l'extenstion est bien "css" et pas "ccs"). Assurer vous d'être bien dans le dossier "code" avant de sauvegarder.  
<img src="images-readme/init-g.png" alt="init-g">

### Faire le lien entre le fichier HTML et le le fichier CSS

* Se postionner juste avant la fermeture de la balise ```<head>``` dans le fichier "index.html".
* taper ```link``` puis la touche "tabulations". On obtient la balise ```<link>``` qui permet de lier un fichier de style au fichier HTML.
* La valeur de l'attribut "href" est le nom du fichier CSS, soit dans notre exemple "style.css".

```html
<head>
  [...]
  <link rel="stylesheet" href="style.css">
</head>
```

## Le fichier CSS
<img src="images-readme/css.png" alt="css" width="100px">

### Appliquer du style au titre principal h1
Dans le fichier "style.css" taper le nom du sélecteur (par exemple: ```h1``` suivi des accolades ```{}```. L'ensemble des propriétés qui s'appliqueront à ce sélecteur seront listées à l'interieur de ces accolades.

```css
h1 {
  color: green;
  font-size: 32px;
  background: pink;
  font-family: arial;
}
```

### Appliquer du style à plusieurs balises en une seule fois
Les balises concernées sont séparées par une virgules.

```css
h2, h3, h4 {
  font-size: 28px;
  background: pink;
  font-family: arial;
}

p, ul, ol {
  font-size: 20px;
}
```

### Aplliquer du style à toute la page
Pour cela on peut utiliser la balise ```<body>```

```css
body {
  background: pink;
  font-family: arial;
}

h1 {
  color: green;
  font-size: 32px;
}

h2, h3, h4 {
  font-size: 28px;
}
```

### Positionner le texte dans la page
Pour cela on peut utiliser la propriété ```text-align```.

```css
body {
  background: pink;
  font-family: arial;
  text-align: center;
}

h4, ul, ol {
  text-align: left;
}
```

### Aplliquer du style à une image

```css
img {
  width: 300px;
  height: 300px;
  object-fit: cover;
}
```

### Aplliquer du style à un lien
Le suffixe ```:hover``` permet d'appliquer du style au lien lorsque la souris survole le lien. 

```css
a:hover {
  color: brown;
}

a, a:hover {
  text-decoration: none;
}
```

## Utiliser une police google
Google fonts (https://fonts.google.com/)

* Aller sur le site google fonts.
* Sélectionner une police en cliquant sur le petit "+" en face du nom de la police.
<kbd>
  <img src="images-readme/google-fonts1.png" alt="google-fonts1">
</kbd>
  
* Copier le code html de la forme ```<link href="https://fonts.googleapis.com/css?family=Pacifico&display=swap" rel="stylesheet">```.
<kbd>
  <img src="images-readme/google-fonts2.png" alt="google-fonts2">
</kbd>
* Coller le code obtenu dans le fichier HTML au dessus de la ligne ```<link rel="stylesheet" href="style.css">```

Soit :

```html
<head>
  <title>Jour 1</title>
  <link href="https://fonts.googleapis.com/css?family=Pacifico&display=swap" rel="stylesheet">
  <link rel="stylesheet" href="style.css">
</head>
```

* Copier la propriété CSS de la forme ```font-family: 'Pacifico', cursive;```.
* Coller dans le fichier CSS :

```css
h1 {
  font-family: 'Pacifico', cursive;
  color: green;
  font-size: 32px;
}

h2, h3, h4 {
  font-family: 'Pacifico', cursive;
  font-size: 28px;
}
```

## Insérer une vidéo Youtube

* Aller sur Youtube et choisir une video (https://www.youtube.com/watch?v=fBuSNu2m3XA&feature=youtu.be)
* Taper clique droit sur la vidéo.
* Cliquer sur "< > Copier le code d'intégration".
<kbd>
  <img src="images-readme/youtube.png" alt="youtube">
</kbd>

* Coller le code dans le fichier html la où vous souhaitez intégrer la vidéo :

Remarque : Il est possible de changer la taille de la vidéo grâce aux attributs "width" et "height".

```html
<h3>La recette en vidéo</h3>
<iframe width="500" height="300" src="https://www.youtube.com/embed/fBuSNu2m3XA" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
```
## Rendu final du fichier HTML avec le fichier CSS

<kbd>
  <img src="images-readme/css-screenshot.png" alt="css-screenshot">
</kbd>
