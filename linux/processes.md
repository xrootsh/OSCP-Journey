Linux Processes

What is a Process?

A process is a running program.

Examples:

- Firefox
- SSH
- Python script
- Apache web server

Purpose:
Processes allow programs to run and perform tasks.

---

Viewing Running Processes

Command:

ps

Purpose:
Shows processes running in the current terminal session.

---

Viewing All Processes

Command:

ps aux

Purpose:
Displays all running processes on the system.

Example:

ps aux

Real World Use:
Used to inspect running services and applications.

---

Searching for a Process

Command:

ps aux | grep ssh

Purpose:
Searches for a specific process.

Example Output:

root      1234  sshd

Real World Use:
Check if a service is running.

---

Real-Time Process Monitoring

Command:

top

Purpose:
Shows running processes in real time.

Displays:

- CPU usage
- Memory usage
- Running processes

Exit:

q

---

htop

Definition:
An improved version of top.

Command:

htop

Purpose:
Provides an easier process monitoring interface.

Note:
May need installation.

---

Process ID (PID)

Definition:
Every process has a unique Process ID.

Example:

PID 1234

Purpose:
Used to identify and manage processes.

---

Killing a Process

Command:

kill PID

Example:

kill 1234

Purpose:
Stops a running process.

---

Force Kill a Process

Command:

kill -9 PID

Example:

kill -9 1234

Purpose:
Forcefully terminates a process.

Warning:
Use carefully.

---

Kill by Process Name

Command:

killall firefox

Purpose:
Stops all processes with a specific name.

Example:

killall firefox

---

Background Processes

Definition:
Processes running without occupying the terminal.

Start in background:

command &

Example:

python script.py &

Purpose:
Allows the terminal to remain usable.

---

Jobs

Command:

jobs

Purpose:
Shows background jobs in the current shell.

Example:

jobs

---

Bring Process to Foreground

Command:

fg

Purpose:
Moves a background job to the foreground.

---

Send Process to Background

Command:

bg

Purpose:
Continues a stopped process in the background.

---

View Parent and Child Processes

Command:

pstree

Purpose:
Displays processes in a tree structure.

Example:

pstree

---

Why Processes Matter?

Processes help you:

- Monitor system activity
- Troubleshoot problems
- Manage running services
- Understand resource usage

Process management is an important Linux skill.

---

Quick Summary

Process
A running program.

ps
View processes.

ps aux
View all processes.

grep
Search for a process.

top
Real-time monitoring.

htop
Enhanced process viewer.

kill
Stop a process.

kill -9
Force stop a process.

killall
Stop processes by name.

jobs
View background jobs.

fg
Move job to foreground.

bg
Move job to background.

pstree
View process hierarchy.
