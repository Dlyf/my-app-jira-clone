# context

JIRA clone : C'est une application permettant d'afficher une liste de ticket ordonnée par des status (TODO<IN_PROGRESS<DONE) matche avec leur status.
Construire un JIRA clone dans React
Coder la partie front-end et relier sur un API pre-existé.

# actions 

Créer deux composants : 
. Ticket List 
Displays a list of tickets : assigne_picture, title, status
The tickets are ordered by status (TODO > IN_PROGRESS > DONE)

. Board
Display a list of tickets with assigne_picture, title in the column that matches their status

# user interaction 
- Quand un utilisateur clique sur un ticket (list of board), le ticket va changer en un status suivant. 
- le status va se mettre à jour et peut être utilisé dans l'appli.
Si l'utilisateur clique dans le composant "ticket list", le status change dans le composant "board"

# fetch real data 

https://jsonplaceholder.typicode.com/todos

# techno 
React

https://ibb.co/p3Dv9B2