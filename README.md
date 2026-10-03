# Synscan
A basic SYN scanner built in python.

# Installation
We need to install Scapy before we install Synscan
- For Arch
```bash
sudo pacman -S python-scapy 
```

- For Debian
```bash
sudo apt install python-scapy
```

Then clone this repository using 
```bash
git clone https://github.com/slotthyyy/synscan.git
```
Change to this directory 

```bash
cd synscan
```
Make the install script executable

```bash
chmod +x install.sh
```
Install using the script

```bash
./install.sh
```
Run the program as root (This command shows the help menu)
```bash
sudo synscan -h
```
# Uninstallation

Change directory to Synscan

```bash
cd synscan
```
Make the uninstall script executable 

```bash
chmod +x uninstall.sh
```
Run the uninstall script
```bash
./uninstall.sh
```
