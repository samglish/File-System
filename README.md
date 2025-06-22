# 🗂️ Structure du système de fichiers Linux (FS)
- >  <a href="Readme-english.md">English version</a>
<img src="fig.png" width="70%">

---

## `/` – Racine
Point de départ de toute l’arborescence. Tous les dossiers dépendent de lui.

---
## `/bin` – Commandes de base
Contient les commandes essentielles accessibles à tous les utilisateurs.
- Exemples : `ls`, `chmod`, `sort`, `date`, `cp`, `dd`

---
## `/boot` – Démarrage du système
Contient les fichiers nécessaires au démarrage de Linux.
- Exemples : `vmlinuz` (noyau), `system.map`

---
## `/dev` – Périphériques
Contient les fichiers représentant les périphériques du système.
- Exemples : `hd*` (disques durs), `tty*` (terminaux), `sd*` (USB/disques), `fd*` (disquettes), `cdrom`

---

## `/etc` – Configuration
Contient les fichiers de configuration du système.
- Exemples : `fstab`, `lilo.conf`, `inittab`, `modules.conf`
- Dossier spécial : `X11` pour la configuration graphique

---
## `/home` – Répertoires utilisateurs
Dossiers personnels des utilisateurs normaux.
- `default user`, `other users`
- Fichiers personnels : `.bashrc`, `.bash_profile`, etc.

---
## `/mnt` – Points de montage temporaires
Utilisé pour monter temporairement des systèmes de fichiers externes.
- Exemples : `/mnt/cdrom`, `/mnt/floppy`

---
## `/root` – Home de root
Répertoire personnel du superutilisateur `root`.

---
## `/sbin` – Commandes système
Commandes réservées à l'administration système (souvent utilisables uniquement par `root`).
- Exemples : `shutdown`, `fdisk`, `cfdisk`, `insmod`

---
## `/usr` – Programmes utilisateur
Contient les programmes, bibliothèques et manuels.
- `/usr/local` : installations locales
- `/usr/lib` : bibliothèques
- `/usr/man` : pages de manuels

---
## `/var` – Fichiers variables
Fichiers susceptibles de changer régulièrement.
- `/var/log` : fichiers journaux du système

---

> ### Résumé rapide

| Dossier     | Rôle principal                                |
|-------------|-----------------------------------------------|
| `/`         | Racine du système                             |
| `/bin`      | Commandes de base                             |
| `/boot`     | Fichiers de démarrage                         |
| `/dev`      | Périphériques                                 |
| `/etc`      | Fichiers de configuration                     |
| `/home`     | Répertoires utilisateurs                      |
| `/mnt`      | Points de montage externes temporaires        |
| `/root`     | Dossier personnel de l’administrateur `root`  |
| `/sbin`     | Commandes système (admin)                     |
| `/usr`      | Programmes et bibliothèques utilisateurs      |
| `/var`      | Données variables (logs, etc.)                |