# repwar

Projet personnel s'inspirant du [projet corewar effectué en fin de première année à Epitech](https://github.com/MikaelVallenet/Corewar).

L'idée derrière ce projet consiste à créer une commande sous Bash permettant de :
- descendre récursivement dans des sous-répertoires du répertoire d'où la commande a été lancée
- faire combattre l'ensemble des champions présent dans le sous-répertoire actuellement ouvert au sein d'une arène définie par l'utilisateur
- remonter récursivement les champions gagnants de chaque sous-répertoire vers le répertoire originel

Pour résumer, cette commande permet d'effectuer un tournoi entre plusieurs champions séparés entre différents sous-répertoires et de déterminer lequel est le plus efficace au fil et à mesure de chaque round en déplacant le gagnant d'un round vers le répertoire parent jusqu'à atteindre le combat final du tournoi.

Ce projet est actuellement en cours de production

Les étapes de celui-ci sont :
- écrire des champions
- effectuer un premier combat entre plusieurs champions
- effectuer un tournoi de plusieurs combats
- écrire le programme permettant d'utiliser la commande repwar et d'obtenir le résultat souhaité
