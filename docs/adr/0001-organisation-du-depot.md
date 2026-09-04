# 0001 - Un seul arbre de tests à la racine

## Contexte
Cinq équipes traitent le même sujet, chacune sur sa base. À la fin du sprint,
les cinq bases sont comparées, et le nombre de tests par type (unitaire,
intégration, bout en bout) entre dans la lecture. Si chaque équipe range ses
tests où elle veut, ce décompte n'a plus de sens.

## Options
1. Laisser chaque équipe organiser ses tests comme elle l'entend.
2. Un arbre de tests unique à la racine (`tests/unit`, `tests/integration`,
   `tests/e2e`), partagé par le backend et le frontend.
3. Un arbre de tests par application (`backend/tests`, `frontend/tests`).

## Décision
Option 2.

## Conséquences
Les cinq bases se comparent à la même aune, et compter les tests par type
devient direct. En contrepartie, les tests d'une application ne sont pas collés
à son code, ce qui est inhabituel côté frontend. Si la comparaison entre
équipes disparaissait, ce choix se rouvrirait.

Cet ADR est aussi un exemple : il montre le format attendu. Voir `TEMPLATE.md`.
