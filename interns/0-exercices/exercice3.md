### Exercice 3 : protocole HTTP

**En binôme**

- Le HTTP est le protocole utilisé par le client et le serveur web pour communiquer.
- Le client effectue une requête au serveur pour demander par exemple la page des commandes du site web `cdiscount.com`.
- Le serveur reçoit la requête et le traite.
- Le serveur renvoie :
 - Le code d'état de la réponse dont la valeur est 200 en cas de succès, c'est-à-dire que le serveur répond correctement à la demande du client. Cette partie constitue l'en-tête de la réponse.
 - La page des commandes contentant les informations de l'utilisateur connecté actuellement sur le site web. Cette partie constitue le corps de la réponse.
 Ce code est une énumération (liste fermée) dont les valeurs peuvent être regroupées dans 5 grandes familles :
 - 1xx : informations
 - 2xx : succès
 - 3xx : redirection
 - 4xx : erreur côté client
 - 5xx : erreur côté serveur

[Liste des codes HTTP](https://fr.wikipedia.org/wiki/Liste_des_codes_HTTP)

1. Toujours sur le même dépôt des exercices.
2. Créez une nouvelle branche nommée `feature/exercise3` à partir de la branche principale `main`.
3. Modélisez sous forme de diagramme de classe, l'utilisation du protocole HTTP avec les codes réponses par le service web.
4. Commitez votre travail sur la branche `feature/exercise3`.
5. Envoyez la branche `feature/exercise3` vers le dépôt distant.