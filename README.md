Challenge
C'est à toi de jouer maintenant. Tu vas réaliser ta première page web en utilisant un fichier HTML et une feuille CSS.

Avant de commencer, assure-toi de disposer d'un éditeur de texte avec coloration syntaxique, par exemple Sublime Text.

Sur ton ordinateur, commence par créer un dossier que tu appelleras comme tu le souhaites. Ouvre ton éditeur de texte, et crée un nouveau fichier que tu enregistreras dans le dossier créé. Tu appelleras ce fichier index.html. Puis crée un second fichier que tu appelleras style.css.

Dans le fichier index.html, insère le code suivant :

<!DOCTYPE html>
<html>
<head>
<link rel="stylesheet" href="style.css"/>
<title> Le titre qui apparaitra dans le navigateur </title>
<meta charset="UTF-8">
</head>

<body>
<h1> Ici le titre principal </h1>
<p> Et voilà le texte de la page</p>
<h2> On peut créer jusqu'à six niveaux de titres en HTML </h2>
<p> Et voici un autre paragraphe </p> 
</body> 
</html>
En ligne 4, nous indiquons comment s'appelle notre feuille de style CSS. Si tu appelles ton fichier différemment, pense à bien l'indiquer, pour que le lien soit correctement effectué.

Tu peux ouvrir le fichier index.html dans ton navigateur pour voir ta page HTML. Pour l'instant, la mise en forme est celle par défaut de ton navigateur, car nous n'avons rien renseigné dans la feuille CSS.

Dans le fichier style.css, insère le code suivant, et enregistre ton fichier.
h1{
font-size: 30px;
text-align: center;
color: #de7471
}

p{
font-size: 20px;
text-align: left;
font-family: Helvetica, sans-serif;
}

body {
background-color: #007471;
}
Les indentations n'ont pas d'importance en CSS et en HTML. Mais c'est nettement plus lisible de bien les utiliser.

Tu peux actualiser le fichier index.html dans ton navigateur pour voir ta page HTML mise en forme.

C'est à toi de jouer : personnalise le contenu et la mise en forme pour en faire une page intéressante et élégante. Essaye d'intégrer des liens grâce à la balise a.
Par exemple :
<a href= "http://www.wildcodeschool.com"> titre du lien </a>
Essaye aussi d'intégrer une image grâce à la balise img, comme par exemple :

<img src= "https://res.cloudinary.com/wildcodeschool/image/upload/c_fill,h_50/v1/static/irjoy97aq0eol8bf6959">
Ton but est maintenant de rendre accessible ta page au plus grand nombre. Pour cela, tu vas l'héberger sur github.
Pour publier sur github, tu peux faire très simple, car tu découvriras github plus en détail par la suite. Voici les étapes à suivre :

Connecte-toi à github (ou crée toi un compte si tu n'en as pas, c'est gratuit)
Crée un nouveau repository (c'est comme un dossier principal sur github) que tu appelleras du même nom que ton compte github (c'est très important) + .github.io (c'est très important également). Tu laisseras bien ce repository en public.
 

Va dans ton repository fraichement créé, puis upload tes 2 fichiers (HTML + CSS) dans ce repository. Tu peux cliquer via l'interface sur "upload", puis tu pourras faire un glisser déposer. (Tu apprendras un jour à te servir de Git dans un usage plus concret. Pour l'instant, restons sur l'interface web par simplicité)
 

Et c'est tout ! Ta page est maintenant accessible à l'adresse https://username.github.io (en remplaçant évidemment username par ton compte github).