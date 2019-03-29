# IconAction

Widget pour Jeedom permettant d'appliquer une icône aux commandes d'action 'On' & 'Off' d'un équipement tout en en reflétant l'état.

<img src="/doc/IconAction.gif" alt="gif présentation"/>


Le widget inclus 30 appareils différents + 1 visuel par défaut. Il est possible d'ajouter ses propres icônes.
<img src="/doc/LogoTypeList.jpg" alt="Liste Types"/>

<blockquote>Liste des noms d'équipements intégrés au widget: <a href="/doc/TypeList.md">Liste "type"</a>.</blockquote>


Après avoir appliqué le widget sur les 2 commandes 'On' & 'Off' de votre équipement, l'attribution des icônes s'effectue par l'ajout d'un paramètre optionnel "<i><b>type</b></i>" dans les 'Paramètres optionnels du widget' dans l'onglet 'Affichage' de la configuration de la commande.
Tous les paramètres optionnels doivent être appliqués sur les 2 commandes.
<blockquote><b>Conseil:</b> Décocher la case 'Afficher' sur la commande 'Etat' associée.</blockquote>

Il est également possible de spécifier la hauteur et la largeur des icônes par l'ajout de paramètres optionnels "<i><b>hauteur</b></i>" & "<i><b>largeur</b></i>" ayant pour valeur la dimension souhaitée (exemple: hauteur=120 - largeur=90 -> icône de 120px*90px).
Par défaut les icônes font 90px90px.


Vous avez la possibilité d'inclure vos propres icônes dans le widget. Le nommage des icônes est normalisé et doit respecter le format suivant: 
"type_off.png" & "type_on.png". 
Pour ajouter vos icônes, sur la page du Widget, cliquer sur le bouton "Fichiers" tout en haut puis "choisir un fichier" et ajouter vos images une par une.