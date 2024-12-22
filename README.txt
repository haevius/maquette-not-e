Explications : HTML5 & CSS3

Compréhension des bases de HTML5 et CSS3   
HTML est le langage utilisé pour structurer une page web (organiser les éléments tels que les titres, paragraphes, images, liens, etc.) tandis que CSS est utilisé pour styliser cette structure.
Il définit le style visuel des éléments présents dans le fichier html, incluant la mise en page, les couleurs, ou encore les polices d'écriture.

Compréhension de la structure d’une page web  
Le squelette de base d’une page web contient tout d'abord  <!DOCTYPE html>. C'est ce qui spécifie que le document est en HTML5, sa présence est donc obligatoire.
- La balise <html> constitue la racine de la page. C'est ce qui va contenir toutes les autres balises de notre page web.
- La balise <head> quant à elle inclut toutes les données comme les liens CSS, les polices d'écriture et les scripts.  
- Enfin, la balise <body> contient tout ce qui est visible sur la page et donc tout son contenu(textes, images, vidéos, boutons...).

Utilisation des balises HTML courantes  
La sémantique en HTML désigne des balises. Ces balises sont dites sémantiques. Elles donnent une indication sur le contenu qu’elle entoure.
Nous avons par exemple :  
- <header> pour les en-têtes,
- <nav> pour les menus de navigation,
- <main> pour le contenu principal de la page, qui est une balise unique (ne peut être utilisée qu'une fois),
- <section> pour une section logique regroupant un ensemble de contenu dans le même thème,
- <footer> pour le pied de page.
Ces balises rendent le contenu plus accessible et mieux interprété par les moteurs de recherche et permettent également de mieux organiser sa page web.

Mise en pratique des styles avec CSS3  
Pour appliquer des styles aux éléments HTML, CSS utilise plusieurs indicateurs :
- Il y a id qui est un sélecteur unique utilisé pour styliser un élément précis. Il ne peut être utilisé que sur un élément.  
- Et il y a class qui est quant à lui un sélecteur réutilisable. Il peut donc être appliqué à plusieurs éléments.  

Mises en page simples en CSS3
Pour mettre notre page web en page avec CSS3, on connait trois attributs :
- Flexbox, qui est utilisé pour aligner et répartir des éléments sur un axe (horizontal ou vertical).
- Grid, qui offre une mise en page adéquate pour structurer des colonnes et des lignes.
- Et position, qui définit le placement des éléments.

Utilisation des fonctionnalités avancées de CSS3
Nous avons présenté les fonctionnalités basiques de CSS3, qui sont nécéssaire pour une mise en page claire. Cependant, il existe également des fonctionnalités plus avancées :
- Les pseudo-classes servent à ajouter des styles basés sur des états spécifiques (:hover, :focus, ...).
- Et les transitions permettent d’animer les changements de styles (comme avec une transition de couleur ou d’opacité).
Ces fonctionnalités, en plus de compléter celles expliquées précédemment, vons permettre de rendre la page web bien plus attractive.

Intégration de médias dans une page Web
Dans une page web, nous pouvons intégrer divers médias, qui apporteront davantage de contenus et rendront la page plus visuelle.
Les images :
    - Pour les intégrer, il est mieux d'utiliser des formats modernes comme WebP ou SVG plutot que des PNG.
Les Vidéos :
    - Dans la même optique que les photos, il vaut mieux préférer les formats compatibles web tels que MP4 ou WebM pour que leur format soit plus optimisés.

Compréhension des formulaires basiques
Un formulaire HTML collecte des données via différentes balises. Nous avons :
- <form> qui sert à regrouper tous les éléments d'un formulaire,
- <input> qui accepte divers types de données (texte, email, fichiers, ...),
- <textarea> qui permet d’insérer du texte long tel qu'un message,
- Et enfin <button> qui permet de soumettre un formulaire.
Les attributs action et method définissent la destination et le mode de traitement des données.

Optimisation d’un site web
Nous avons précédemment affirmé que nous pouvions intégrer divers types de médias dans des pages web. Ces médias peuvent aussi être optimisés :
   - en réduisant les tailles des fichiers,
   - en chargeant les médias de manière asynchrone (télécharger et charger en arrière-plan sans bloquer l'affichage de la page principale) ou conditionnelle (charger seulement en cliquant sur un bouton "play" ou uniquement si elles entrent dans le champ de vision de l'utilisateur) pour améliorer les performances.