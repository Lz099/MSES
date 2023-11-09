# MSES
This script automates the installation process of Metasploit Framework on both macOS and Ubuntu systems. It checks for dependencies, installs required packages, and sets up the environment for Metasploit.

### Usage
```./mses.sh [-i] [-p <password>] [-g] [-h]```

-i : Install Metasploit Framework.

-p <password> : Set a password for the Metasploit database user. If not provided, a random password will be generated.

-g : Install GNU GCC (Optional, only required if compiling and installing Ruby on macOS).

-h : Display the help message.
