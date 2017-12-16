# Gladys-Device-HTTP
Gladys hooks for sending http request.

## Prérequis

Installer le module Gladys Device HTTP


## Pour Installer le module Gladys Device HTTP

Aller dans l'onglet "Avancé" de la vue module de Gladys

Renseigner tout les champ comme ci dessous (L'URL a renseigner est celui-ci => https://github.com/LeptitGeek/Gladys-Device-HTTP.git) Le slug représente le nom dans lequel le module sera installé donc mettez ce que bon vous semble ici ça sera **device-http** mais noter le car nous en n'auront besoin plus tard.

Une fois le module installé redémarrer Gladys

## Utilisation du module

Créé un device. Donnez lui un petit nom et dans le champ identifier renseignez l'adresse complete de votre device avec un paramètre si vous le souhaitez, ici ça sera http://192.168.1.55:4200?r= (l'adresse doit comporter l'IP du device ainsi que son Port afin que Gladys puisse le contacter sur le reseau, si vous souhaitez integrer un paramètre il doit être précédé d'un point d'intérogation) 
Pour cet exemple j'ia intégré un paramètres **r** qui correspond à **relais** mais vous pouvez mettre ce que vous voulez.

Ensuite son service et son protocole sont très important ! Il faut absolument que le service et le protocole soit identique au slug renseigné au moment de l'installation du module Gladys device HTTP ! Donc dans cet exemple c'est **device-http**.

Cliquez sur "Edit" et créé un devicetype.

Vous pouvez maintenant envoyer une requête http depuis Gladys depuis l'onglet device 😁
