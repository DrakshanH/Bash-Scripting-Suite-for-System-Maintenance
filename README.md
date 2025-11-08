# Bash-Scripting-Suite-for-System-Maintenance

# 🧰 System Maintenance Suite (Assignment 5 - LinuxOS & LSP)

## 📄 Overview
This project is a **Bash Scripting Suite** designed to automate key system maintenance tasks on Linux systems.  
It is part of **Assignment 5 (LinuxOS and LSP)** from the Capstone Project series.

The suite includes individual scripts for:
- Performing backups
- Updating and cleaning the system
- Monitoring system logs
- Running all tools through a single menu-driven interface

---

## 📂 Project Structure
system_maintenance_suite/
│
├── backup.sh # Automates document backup 
├── update_cleanup.sh # Updates system and removes unnecessary packages 
├── log_monitor.sh # Scans system logs for errors or warnings 
├── maintenance_suite.sh # Menu-driven interface to run all scripts 
└── README.md # Project documentation 


---

## ⚙️ Requirements
- Linux OS (Ubuntu/Debian preferred)
- `bash` shell
- `tar`, `grep`, and `apt` utilities
- `sudo` privileges for update and cleanup operations

---

## 🚀 Setup Instructions

1. **Extract the ZIP file**
   ```bash
   unzip system_maintenance_suite.zip
   cd system_maintenance_suite

2. **Make scripts executable**
   ```bash
    chmod +x *.sh

4. **Run the main maintenance suite** 
   ```bash
   ./maintenance_suite.sh

## Day-wise Tasks:
Day 1: Write a script for automated system backups. //backup.sh

Day 2: Create a script to perform system updates and clean up. //update_cleanup.sh

Day 3: Develop a log monitoring script to alert on certain conditions. //log_monitor.sh

Day 4: Combine scripts into a maintenance suite with a menu to execute them. //maintenance_suite.sh

Day 5: Test scripts and add error handling and logging functionalities.
