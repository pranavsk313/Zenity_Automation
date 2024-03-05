# Basic RHEL9 Cockpit Script

This Bash script provides a basic graphical interface for managing various aspects of Red Hat Enterprise Linux 9 (RHEL9) using Zenity dialogs. It allows users to perform tasks such as user management, firewall configuration, and crontab setup in a user-friendly manner.

## 1. Things you will Learn from this project 🤯
1. Bash Scripting:
   - Learn how to create interactive Bash scripts.
   - Utilize Zenity to provide graphical user interfaces (GUIs) for system configuration management.
2. User Management:
   - Understand how to create and delete users from the command line.
   - Utilize Zenity dialogs for user management tasks.
3. Firewall Configuration:
   - Learn interactive firewall configuration.
   - Utilize Zenity dialogs for configuring firewall settings, including package installation and port opening.
4. Crontab Setup:
   - Explore setting up scheduled tasks using cron.
   - Utilize Zenity dialogs to interactively configure crontab entries.

##  2. **Prerequisites** ! 
Before using this project, ensure you have the following:

1. **Red Hat Enterprise Linux 9 (RHEL9) or Compatible Distribution**
   - This project is designed for RHEL9 or similar Linux distributions.

2. **Zenity**
   - Ensure Zenity is installed on your system. If Zenity is not already installed, You can install Zenity using the following command:
     ```bash
     sudo yum install zenity
     ```

3. **Basic Linux Command Line Skills**
   - Familiarize yourself with basic Linux command line operations as this project involves interacting with the terminal.

4. **Root or Sudo Access**
   - You may need root or sudo access to execute certain commands depending on the tasks performed by the script.

# 3. Steps

### 1. Clone or Download the Script
```bash
 git clone https://github.com/pranavsk313/Zenity_Automation/
```
### 2. Make the Script Executable
Navigate to the directory where you downloaded the script and make it executable using the following command:

```bash
chmod 755 Script.sh
```

### 3. Run the Script
```
./Script.sh
```
### 4. Options
- **User Management:** Allows for creating and deleting users.

- **Firewall Configuration:** Configures the firewall by installing packages, adding services, and opening ports.

- **Crontab Setup:** Sets up cron jobs by specifying minute, hour, day of month, month, day of week, and the command to run.

![1](https://github.com/pranavsk313/Zenity_Automation/assets/122976840/7757caca-450f-4aa5-9105-7d28b0748305)

### Once you've selected the **User Management** option from the main menu, you'll be presented with the following choices:

   1. Creating a User:
    To create a new user, follow these steps:
   - Choose Create user from the User Management menu.
   - Enter the required user details such as username, UID, GID, GECOS, home directory, and shell in the provided form.
   - Click OK to create the user.











