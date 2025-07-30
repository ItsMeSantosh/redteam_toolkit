# RedTeam Toolkit Installer

A modular Python script to automate the installation of popular red teaming and penetration testing tools on Kali Linux or Debian-based systems.

---

## Features

- Easy terminal UI to select categories of tools to install  
- Modular design for easy maintenance and expansion  
- Installs system packages via `apt`  
- Installs Python packages via `pip`  
- Clones important GitHub repos automatically  
- Virtual environment friendly  

---

## Installation

```bash
git clone https://github.com/ItsMeSantosh/redteam-toolkit.git
cd redteam-toolkit
chmod +x setup.sh
./setup.sh

Usage

Activate the virtual environment: source venv/bin/activate

Run the installer script: python3 redteam_toolkit.py


Explanation:

    Checks for python3 and pip3, installs pip3 if missing.

    Creates a virtual environment venv (if it doesn’t exist).

    Activates the virtual environment.

    Upgrades pip and installs Python dependencies from requirements.txt.

    Prints helpful next steps for the user.

Tool Categories
    Reconnaissance
    Exploitation
    Privilege Escalation
    Post-Exploitation
    Social Engineering
    Web Pentesting
    Active Directory
    Wireless
    OSINT
    Cloud & Containers
