# Commands

/help
```
    /help
```
> Affiche tout les messages d'aides de tout les commandes

```
    /help ["command_name"]
```
> Affiche le message d'aide sur la commande donnée par l'utilisateur

/login
```
    /login ["username"]
```
> Connecte l'utilisateur au service et génère un nouvel UUID quand un nouvel utilisateur est crée.

/logout
```
    /logout
```
> Déconnecte l'utilisateur de l'interface de ligne de command.

/users
```
    /users
```
> Liste les détails (username, uuid, logged_status...) à propos de tout les utilisateurs du serveur.

/user
```
    /user ["uuid"]
```
> Liste les détails (username, uuid, logged_status...) à propos de l'utilisateur désigné.

/send
```
    /send ["uuid"] ["message body"]
```
> Envoie message_body à l'utilisateur nominé par l'UUID