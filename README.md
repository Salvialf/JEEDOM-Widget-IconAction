# IconAction

Widget pour Jeedom permettant d'appliquer une icône aux commandes d'action 'On' & 'Off' d'un équipement tout en en reflétant l'état.

Le widget inclus 28 appareils différents + 1 visuel par défaut. Il est possible d'ajouter ses propres icônes.

Après avoir appliqué le widget sur les 2 commandes 'On' & 'Off' de votre équipement, l'attribution des icônes s'effectue par l'ajout d'un paramètre optionnel "type" dans les 'Paramètres optionnels du widget' dans l'onglet 'Affichage' de la configuration de la commande.
Tous les paramètres optionnels doivent être appliqués sur les 2 commandes.

Il est également possible de spécifier la taille des icônes par l'ajout d'un paramètre optionnel "taille" ayant pour valeur la dimension souhaitée.
Par exemple: taille:100 = icône de 100px100px. Par défaut les icônes font 90px90px.

Vous avez la possibilité d'inclure vos propres icônes dans le widget. Le nommage des icônes est normalisé et doit respecter le format suivant: 
"type_off.png" & "type_on.png". 
Pour ajouter vos icônes, sur la page du Widget, cliquer sur le bouton "Fichiers" tout en haut puis "choisir un fichier" et ajouter vos images une par une. 