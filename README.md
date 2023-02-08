<h1 align="center">Agence de voyage</h1>

<div align="center">
  <a href="https://devdocs.io/html/">
    <img src="https://img.shields.io/badge/html5%20-%23e34f26.svg?&style=for-the-badge&logo=html5&logoColor=white" alt="HTML" />
  </a>
  <a href="https://devdocs.io/css/">
    <img src="https://img.shields.io/badge/CSS3-1572B6?&style=for-the-badge&logo=css3&logoColor=white" alt="CSS" />
  </a>
</div>


## Projet : Réalissation d'une page d'accueil d'une agence de voyage en HTML &amp; CSS
## Informations globales :

- Status terminé
- Projet réaliser seul
- Lien vers le [GitHub](https://github.com/archi974/AgenceVoyage)

## Mise en situation :

L’entreprise souhaite développer un site Internet qui permette aux usagers de trouver des hébergements et des activités dans la ville de leur choix.
Vous êtes chargé d'intégrer l'interface du site avec du code HTML et CSS. Pour cela, vous travaillez en étroite collaboration avec Sarah, la CTO, et Loïc, l’UI designer. 

## Contrainte :

- Fonction recherche

  - Le champ de recherche est **un champ de saisie**, le texte doit donc pouvoir être édité par l'utilsateur.
  - Il faut **englober ce champ dans un formulaire**. La partie Recherche ne doit pas être fonctionnelle - il s'agit d'une première version pour valider l'interface

- Cartes Hébergements et activités :

  - **Chaque carte** d'hébergement ou d'activité **devra être cliquable** dans son intégralité.
  - Pour l'instant, les liens sont vides. On peut utiliser un attribut `href="#"` pour simuler la présence de lien.
  
- Filtres de recherche :

  - Les hébergements peuvent être filtrés par thématique, comme le budget ou l'ambiance.
  - Les **filtres** doivent **changer d'apparence au survol**. Par contre, ils ne doivent pas être fonctionnels.

- Liens "Hébergements" et "Activités" :

  - **Les textes "Hébergements" et "Activités"**, situés dans l'en-tête, **sont des liens**. Ils doivent mener respectivement vers la setion "Hébergements à Marseille" et "Activités à Marseille".

- Largeur max :

  - Pour éviter d'étirer la page web sur la largeur de façon excessive, il va falloir **déterminer une largeur maximum de 1400px.**

- Desktop first :

  - Il faut d'abord réaliser l'intégration pour les tailles d'ordinateurs.
  - l'utilisation des **Media Queries nous permettra de réaliser l'intégration pour les différents supports.**

- Breakpoints :

  - Nous avons convenu avec le designer UI d'**utiliser 992px et 768px**:
    - `>=992 px` pour les écrans d'ordinateurs;
    - `>=768 px` pour les tablettes;
    - Pour les téléphones, tout ce qui est en dessous de 768px.
    
- Couleurs :

  - Les **couleurs** de la charte sont le **bleu `#0065FC`.**
  - Une version **plus claire du bleu `#DEEBFF`.**
  - **Le gris `#D9D9D9`.**
  - Une version **plus claire du gris `#F2F2F2`.**
  
- Police :

  - La **police** du site est **[Raleway](https://fonts.google.com/specimen/Raleway)**. Nous pouvons passer par **Google Fonts** pour importer facilement cette police dans le code.

- Mise en page :

  - Il est recommandé d'utiliser **Flexbox.**

- Balises sémantiques :

  - Il est important d'**utiliser des balises sémantiques**, au minimum "header", "nav", "h1-h2-h3", "main", "section", "article" et "footer".
  
- Validité du code :

  - Afin d'harmoniser les outils avec toute l'équipe, il faudra utiliser **l'IDE Visual Studio Code** pour le développement du site.
  - Le **code** doit être **valide aux validateurs W3C** [HTML](https://validator.w3.org/) et [CSS](https://jigsaw.w3.org/css-validator/).
  - Le code HTML ne doit pas contenir de propriété CSS.
  - Lors du passage du desktop au mobile et à la tablette, **ne pas dupliquer le code** HTML (exception faite dans le formulaire avec le mot "Rechercher" et l'icône de la loupe).
  - **Privilégier l'utilisation des classes CSS** pour cibler un élément, plutôt que d'utiliser le nom de l'élément lui-même.
  - **Ne pas dupliquer des classes CSS inutilement**. Exemple: si 4 éléments sont identiques du point de vue de la mise en forme, alors utiliser une seule et même classe CSS, et non pas 4.
  
- Compatibilité navigateur :

  - La **maquette** doit être **compatible avec les dernières versions de Google Chrome et de Mozilla Firefox.** Il faudra tester la page web sur ces deux navigateurs.
  
- Restrictions :

  - **Aucun framework CSS** (type BootStrap ou Tailwind CSS) ou préprocesseur CSS (type Sass ou Less) ne doit être utilisé.
  - **Aucun autre langage** ne doit être utilisé (comme JavaScript, par exemple).

## Instruction d'installation et d'utilisation :

- Installer [Visual Studio Code](https://code.visualstudio.com/)
- Installer l'extension "Live Server"
- Après récupération du code et ouverture avec Visual Studio Code, lancer "Go Live" en bas à droite

## Bugs connus et corrections éventuelles apportées :

  - Bug d'image en Css qui donne un espace en bas, l'utilisation du `Display: flex` sur l'image règle le problème.

## FAQ

  - Comment espacer mes cartes sans ajouter de margin ou de padding sur les bords ?
  Utiliser les pseudo-classe [`nth-child`](https://developer.mozilla.org/en-US/docs/Web/CSS/:nth-child), [`first-child`](https://developer.mozilla.org/en-US/docs/Web/CSS/:first-child) ou [`last-child`](https://developer.mozilla.org/en-US/docs/Web/CSS/:last-child)

## Droits d’auteurs et informations sur la licence.

Réaliser par Vincent K/BIDI.

©2000 [Openclassroom](https://openclassrooms.com/fr/), Inc. Tout droit réservés.


![Openclassroom](https://camo.githubusercontent.com/e47c349811ac404b8147bd362c598e61c7d20225df17499c6373b44f6ee08a3d/68747470733a2f2f31746f3170726f67726573732e66722f77702d636f6e74656e742f75706c6f6164732f323031392f30352f6f70656e636c617373726f6f6d732d65313535373736313233363135382e706e67)
