Linux File System

What is a File System?

A file system is the way Linux organizes files and directories.

Everything starts from the root directory:

/

---

/

Definition:
The root directory.

Purpose:
The top-level directory of the Linux file system.

Example:

/
├── bin
├── etc
├── home
├── root
├── tmp
└── var

---

/home

Definition:
Stores user home directories.

Purpose:
Contains personal files and folders for normal users.

Example:

/home/john
/home/alice

Real World Use:
Documents, downloads, and personal files.

---

/root

Definition:
Home directory of the root user.

Purpose:
Stores files for the administrator account.

Example:

/root

Real World Use:
Administrative scripts and configuration files.

---

/etc

Definition:
Stores system configuration files.

Purpose:
Contains settings used by the operating system and services.

Examples:

/etc/passwd
/etc/hosts
/etc/ssh/

Real World Use:
System administration and configuration.

---

/var

Definition:
Stores variable data.

Purpose:
Contains logs, caches, and changing application data.

Examples:

/var/log
/var/cache

Real World Use:
Checking logs and troubleshooting problems.

---

/tmp

Definition:
Temporary storage location.

Purpose:
Stores temporary files.

Example:

/tmp

Real World Use:
Applications store temporary data here.

Note:
Files may be deleted automatically.

---

/bin

Definition:
Contains essential user commands.

Purpose:
Provides basic tools required by the system.

Examples:

/bin/ls
/bin/cp
/bin/mv

Real World Use:
Daily command-line operations.

---

/sbin

Definition:
Contains system administration commands.

Purpose:
Used for managing and maintaining the system.

Examples:

/sbin/reboot
/sbin/shutdown

Real World Use:
Administrative tasks.

---

/usr

Definition:
Stores user programs and utilities.

Purpose:
Contains software and documentation.

Examples:

/usr/bin
/usr/share

Real World Use:
Most installed programs are stored here.

---

/opt

Definition:
Optional software installation directory.

Purpose:
Stores third-party applications.

Example:

/opt/application

Real World Use:
Custom software installations.

---

Quick Summary

/
Root of the file system.

home
User files.

root
Administrator files.

etc
Configuration files.

var
Logs and variable data.

tmp
Temporary files.

bin
Basic commands.

sbin
System administration commands.

usr
Programs and utilities.

opt
Optional applications.
