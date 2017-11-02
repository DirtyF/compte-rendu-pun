# Intervention au Master Publication Numérique de l'ENSSIB de Lyon

## Vers des chaînes de publication numérique continue

Qu'est-ce qui différencie les textes d'un livre, d'un magazine, d'un site web ou de code informatique ?

Pas grand chose en fait, si l'on considère qu'ils vont tous devoir être saisis dans un éditeur de texte, puis validés, transformés et publiés. Simplement d'un côté on écrit dans une langue, de l'autre dans un langage informatique.

L'industrie logicielle, notamment via l'open-source, s'est dotée depuis un peu plus d'une dizaine d'années d'une palette d'outils visant à automatiser et à faciliter la publication en continu. Au cœur de ces systèmes, une notion essentielle permet cela : la gestion de versions (parfois aussi appelé versionnement). C'est *la* porte d'entrée vers les systèmes de publication actuels.

Ces outils ne se sont pas encore propagés dans toutes les industries, notamment celle de l'édition, qui si j'en crois les retours de mes amis auteurs, continuent de fonctionner pour la majorité _à l'ancienne_ : traitement de texte, aller-retour par email, etc.

L'objectif aujourd'hui est de vous faire découvrir une partie de l'écosystème utilisé dans l'industrie logicielle, de vous présenter les processus de travail qui en découlent et de vous montrer que ces outils sont de plus en plus accessibles.

Cette chaîne de publication numérique utilisée dans l'industrie logicielle est tout à fait utilisable dans d'autres secteurs, dont le logiciel n'est pas le cœur de métier.

## La gestion de versions décentralisée collaborative

Vous êtes peut-être déjà familiers avec la notion de *high-frequency trading* en économie et vous êtes tous témoins de de la course à l'automatisation à outrance en général dans notre société.

La publication numérique n'échappe pas à la règle et obéit de nos jours à une cadence de plus en plus élevée. À tel point que les mises à jour se font parfois plusieurs fois par jour. C'est le cas pour des articles de journaux en ligne. Vous l'aurez surement remarqué si vous utilisez des applications sur votre téléphone et que vous recevez des notifications de mises à jour d'applications. Ces mises à jour sont si régulières qu'elles sont parfois transparentes. Par exemple, des navigateurs web de bureau comme Google Chrome ou Firefox ne demandent même plus à l'utilisateur de faire les mises à jour, elles sont effectuées automatiquement en arrière-plan pour s'assurer que vous bénéficiez des dernières fonctionnalités.

Ces logiciels sont développés par des équipes qui doivent collaborer, souvent à distance sur une même base de code. C'est par exemple le cas pour le noyau du système d'exploitation GNU/Linux, crée par Linus Torvalds en 1991. Ce développeur a lancé un appel à collaborer sur un logiciel open-source et le projet a rapidement pris de l'ampleur. Il a fallut s'organiser pour que tout le monde puisse travailler sur le même logiciel et à l'époque il existait déjà des logiciels de gestion de versions comme CVS, qui permettaient de centraliser les modifications et de versionner les changements. Chaque nouveau collaborateur pouvait alors récupérer la dernière version du logiciel, y apporter des modifications et soumettre ensuite ces modifications aux mainteneurs.

Mais ce modèle centralisé n'était pas forcément pratique, il fallait pouvoir se connecter au dépôt central, les fusions de modifications étaient problématiques et coûteuses en temps. Face à ce constat et devant le manque de solution open-source, en 2005 le même Linus Torvalds a entrepris de développer un nouveau système de fichiers qui faciliterait le versionnement et la collaboration. **Git** était né et cette nouvelle génération de gestion de versions allait bouleverser l'industrie du logiciel.

Aujourd'hui Git est le logiciel de gestion de versions décentralisé le plus populaire, utilisé par des millions de personnes chaque jour. Git est un logiciel en ligne de commande très complet et très puissant, et rapidement des interfaces ont vu le jour pour faciliter sa prise en main par le plus grand nombre. Des services commerciaux comme GitHub ont également connu un essor phénoménal en proposant des fonctionnalités complémentaires à Git qui facilitent l'échange autour des projets open-source.

Pour vous donner une idée, voici les chiffres récemment publiés par GitHub, qui est la société qui héberge actuellement le plus de code open-source au monde : [https://octoverse.github.com/](https://octoverse.github.com/)

## Collaboration en ligne

GitHub est devenu le réseau social des développeurs, ils peuvent suivre des projets, des personnes, discuter des modifications, etc. Grâce à une interface utilisateur conviviale et à un workflow de publication simplifiée, GitHub facilite la collaboration, notamment pour les projets open-source. Des services similaires comme [BitBucket](https://bitbucket.org/) ou [GitLab](https://gitlab.com) ont rapidement emboité le pas.

## Le workflow de GitHub

Git offre de nombreuses possibilités en terme d'organisation, cependant un workflow assez simple est souvent adopté. Pour collaborer sur un projet existant on répétera la séquence suivante :

1. Créer une branche pour isoler son travail
2. Enregistrer ses modifications
3. Publier la branche sur son dépôt distant et ouvrir une demande de fusion sur le dépôt principal
4. Discussion, revue de code, validation (avec un éventuel retour à l'étape 2)
5. Fusion des modifications par un administrateur du dépôt
6. Suppression de la branche de travail
7. Rince and repeat :smile: 

Quelques liens pour s'y mettre : 

* [Essayer Git](https://try.github.io/levels/1/challenges/1)
* [Comprendre le GitHub Flow](https://guides.github.com/introduction/flow/)

## [Le compte-rendu de mon intervention par Anne-Laure Copinot et Marlène Tognifode](https://dirtyf.github.io/compte-rendu-pun/gestion-de-versions-numerique/)

## [Les slides de présentation](./slides/)
