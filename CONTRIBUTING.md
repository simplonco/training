# How to Contribute

## Contexte

Depuis 2011, Simplon réunit de plus en plus d’essaimages en France avec donc de plus en plus de formateurs. Chaque formateur a pu donc au fur et à mesure de sa formation, créer, utiliser et centraliser du contenu pour ses apprenants. Cependant, aucune plateforme n’a été utilisée afin de réunir correctement et d’une manière utile au développement ces différents contenus. Après un audit auprès des formateurs, il s’est avéré que **le meilleur choix pour centraliser le contenu était Github**. Création de workshops, publications de supports de cours mais surtout revue de code et versionning, c’est donc l’outil idéal à utiliser. L’utilisation de Gitlab permet donc d’utiliser des repos Git très facilement tout en ayant **la possibilité de créer des repo privés et illimités**.

## Nomenclature

`{techno}-{type}-{name}`

Les repo doivent être écrits sous cette forme afin d’uniformiser les catégories et de faciliter le travail de recherche et de référencement au sein de GitLab.

Voici l’exemple d’un nom de repo, il est décomposé en **trois parties** :

`php-workshops-twig`

Il contient en **première partie** le nom de la technologie principale, ensuite il contient en **deuxième partie** la catégorie du repo d’après le tableau ci-dessous (vous remarquerez que le nom est toujours au pluriel) :

<table>
  <tr>
    <td>ressources</td>
    <td>Currated list of external urls / root of GitLab repository for a technology - modules</td>
    <td>{techno}-training-{name}</td>
  </tr>
  <tr>
    <td>project(s)</td>
    <td>Long project activity, without tutorial, but some functional / technical specifications, to engage students autonomy</td>
    <td>{techno}-project(s)-{name}</td>
  </tr>
  <tr>
    <td>challenge(s)</td>
    <td>TDD exercices validated by GitLab CI (cool for algorithms teaching: input => output), can be imported from exercism.io</td>
    <td>{techno}-challenge(s)-{name}</td>
  </tr>
  <tr>
    <td>exercise(s)</td>
    <td>Exercices given without automated validation, with just a short subject / explanation</td>
    <td>{techno}-exercise(s)-{name}</td>
  </tr>
  <tr>
    <td>workshop(s)</td>
    <td>Guided tutorial / courses / short code activity</td>
    <td>{techno}-workshop(s)-{name}</td>
  </tr>
</table>


Pour terminer, la **troisième partie** contient le nom du thème abordé dans ce repo.

Il faut essayer d’être simple et qu’il soit facilement compréhensible avec des mots clés pertinents (bootstrap, ui, ux, flex, materialize, jquery, send-mail etc…)

## Éviter la redondance de contenu

Afin de garder une cohérence dans le projet, il est nécessaire de bien faire une recherche dans le contenu avant de publier un nouveau repo.

_// TO BE CONTINUED_

## Créer un identifiant Gitlab

Une connexion SSO avec Github est disponible. Nous vous conseillons d’utiliser ce mode de connexion afin de pouvoir facilement importer vos projets de votre compte Github à l’avenir.

## Créer son groupe correspondant à sa promotion

_// TO DO_

## Ajouter un repo dans le groupe principal de simplon-co

_// TO DO_

## Ajouter un repo du groupe simplon-co dans son groupe de promotion

_// TO DO_

## Ajouter un apprenant dans son groupe de promotion

_// TO DO_

## Sources externes

_// TO DO_
