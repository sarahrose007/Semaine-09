# Intégration maquette - Creative

> Bonjour à toi jeune entrepreneur, es-tu prêt à intégrer une maquette en équipe?

![entrepreneur](../images/question-repondue.jpg)

Tu vas devoir travailler avec un collègue pour reproduire cette maquette de la manière la plus précise possible.

## Consigne

Par groupe de 2 vous allez devoir vous répartir la masse de travail pour être le plus optimal possible. Voici quelques conseils:

- Créez un Trello pour vous assigner des tâches spécifiques et répartir le travail. Par exemple quelqu'un peut s'occuper du header et footer, pendant que l'autre intégrateur s'occupe du contenu principal de la page.
- Procédez composants par composants. Créez les dans une page vide de tout autre élément, assurez-vous qu'il fonctionne et puis intégrez le dans le reste du travail.
- Créez un Repository et invitez votre collègue comme `contributor`
- Utilisez Sass pour optimiser votre CSS
  - Créez un fichier `main.scss` pour tous vos styles globaux (body, html, div,...)
  - Créez et importez d'autres fichiers `.scss` pour chacun des composants de votre maquette (variables, functions, header, articles, sidebar, footer,...)
- Il ne faut pas reproduire à l'identique le contenu, mais faire en sorte que l'on puis en ajouter et que tout se passe bien. En gros, sur la page d'accueil, pas besoin d'afficher nécessairement 4 articles dans le container central, tout comme il n'est pas obligé d'en avoir trois dans le widget "Recent Posts". Faites en sortes que le CSS soit prêt pour accueillir un nombre "illimité" de contenu.
- Mobile first? Pas spécialement, car ici la maquette est déjà pensé telle qu'elle, donc commencer par ce que vous avez le plus simple.
- Javascript? Pas besoin.
- Il y a un tout début de code disponible dans le dossier `SASS` et dans le fichier `index.html`. Vous pouvez les utiliser ou repartir de zéro. Vous aurez besoin de la commande suivante:

`sass --watch ./sass/main.scss ./css/main.css`

## Groupes

Groupe 1 | Groupe 2 | Groupe 3
--- | --- | ---
Sara | Angélique | Méthode
Jean-Eudes | Ezechiel | Samantha

Groupe 4 | Groupe 5
--- | --- | ---
Zena | Lionel
Zena | Fanny 

## Informations maquette

Voici les informations fournie par votre designer concernant la maquette. Malheureusement il n'a pas de compte Figma pro et ne peut pas vous y donner accès. Vous allez devoir vous contenter de ses informations et des screenshots.

- Votre designer vous a envoyé des screenshots d'une page d'accueil et d'une page d'article complet. Reproduisez les deux.
- Le site à un container de largeur maximum de **1200px**
- **Page d'accueil:** Le container des articles sur la page principale fait **800px** max de largeur.
- **Page d'accueil:** La sidebar fait **332px** max de largeur.
- **Page d'accueil:** Le carrousel fait **1600px** max de largeur et **480px** de hauteur.
- **Page d'article complet:** L'image de l'article fait une largeur max de **786px** sur **491px** en hauteur max
- Les couleurs:
  - Le background: <span style="color:#33264E">**#33264E**</span>
  - Le background footer et le bg des cards des articles: <span style="color:#362953">**#362953**</span>
  - Les liens et éléments important: <span style="color:#EE3E52">**#EE3E52**</span>
  - Les couleurs du gradient sur les boutons: <span style="color:#FF6071">**#FF6071**</span> / <span style="color:#FF7E8E">**#FF7E8E**</span>
  - Les couleurs des catégories:
    - <span style="color:#673AB7">**#673AB7**</span>
    - <span style="color:#5567DA">**#5567DA**</span>
    - <span style="color:#1E88E5">**#1E88E5**</span>
    - <span style="color:#27CC81">**#27CC81**</span>
    - <span style="color:#38C4D1">**#38C4D1**</span>
    - <span style="color:#E91E63">**#E91E63**</span>
  - Les couleurs des réseaux sociaux;:
    - <span style="color:#63CDF1">Twitter **#63CDF1** </span>
    - <span style="color:#507CBE">Facebook **#507CBE** </span>
    - <span style="color:#D62976">Instagram **#D62976** </span>
    - <span style="color:#EE3E52">Pinterest **#EE3E52** </span>
- Les polices:
  - Le logo utilise **Vampiro One**
  - Les titres utilisent **Playfair Display**
  - Le texte est en **Muli** / **Mulish**
  - Ce sont des Google Font
  - La taille n'a pas d'importance tant que vous respectez l'échelle établie dans la maquette.
- Les icônes:
  - Le fond des icônes est un dégradé dont les couleurs sont notés plus haut.
  - Les icônes en elle-même peuvent être différentes tant qu'elle transmette le même message (liens sociaux, recherche, commentaires, partager)

## Screenshots

Pour garder le repository le plus léger possible, vous pouvez retrouver tous les screenshots sur mon [Google Drive](https://drive.google.com/drive/folders/1x6AU9gIeHi-FXgQAhRd5iG6twRYGevPP?usp=sharing)

Vous trouverez également une sélection d'images qui peuvent servir d'illustration d'article. Mais n'hésitez pas utiliser les vôtres. Si vous en êtes en panne d'inspiration, je vous conseille le site [Pexels](https://www.pexels.com/fr-fr/) qui regorge d'images libre de droit pour utiliser dans vos maquettes!