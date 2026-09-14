# Promotion [n] · Agona

## Ce que vous regardez

Agona est une formation où 25 aspirants et développeurs juniors travaillent
11 semaines sur une problématique réelle proposée par une entreprise
marraine, encadrés à temps plein par un formateur senior.

À chaque sprint de 2 semaines, **5 équipes partent de la même base de code et la font
évoluer chacune de leur côté**. À la fin du sprint, les 5 bases sont comparées
contre des critères publiés à l'avance, et la plus convaincante devient la base
commune du sprint suivant. Les équipes sont ensuite recomposées.

Le graphe git raconte exactement ça.

## L'entreprise marraine

**[Entreprise]**, [son métier en une ligne]. [Effectif], [ville]. [adresse du site]

[2 à 4 phrases de présentation : ce qu'elle fait, pour qui, depuis quand. Écrites
avec elle, relues par le formateur.]

**Le sujet qu'elle a fourni.** Elle a présenté ses problématiques, et le
formateur a retenu celle qui est devenue le sujet du parcours : [le sujet en une
phrase].

[2 à 3 phrases : le problème tel qu'il se pose chez elle, ce qu'il fallait
construire, et ce qui en fait un bon terrain de formation.]

**Ce que le parrainage recouvre.** L'entreprise marraine finance l'encadrement de
la promotion et fournit le sujet. Elle ne dirige personne, ne choisit pas les
participants et ne participe à aucune évaluation. Le travail se fait sur
l'infrastructure d'Agona, avec des données synthétiques. Le code de ce dépôt est
une production de formation, publiée sous Apache 2.0 dans les conditions décrites
plus bas.

## Comment lire le dépôt

- `main` porte la **lignée des bases communes**. Un tag par sprint.
- Les branches `sprint-N/equipe-N` portent le travail de chaque équipe pendant
  le sprint N. Les quatre branches non retenues restent visibles.
- Chaque fusion dans `main` marque la base retenue à l'issue d'un sprint.

Les dépôts de travail sont privés pendant le sprint. Ils sont publiés ici après
les soutenances, une fois le classement prononcé.

## Les critères

Ils sont publics et remis aux apprenants dès le premier jour :
[la grille de revue de code](https://agona.dev/grille-revue/),
[le barème de la soutenance](https://agona.dev/soutenance/),
[le déroulé de la peer-review](https://agona.dev/peer-review/) et
[la consigne de développement](https://agona.dev/consigne/).

## Licence et droits

Apache 2.0. **Chaque contributeur conserve ses droits d'auteur** sur ses propres
contributions et en concède l'usage sous cette licence, contribution par
contribution, au moyen d'une signature `Signed-off-by` sur chacun de ses commits
(`git commit -s`).

Voir [CONTRIBUTORS.md](CONTRIBUTORS.md) et [NOTICE](NOTICE).

## Conditions de publication

Ce dépôt est publié en l'état, sans obligation de résultat ni engagement de
maintenance. Toute mise en production relève de la responsabilité de qui la
décide.
