## Q.2.1.1 Sur le serveur, créer un compte pour ton usage personnel.

![Q211](https://github.com/user-attachments/assets/debfc2a9-a04e-47c5-8ec2-08e1c9bb2399)

## Q.2.1.2 Quelles préconisations proposes-tu concernant ce compte ?

Définir un mot de passe fort et unique, mais forcer le renouvellement du mot de passe régulièrement.
Donner les droits sudo pour les tâches administratives et afin d'éviter de travailler constamment en super-utilisateur.
Restreindre les permissions
Activer l'authentification par clé SSH et désactiver l’accès par mot de passe.

## Q.2.2.1 Désactiver complètement l'accès à distance de l'utilisateur root.
![Q222](https://github.com/user-attachments/assets/6217dd61-bfb7-461b-a1de-1a6c5f26a9a4)



## Q.2.2.2 Autoriser l'accès à distance à ton compte personnel uniquement.

![Q222](https://github.com/user-attachments/assets/3e7744b1-ba8c-450e-91c3-b19251e8c50c)


## Q.2.2.3 Mettre en place une authentification par clé valide et désactiver l'authentification par mot de passe
screen Q223 mais non fonctionnel
![Q223](https://github.com/user-attachments/assets/2cefe908-84df-417f-abb2-1da4dc8521a8)
![Q2231](https://github.com/user-attachments/assets/9812b9e0-fa08-44ce-b4d8-682174fbbd6c)
![Q2232](https://github.com/user-attachments/assets/4a007147-1214-46ad-9f87-7949bc13f0ec)

## Q.2.3.1 Quels sont les systèmes de fichiers actuellement montés ?



## Q.2.3.2 Quel type de système de stockage ils utilisent ?

## Q.2.3.3 Ajouter un nouveau disque de 8,00 Gio au serveur et réparer le volume RAID

## Q.2.3.4 Ajouter un nouveau volume logique LVM de 2 Gio qui servira à héberger des sauvegardes. Ce volume doit être monté automatiquement à chaque démarrage dans l'emplacement par défaut : /var/lib/bareos/storage.

## Q.2.3.5 Combien d'espace disponible reste-t-il dans le groupe de volume ?

## Q.2.4.1 Expliquer succinctement les rôles respectifs des 3 composants bareos installés sur la VM.

## Q.2.5.1 Quelles sont actuellement les règles appliquées sur Netfilter ?

## Q.2.5.2 Quels types de communications sont autorisées ?

## Q.2.5.3 Quels types sont interdit ?

## Q.2.5.4 Sur nftables, ajouter les règles nécessaires pour autoriser bareos à communiquer avec les clients bareos potentiellement présents sur l'ensemble des machines du réseau local sur lequel se trouve le serveur.
## Q.2.6.1 Lister les 10 derniers échecs de connexion ayant eu lieu sur le serveur en indiquant pour chacun :

La date et l'heure de la tentative
L'adresse IP de la machine ayant fait la tentative
