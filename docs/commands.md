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
> Déconnecte l'utilisateur de l'interface de ligne de commandes.

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

/messages
```
    /messages ["user_uuid"]
```
> Liste les messages échangés avec l'utilisateur spécifié.

/use
```
    /use
    /use ["team_uuid"]
    /use ["team_uuid"] ["channel_uuid"]
    /use ["team_uuid"] ["channel_uuid"] ["thread_uuid"]
```
> Mets à jour la sélection de l'utilisateur pour effectuer diverses opérations par la suite.

/create
```
    /create ["nom_de_la_ressource"] ["description_de_la_ressource"]
```
> Créé une ressource en fonction du /use précédent (team, channel, thread ou commentaire).

/subscribe
```
    /subscribe ["team_uuid"]
```
> Permet de s'abonner et ainsi recevoir des notifications ou la possibilité de modifier des teams.

/unsubscribe
```
    /unsubscribe ["team_uuid"]
```
> Se désabonne d'une team.

/subscribed
```
    /subscribed
    /subscribed ["team_uuid"]
```
> Liste tous les abonnements de l'utilisateur ou d'une team entrée.

/info
```
    /info
```
> Liste les informations d'une ressource en fonction du /use précédent.

/list
```
    /list
```
> Affiche les sous ressources d'une ressource en fonction du /use précédent.
