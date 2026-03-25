Partie 1 – Linux et Terminal (8 questions)
1. Navigation et structure Linux
Créez l’arborescence suivante depuis le terminal uniquement :
projet-linux/
├── scripts/
├── logs/
├── sauvegardes/
└── utilisateurs/
Ensuite :
• créez 3 fichiers dans logs/
• créez 2 fichiers dans scripts/
• affichez toute l’arborescence avec une commande Linux
Expliquez brièvement chaque commande utilisée.

Reponses 1.1

> mkdir projet-linux
> cd projet-linux
> mkdir scripts
> mkdir logs
> mkdir sauvegardes
> mkdir utilisateurs

> cd ..
> cd logs
> touch logs1
> touch logs2
> touch logs3

> cd ..
> cd scripts
> touch scripts1
> touch scripts2
> touch scripts3 

> cd ..
> ls 

 **mkdir** : pour creer un dossier, suivis du nom du dossier.
 **cd**   : Pour acceder à un dossier
 **cd ..** : pour faire un retour au dossier precedent 
 **touch** : cette commande cree un fichier, suivis de nom du fichier
 **ls** :  cette commande affiche tous les éléments (dossiers, fichiers) d'un repertoire


 2. Gestion des permissions
Créez un fichier nommé deploy.sh puis :
• donnez uniquement au propriétaire le droit de lecture, écriture et exécution
• donnez au groupe le droit de lecture et exécution
• retirez tous les droits aux autres utilisateurs
Expliquez la signification du mode de permission utilisé.