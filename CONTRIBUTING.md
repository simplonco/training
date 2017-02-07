# How to Contribute

> Guidelines for repository contributors

## Contexte historique

Depuis 2011, Simplon.co réunit de plus en plus d’essaimages avec donc de plus en plus de formateurs. Chaque formateur a pu donc au fur et à mesure de sa formation, créer, utiliser et centraliser du contenu pour ses apprenants. Cependant, aucune plateforme n’avait été utilisée afin de réunir correctement et d’une manière utile au développement ces différents contenus.

Suite à un audit auprès des formateurs, il s’est avéré que le meilleur choix de plateforme pour centraliser le contenu était **GitHub** : création de workshops, publications de supports de cours mais surtout revue de code et versionning, c’est donc la collection d'outils idéale à utiliser !

## Prérequis techniques

> https://guides.github.com/

> https://github.com/simplonco/git-training

## Nomenclature de nomage

`{techno}-{type}-{name}`

Les dépots doivent être écrits sous cette forme afin d’uniformiser les catégories et de faciliter le travail de recherche et de référencement au sein de GitHub.

Voici l’exemple d’un nom de repo, il est décomposé en **trois parties** :

`php-workshops-twig`

Il contient en **première partie** le nom de la technologie principale, ensuite il contient en **deuxième partie** le type de contenu du décrit dans le tableau ci-dessous (vous remarquerez que le nom est toujours au pluriel) :

<table>
  <tr>
    <td>training</td>
    <td>Root of GitLab repository for a technology - modules</td>
    <td>{techno}-training-{name}</td>
  </tr>
  <tr>
    <td>resources</td>
    <td>Currated list of external urls - resources</td>
    <td>{techno}-resources-{name}</td>
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

Pour terminer, la **troisième partie** contient le nom du thème abordé dans ce dépôt.

Il faut essayer d’être simple, fun et facilement compréhensible avec des mots clés pertinents, ex: `bootstrap-portfolio`, `UX-vs-UI`, `flexminator`, `send-mail-form`, etc...

## Créer un identifiant GitHub

Une connexion SSO avec Github est disponible. Nous vous conseillons d’utiliser ce mode de connexion afin de pouvoir facilement importer vos projets de votre compte Github à l’avenir.

## Créer son groupe correspondant à sa promotion

https://github.com/orgs/simplonco/teams

> Ajouter un apprenant dans son groupe de promotion

## Créer un repo dans le groupe principal de `simplonco`

https://github.com/organizations/simplonco/repositories/new

_To be continued.._
