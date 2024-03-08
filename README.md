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
1. **User Management:** Allows for creating and deleting users.

2. **Firewall Configuration:** Configures the firewall by installing packages, adding services, and opening ports.

3. **Crontab Setup:** Sets up cron jobs by specifying minute, hour, day of month, month, day of week, and the command to run.

![1](https://github.com/pranavsk313/Zenity_Automation/assets/122976840/7757caca-450f-4aa5-9105-7d28b0748305)

## Option 1: **User Management** 
   ![2](https://github.com/pranavsk313/Zenity_Automation/assets/122976840/60ac8a90-a7bd-4662-97b7-8f3fb94a9dc0)

### 1. **Creating a User:**
   To create a new user, follow these steps:
   - Choose Create user from the User Management menu.
   - Enter the required user details such as username, UID, GID, GECOS, home directory, and shell in the provided form.
   - Click OK to create the user.

![3](https://github.com/pranavsk313/Zenity_Automation/assets/122976840/aafe8212-6603-41e8-8867-6daf88a65281)

### - Output of user creation:
![4](https://github.com/pranavsk313/Zenity_Automation/assets/122976840/510ce810-3489-4e40-b158-8876752d5962)


### 2. **Deleting a User**
   If you need to remove an existing user, here's what you should do:
   - Select Delete user from the User Management menu.
   - Enter the username of the user you want to delete.
   - Click OK to confirm and delete the user.

![9](https://github.com/pranavsk313/Zenity_Automation/assets/122976840/91959af2-6397-4704-b289-cd5d3c2d4df4)


##  Option 2: **Firewall Configuration**
   - Select Firewall Configuration from the main menu.
   - Enter the package to install, service name, and port number with /tcp.
   - Click OK to configure the firewall.

![6](https://github.com/pranavsk313/Zenity_Automation/assets/122976840/654e82c6-9c4c-4846-a9ae-f5a8c7fa386d)

### Output of the Firewall Configuration:

![7](https://github.com/pranavsk313/Zenity_Automation/assets/122976840/341f4896-c2d3-4571-96e6-ae3ea6e671d2)

## Option 3: **Crontab Setup**
- Select Crontab Setup from the main menu.
- Enter the minute, hour, day of month, month, day of week, and the command for the cron job.
- Click OK to set up the cron job.


![8](https://github.com/pranavsk313/Zenity_Automation/assets/122976840/5ef52dc6-b832-4918-b12f-fe64dacb92bb)








