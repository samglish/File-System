# 🗂️ Linux File System Structure (FS)

The Linux file system is organized hierarchically, with `/` as the root directory.
<img src="fig.png" width="50%">

---

## `/` – Root
The starting point of the entire file hierarchy. All other folders depend on it.

---

## `/bin` – Basic Commands
Contains essential commands available to all users.
- Examples: `ls`, `chmod`, `sort`, `date`, `cp`, `dd`

---

## `/boot` – System Boot
Contains files needed to boot Linux.
- Examples: `vmlinuz` (kernel), `system.map`

---

## `/dev` – Devices
Contains files representing system devices.
- Examples: `hd*` (hard drives), `tty*` (terminals), `sd*` (USB/disks), `fd*` (floppy), `cdrom`

---

## `/etc` – Configuration
Holds system configuration files.
- Examples: `fstab`, `lilo.conf`, `inittab`, `modules.conf`
- Special folder: `X11` for graphical settings

---

## `/home` – User Directories
Personal folders for normal users.
- `default user`, `other users`
- Personal files: `.bashrc`, `.bash_profile`, etc.

---

## `/mnt` – Temporary Mount Points
Used to temporarily mount external file systems.
- Examples: `/mnt/cdrom`, `/mnt/floppy`

---

## `/root` – Root User's Home
Personal directory of the superuser `root`.

---

## `/sbin` – System Commands
Contains administrative system commands (usually for `root` only).
- Examples: `shutdown`, `fdisk`, `cfdisk`, `insmod`

---

## `/usr` – User Programs
Contains user applications, libraries, and manuals.
- `/usr/local`: locally installed programs
- `/usr/lib`: libraries
- `/usr/man`: manual pages

---

## `/var` – Variable Files
Files that change frequently.
- `/var/log`: system log files

---

## ✅ Quick Summary

| Directory   | Main Purpose                                |
|-------------|---------------------------------------------|
| `/`         | System root                                 |
| `/bin`      | Basic user commands                         |
| `/boot`     | Boot files                                  |
| `/dev`      | Device files                                |
| `/etc`      | Configuration files                         |
| `/home`     | User home directories                       |
| `/mnt`      | Temporary external mount points             |
| `/root`     | Administrator (`root`) home directory       |
| `/sbin`     | System admin commands                       |
| `/usr`      | User applications and libraries             |
| `/var`      | Variable data (logs, etc.)                  |
