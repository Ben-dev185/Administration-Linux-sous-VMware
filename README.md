# Administration Linux sous VMware

## Présentation

Ce projet consiste à concevoir et administrer une infrastructure Linux virtualisée sous VMware Workstation. L'objectif était de reproduire un environnement d'entreprise réaliste composé de serveurs Ubuntu 22.04 et Debian 12, administrés à distance et sécurisés selon les bonnes pratiques professionnelles.

## Objectifs

* Déployer plusieurs serveurs Linux
* Configurer le réseau et les accès distants
* Sécuriser les connexions SSH
* Mettre en place un pare-feu UFW
* Automatiser les tâches d'administration avec Bash
* Gérer les utilisateurs et les permissions

## Environnement

* VMware Workstation
* Ubuntu Server 22.04
* Debian 12
* OpenSSH
* UFW Firewall
* Bash
* Systemd

## Réalisations

### Administration système

* Installation et configuration de serveurs Linux
* Configuration réseau avec adresses IP statiques
* Gestion des utilisateurs et groupes
* Gestion des permissions (chmod, chown, ACL)
* Configuration des privilèges sudo

### Sécurisation

* Authentification SSH par clé publique
* Désactivation de l'accès root par mot de passe
* Changement du port SSH
* Configuration du pare-feu UFW
* Analyse des journaux système

### Automatisation

* Scripts Bash de sauvegarde
* Planification des tâches avec Cron
* Génération automatique de logs
* Maintenance automatisée

## Captures d'écran

### Déploiement Apache2

![Apache](https://github.com/Ben-dev185/Administration-Linux-sous-VMware/blob/1ce64962e8a2f13ba8534e5c285342559a60853e/De%CC%81ploiement%20Apache.png)

### Validation du serveur Web

![Apache Web](captures/apache-web.png)

### Configuration SSH

![SSH](https://github.com/Ben-dev185/Administration-Linux-sous-VMware/blob/7b678cd012181314c96cd1c828807466a931cf64/Configuration%20SSH.png)

### Pare-feu et sauvegardes

![UFW](captures/ufw-backup.png)

## Compétences démontrées

* Administration Linux
* Sécurité système
* Bash Scripting
* Réseaux TCP/IP
* Gestion des services Systemd
* Supervision et analyse des logs

## Résultat

Infrastructure Linux entièrement opérationnelle, sécurisée et automatisée, proche d'un environnement de production réel.
# Administration-Linux-sous-VMware
