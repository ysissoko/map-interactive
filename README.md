# Projet map interactive
Un projet d'élaboration d'une map interactive qui affiche les informations des pays en temps réel.

# Requirements
- En tant qu'utilisateur, je souhaite pouvoir rechercher un pays et voir le drapeau + nom du pays
- En tant qu'utilisateur je souhaite pouvoir voir les informations du pays selectionné par la souris

# Pistes de réflexions
- Les évènements JS (saisie clavier + souris)
- L'envoi de requête HTTP via fetch pour récupérer les données sur les pays
- la manipulation du dom: chaque pays est représenté par un élément svg du dom

# Tâches
1. Ecrire une fonction qui permet de faire une requête GET vers l'API <https://restcountries.eu> afin de récupérer les information d'un pays sélectionné.

2. Récupérer l'élément sélectionné avec l'évènement *mouseover* <https://developer.mozilla.org/fr/docs/Web/API/Element/mouseover_event>

3. Afficher les informations dans une *div* au niveau de la position x et y du curseur (disponible dans l'évènement mouse over)

5. Utiliser un filtre de recherche par nom et/ou par région dans la requête envoyée à REST countries (Voir comment filtrer par nom lors de l'envoi de la requête vers l'API rest countries).

7. Récupérer la saisie clavier de l'utilisateur dans la barre de recherche et rafraichir la liste affichée en fonction de la saisie de l'utilisateur.

8. Récupérer le contenu de la select box avec la région sélectionnée et faire une requête "filtrée" vers rest countries