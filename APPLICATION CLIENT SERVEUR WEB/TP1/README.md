TP1 – Modèle client-serveur

Présentation

Ce travail pratique porte sur le modèle client-serveur et son fonctionnement dans un environnement réseau virtualisé.
Il consiste à mettre en place un serveur et plusieurs clients afin d’étudier les échanges de données, les connexions réseau et les services accessibles à distance.

Objectifs

* Comprendre le fonctionnement du modèle client-serveur.
* Configurer un réseau privé entre plusieurs machines.
* Installer et configurer le serveur MariaDB.
* Permettre aux clients de se connecter à distance à la base de données.
* Mettre en place un serveur Web Apache.
* Observer les connexions simultanées de plusieurs clients.
* Étudier les limites et les problèmes de sécurité du modèle client-serveur.

Environnement de travail

* Windows 11
* VMware Workstation
* Ubuntu 24
* MariaDB
* HeidiSQL
* tcpdump
* Wireshark

Architecture réseau

Le TP utilise un réseau Host-only avec l’adressage suivant :

* Windows : 192.168.56.1
* VM1 Ubuntu (serveur) : 192.168.56.11
* VM2 Ubuntu (client) : 192.168.56.12

Le serveur VM1 héberge les services MariaDB.


Contenu du TP

Le TP est organisé autour des manipulations suivantes :
1. Mise en place du réseau et du serveur MariaDB.
2. Configuration de l’accès réseau au serveur.
3. Connexion de plusieurs clients et gestion des droits.
4. Étude des limites du modèle client-serveur et observation du trafic réseau.


Fichiers

Ce dossier contient le compte rendu du TP ainsi que les documents et captures d’écran associés aux manipulations. Voici les fichiers:
* scolarite.sql : script SQL de la base de données scolarité.
* utilisateurs_tp1.sql : script SQL de gestion des utilisateurs du TP1.
* index.html : page Web du serveur Apache.


Conclusion

Ce TP permet de comprendre les échanges entre un client et un serveur, la centralisation des services et des données, ainsi que les avantages et les limites de cette architecture.
