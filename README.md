# Basic RHEL9 Cockpit Script

This Bash script provides a basic graphical interface for managing various aspects of Red Hat Enterprise Linux 9 (RHEL9) using Zenity dialogs. It allows users to perform tasks such as user management, firewall configuration, and crontab setup in a user-friendly manner.

## Features

- **User Management:** Allows users to create or delete users with specified attributes.
- **Firewall Configuration:** Facilitates the configuration of firewall settings including service installation, service name, and port number.
- **Crontab Setup:** Enables users to set up scheduled tasks using cron with minute, hour, day of month, month, day of week, and command specifications.

## Usage

### 1. Clone or Download the Script
```bash
$ git clone https://github.com/
```
### 2. Install Zenity

Make sure you have Zenity installed on your RHEL9 system. If Zenity is not already installed, you can install it using the following command:

```bash
$ sudo yum install zenity
```
### 3. Make the Script Executable
Navigate to the directory where you downloaded the script and make it executable using the following command:
