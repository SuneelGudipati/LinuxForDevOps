# Essential Linux Commands for DevOps Engineers

In this article, we’ll explore some essential Linux commands frequently used by DevOps engineers in their daily workflows. Mastering these commands can significantly improve efficiency and streamline operations.

---

## System Information Commands
- **`hostname`** – Displays the system’s hostname.
- **`hostid`** – Shows the unique host ID assigned by the OS.
- **`date`** – Shows the current date and time in UTC format.
- **`whoami`** – Displays the current terminal’s logged-in username.
- **`uptime`** – Shows the duration since the system was last started.
- **`uname`** – Provides system information (Unix name).
- **`clear`** – Clears the terminal screen.
- **`history`** – Lists all previously executed commands.
- **`sudo`** – Super User Do (executes commands with superuser privileges).
- **`echo $?`** – Shows the exit status of the last command (0 = success, 1–127 = error).

---

## Directory Navigation Commands
- **`pwd`** – Prints the current directory path.
- **`cd`** – Changes the working directory.
- **`cd ..`** – Navigates to the parent directory.
- **`mkdir`** – Creates a new directory.

---

## File Management Commands
- **`touch`** – Creates an empty file by default.
- **`ls -l`** – Lists files and directories in a detailed format.
- **`vim`** – A powerful text editor in Linux.
  - **Normal mode** – Default mode for navigating and editing text.
  - **Insert mode** – Allows text entry; press "i" to enter, "Esc" to exit.
  - **Command mode** – Used to save or quit Vim; press ":" to enter.
- **`cat`** – Displays file contents.
- **`rm`** – Deletes files or directories.
  - `rm -f <fileName>` – Forces file deletion.
  - `rm -rf <dirName>` – Recursively and forcibly removes a directory and its contents.
- **`cp <source> <destination>`** – Copies files or directories.
- **`mv <fileName> <newFileName>`** – Moves or renames files.

---

## Network Commands
- **`ping <hostName>`** – Checks the reachability of a remote host.
- **`ifconfig`** – Displays available network interfaces.
- **`netstat -lntp`** – Shows open TCP ports.
- **`nslookup`** – Looks up DNS information for a hostname or IP address.

---

## Process Management Commands
- **`ps`** – Shows currently running processes.
- **`ps -ef`** – Displays all system processes.
- **`top`** – Provides a real-time view of running processes.
- **`kill <pid>`** – Terminates a process by its PID.
- **`df -h`** – Shows available disk space by file system.

---

## Package Management (Red Hat)
- **`yum`** – Package manager for RHEL Linux.
  - `yum update -y` – Updates all packages.
  - `yum list --installed` – Lists installed packages.

---

## Service Management
- **`sudo systemctl list-units -t service`** – Lists all active services.
- **`sudo systemctl start <serviceName>`** – Starts a specified service.
- **`sudo systemctl status <serviceName>`** – Checks service status.
- **`sudo systemctl restart <serviceName>`** – Restarts a specified service.

---

## Other Useful Commands
- **`grep`** – Searches for a specific string within a text file (similar to "Ctrl+F").
- **`tail`** – Shows the last N lines of a file (default is 10 lines).
- **`head`** – Shows the first N lines of a file (default is 10 lines).
- **`free`** – Displays system memory usage, including free and used memory.
- **`ssh-keygen`** – Generates a public/private SSH key pair for passwordless remote access.
- **`curl <url>`** – Transfers data to/from a server via HTTP, HTTPS, FTP, and more.
- **`tar`** – Archives multiple files and directories, preserving permissions and structures.
- **`cron` and `crontab`** – Schedules automated tasks.
  - **Example:** `crontab -e` opens a user’s cron table.
  - **Hourly cron job:** `0 * * * * /path/to/script.sh`

---

## File Permission Management
- **`chmod <octalNumber> <fileName>`** – Changes file permissions.
  - **Example:** `chmod 777 test1.txt`

---

This article covers commonly used Linux commands for DevOps professionals. Stay tuned for more updates as new commands and insights are discovered!

---

*Follow for more DevOps content!*
