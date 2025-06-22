# 🗂️ Structure du système de fichiers Linux (FS)

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
