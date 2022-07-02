### Exercice 3 : protocole HTTP

**En binôme**

- Le HTTP est le protocole utilisé par le client et le serveur pour échanger des données.
- Le client effectue une requête au serveur pour demander par exemple la page des commandes.
- Le serveur reçoit la requête et le traite.
- Le serveur renvoie :
 - la page des commandes contentant les informations de l'utilisateur connecté actuellement sur le site web
 - un en-tête contenant le code de réponse HTTP du serveur
 Ce code est une énumération (liste fermée) dont les valeurs peuvent regroupés dans 5 grands familles :
 - 10x : informations
 - 20x : succès
 - 30x : redirection
 - 40x : erreur côté client
 - 50x : erreur côté serveur

1. Toujours sur le même dépôt que l'exercice3
2. Créez une nouvelle branche nommée `feature/exercice3` à partir de la branche principale `main` 
3. Modélisez sous forme de diagramme de classe, le fonctionnement de l'architecture Client/Serveur avec l'utilisation du protocole HTTP
4. Commitez votre travail sur la branche précédemment créée