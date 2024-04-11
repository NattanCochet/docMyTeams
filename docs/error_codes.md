# Codes d'erreur

## Introduction

Durant l'utilisation du programme, l'utilsateur reçoit des codes selon la [commande](commands.md) utilisée et son résultat.
Voici comment sont composés ces derniers :

## Schéma des codes

- Le premier chiffre représente le type d'erreur renvoyé

| Chiffre | Erreur |
| :-----: | :----: |
| 0 | Aucune erreur, la commande s'est bien exécutée. |
| 1 | Le nombre d'arguments donné n'est pas correct. |
| 2 | L'utilisateur n'est pas connecté et n'a donc pas le droit d'executer une commande. |


- Le second chiffre indique le type d'arguments utilisé, en effet certaines commandes tels que `/use` ou `/create` peuvent prendre jusqu'à 4 types d'arguments différents (voir [commandes](commands.md))

- Les deux derniers chiffres, quant à eux, identifient la commande utilisée

| Identifiant | Commande utilisée |
| :----: | :----: |
| 01 | `/login` |
| 02 | `/logout` |
| 03 | `/users` |
| 04 | `/user` |
| 05 | `/send` |
| 06 | `/messages` |
| 07 | `/subscribe` |
| 08 | `/subscribed` |
| 09 | `/unsubscribed` |
| 10 | `/use` |
| 11 | `/create` |
| 12 | `/list` |
| 13 | `/info` |
| 14 | `/help` |
| 99 | Commande inconnue |