# Basic RHEL9 Cockpit Script

This Bash script provides a basic graphical interface for managing various aspects of Red Hat Enterprise Linux 9 (RHEL9) using Zenity dialogs. It allows users to perform tasks such as user management, firewall configuration, and crontab setup in a user-friendly manner.

## Things you will Learn from this project 🤯
1. Bash Scripting:
   1. Learn how to create interactive Bash scripts.
   2. Utilize Zenity to provide graphical user interfaces (GUIs) for system configuration management.
2. User Management:
   1. Understand how to create and delete users from the command line.
   2. Utilize Zenity dialogs for user management tasks.
3. Firewall Configuration:
   1. Learn interactive firewall configuration.
   2. Utilize Zenity dialogs for configuring firewall settings, including package installation and port opening.
4. Crontab Setup:
   1. Explore setting up scheduled tasks using cron.
   2. Utilize Zenity dialogs to interactively configure crontab entries.

##  **Prerequisites** ! 
Before using this project, ensure you have the following:

1. **Red Hat Enterprise Linux 9 (RHEL9) or Compatible Distribution**
   - This project is designed for RHEL9 or similar Linux distributions.

2. **Zenity**
   - Ensure Zenity is installed on your system. You can install Zenity using the following command:
     ```bash
     sudo yum install zenity
     ```

3. **Basic Linux Command Line Skills**
   - Familiarize yourself with basic Linux command line operations as this project involves interacting with the terminal.

4. **Root or Sudo Access**
   - You may need root or sudo access to execute certain commands depending on the tasks performed by the script.

## Features

- **User Management:** Allows users to create or delete users with specified attributes.
- **Firewall Configuration:** Facilitates the configuration of firewall settings including service installation, service name, and port number.
- **Crontab Setup:** Enables users to set up scheduled tasks using cron with minute, hour, day of month, month, day of week, and command specifications.

## Usage

### 1. Clone or Download the Script
```bash
 git clone https://github.com/
```
### 2. Install Zenity

Make sure you have Zenity installed on your RHEL9 system. If Zenity is not already installed, you can install it using the following command:

```bash
 sudo yum install zenity
```
### 3. Make the Script Executable
Navigate to the directory where you downloaded the script and make it executable using the following command:

```bash
chmod 755 script.sh
```

### 4. Run the Script
```
./script.sh
```












