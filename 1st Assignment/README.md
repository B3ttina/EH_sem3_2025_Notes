#  Directory Monitoring Script using inotify-tools

This project is a simple Bash-based directory monitoring tool built on Kali Linux using `inotify-tools`. It helps track changes made to files within a specified directory in real-time, such as creation, deletion, and modifications.

---

##  Features

- Real-time monitoring of a target directory  
- Logs file events like CREATE, MODIFY, DELETE  
- Saves logs with timestamps to a log file for review

---

##  Requirements

- Linux environment (tested on Kali Linux 2025.2)
- `inotify-tools` installed  
  You can install it using:  
  ```bash
  sudo apt update  
  sudo apt install inotify-tools  

