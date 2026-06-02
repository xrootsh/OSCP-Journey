Linux Users and Groups

What is a User?

A user is an account that can log in and use the system.

Purpose:
Provides access to files, programs, and resources.

Examples:

- root
- kali
- john

Real World Use:
Each person using a Linux system usually has a user account.

---

What is the Root User?

Definition:
The root user is the administrator of the system.

Purpose:
Has full control over the operating system.

Username:
root

Example:

whoami

Output:

root

Note:
Be careful when using the root account because it can modify or delete any file.

---

What is a Group?

Definition:
A group is a collection of users.

Purpose:
Makes permission management easier.

Examples:

- sudo
- adm
- developers

Real World Use:
Multiple users can share access through a group.

---

Viewing Current User

Command:

whoami

Purpose:
Shows the current logged-in user.

Example Output:

kali

---

Viewing User ID Information

Command:

id

Purpose:
Displays user ID (UID), group ID (GID), and group memberships.

Example:

id

Output:

uid=1000(kali) gid=1000(kali) groups=1000(kali),27(sudo)

---

Listing Users

File:

/etc/passwd

Command:

cat /etc/passwd

Purpose:
Shows user accounts on the system.

Example Entry:

root:x:0:0:root:/root:/bin/bash

---

Listing Groups

File:

/etc/group

Command:

cat /etc/group

Purpose:
Shows groups on the system.

---

Creating a User

Command:

useradd testuser

Purpose:
Creates a new user account.

Note:
Requires administrative privileges.

---

Setting a Password

Command:

passwd testuser

Purpose:
Sets or changes a user's password.

---

Creating a Group

Command:

groupadd developers

Purpose:
Creates a new group.

---

Adding a User to a Group

Command:

usermod -aG developers testuser

Purpose:
Adds a user to a group.

---

File Ownership

Command:

ls -l

Example Output:

-rw-r--r-- 1 kali kali file.txt

Meaning:

Owner:
kali

Group:
kali

Purpose:
Determines who controls the file.

---

Changing File Owner

Command:

chown user file.txt

Example:

chown kali file.txt

Purpose:
Changes the owner of a file.

---

Changing File Group

Command:

chgrp developers file.txt

Purpose:
Changes the group ownership of a file.

---

Why Users and Groups Matter?

Users and groups control:

- File access
- Program access
- Administrative privileges
- Security boundaries

Understanding users and groups is important for Linux administration and security.

---

Quick Summary

User
An account that can use the system.

Root
The administrator account.

Group
A collection of users.

whoami
Shows current user.

id
Shows user and group information.

cat /etc/passwd
Lists users.

cat /etc/group
Lists groups.

chown
Changes file owner.

chgrp
Changes file group.

Users and groups are the foundation of Linux permissions and access control.
