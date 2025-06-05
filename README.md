# First Linux VM — Shell Basics on WSL

## 📄 Description
Setup of a Linux virtual machine using Windows Subsystem for Linux (WSL) with the Ubuntu distribution. This project involves accessing the Linux terminal and practicing basic shell commands to develop essential skills in system navigation, file manipulation, directory management, and network information verification.

## 🚀 Activities Performed
- Installation and configuration of Ubuntu using WSL.
- Accessing the Linux terminal through WSL.
- Executing shell commands for:
  - Navigating directories.
  - Creating, editing, and deleting files and folders.
  - Checking network information.
  - Creating aliases to optimize terminal commands.

## 🔧 Commands Used
- `pwd` → Displays the current directory.
- `ls` → Lists files and directories.
- `alias ls='ls -ltraphi'` → Creates a custom alias for `ls` with parameters.
- `ip addr` → Shows network information.
- `whoami` → Displays the current logged-in user.
- `mkdir lab1` → Creates a directory called `lab1`.
- `cd lab1` → Enters the `lab1` directory.
- `cd ..` → Goes back to the previous directory.
- `touch text.txt` → Creates a file called `text.txt`.
- `echo "texto" > text.txt` → Adds text to the file `text.txt`.
- `cat text.txt` → Displays the contents of the file.
- `rm text.txt` → Deletes the file.
- `rmdir lab1` → Removes the `lab1` directory.
- `history` → Shows the command history.
- `clear` → Clears the terminal screen.
- `exit` → Ends the terminal session.

## 🐞 Challenge Faced
- The `ifconfig` command was not available by default on Ubuntu installed through WSL. The `ip addr` command was used as an alternative to check network configurations.

## 🧠 Lessons Learned
- Navigating the Linux terminal using WSL.
- Creating, managing, and deleting files and directories.
- Checking network configurations.
- Using aliases to personalize and optimize terminal commands.
- Basic administration and interaction with a Linux environment integrated into Windows through WSL.

## 📸 Screenshots and Evidence
All screenshots are included in the [documentation.pdf](https://github.com/jmur4saki/first-linux-vm/blob/main/documentation.pdf)
