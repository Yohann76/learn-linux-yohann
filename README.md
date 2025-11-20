# Learn Linux Yohann

run wiki with docker:

```
docker compose up
```

Available in http://localhost:8000

## Available with Github Page (soon)

```
https://xxxxxxx.github.io/xxxxxxx/
```

## Contribute

1. Clone project
2. Create your branch
3. Add/commit your change
4. push and create merge request

## Ressources:

- [Roadmap Linux](https://roadmap.sh/linux)

## Program

```
Module 1 : Introduction à Linux

```
Qu’est-ce que Linux ? (histoire, distributions)
Pourquoi utiliser Linux (serveurs, dev, administration)
Les bases du système Linux : noyau, shell, architecture
Installation : VM, Dual Boot, WSL, etc.
```

Module 2 : Navigation et manipulation de fichiers

```
Structure du système de fichiers Linux (hierarchie : /, /etc, /home, …) 
Commandes de base : ls, cd, pwd, cp, mv, rm, mkdir
Liens symboliques / hard links
Montage / démontage de disques (mount, umount)
Analyser l’espace disque (du, df)
```

Module 3 : Permissions et gestion des utilisateurs

```
Propriétaires, groupes, UID / GID

Permissions : chmod, chown, octal vs symbolique
umask
ACL (Access Control Lists)
Utilisateurs et groupes : création, suppression, modification (useradd, usermod, groupadd…)
sudo et escalade de privilèges
```

Module 4 : Processus, jobs et services

```
Processus : que sont-ils, comment les lister (ps, top, htop)
Envoyer des signaux (kill, pkill, etc.)
Priorités de processus (nice, renice)
Processus en arrière-plan vs premier plan
cron (planification), at éventuellement
Services : systemd, systemctl (démarrer, arrêter, status)
Logs système : journalctl, /var/log
```

Module 5 : Gestion du système de fichiers / Disques

```
Types de systèmes de fichiers (ext4, xfs, etc.)
Partitionnement (fdisk, parted)
LVM (Logical Volume Manager)
Swap
Montage automatique, /etc/fstab
Inodes
```

Module 6 : Gestion des paquets

```
Manager de paquets selon la distribution : apt, yum/dnf, pacman, etc.
Repos, installation, mise à jour, suppression de paquets
Construction de paquets (compile à partir des sources)
```

Module 7 : Scripting Shell

```
Introduction au shell (bash, zsh, etc.)
Variables, conditions, boucles
Fonctions
Redirections, pipes
Gestion des erreurs
Automatisation de tâches (sauvegarde, scripts de maintenance, etc.)
```

Module 8 : Réseau sous Linux

```
Concepts réseau de base : IP, DNS, route, sous-réseaux
Commandes réseau : ping, netstat, ss, ifconfig / ip
SSH : configuration, clés, tunnels
Pare-feu : netfilter / iptables / nftables
Transfert de fichiers : scp, rsync
```

Module 9 : Sécurité Linux

```
Gestion des privilèges root
Authentification (mot de passe, clés SSH)
Sécurisation des services
SELinux / AppArmor (selon la profondeur du cours)
Chiffrement des fichiers et disques
```

Module 10 : Administration avancée

```
Journaux, monitoring
Sauvegarde et restauration (rsync, tar, cron)
Virtualisation (VM, conteneurs) — optionnel selon ton audience
Conteneurisation et Linux (préparer à Docker, Kubernetes)
Gestion des limites système (ulimits, cgroups)
```

Module 11 : Projets pratiques

```
Créer un script de backup automatique
Déployer un petit serveur web (Apache ou Nginx) sur Linux
Automatiser la gestion utilisateurs / groupes
Mettre en place une surveillance des processus + alerte simple
Script d’archivage de logs
```

Module 12 : Aller plus loin (“Next”)

```
Introduction au kernel Linux (architecture, compilation)
Contribution open-source sur des projets Linux
Linux dans le DevOps / cloud (lié à Docker, Kubernetes)
Optimisation des performances
Sécurité avancée (audit, pentest, sandboxing)
```

## Timing Plan

Module 1 : 1 séance
Module 2 : 2 séances
Module 3 : 1–2 séances
Module 4 : 2 séances
Module 5 : 1 séance
Module 6 : 1 séance
Module 7 : 2 séances
Module 8 : 2 séances
Module 9 : 1 séance
Module 10 : 1–2 séances
Module 11 : 2 séances (projets)
Module 12 : 1 séance ou plus selon la profondeur