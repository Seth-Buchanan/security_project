# security_project
Install script and documentation for Linux Security and Networking security Audit project

## Installation
When installing Ubuntu server, make sure to enable drive encryption in the installer. This allows us to add a password that will be used as a key to decrypt the drive on startup and keep the installation from being mounted along with other vunerabilites.

### Usage
Since the install script runs many programs that require root privileges it must be ran as root. 
```bash
$ sudo ./install
```
