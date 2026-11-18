# Spécification
/speckit.specify

Créer une application de vérification de présence des étudiants.

Chaque étudiant possède un identifiant unique sous forme de QR code.
Avant d’entrer en classe, l’étudiant présente son QR code devant le scanner.
Après un scan réussi, rechercher l’étudiant correspondant dans la base de données et afficher son identité ainsi que son statut « Présent ».

L’application doit empêcher qu’un même étudiant soit enregistré plusieurs fois pour la même séance.

Prévoir une page permettant de consulter la liste des étudiants présents et absents, avec la date et l’heure du scan.

# Plan
/speckit.plan

Créer une application web simple et responsive.
Utiliser une interface avec quelques boutons et écrans clairement identifiés.

Écrans principaux :
- Connexion / accueil
- Scan de l’identifiant
- Liste des étudiants présents
- Liste des étudiants absents

Prévoir une base de données locale pour stocker les étudiants et les présences.
Utiliser un lecteur de QR code avec la caméra de l’appareil.
Prévoir un bouton « Scanner », un bouton « Présences » et un bouton « Absences ».

L’application doit fonctionner directement après installation et être utilisable par un enseignant sans configuration complexe.