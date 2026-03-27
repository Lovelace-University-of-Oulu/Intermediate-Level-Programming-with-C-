#### Setting Up Your Work Environment
##### Linux Subsystem Installation
- Unless you already have Linux installed on your machine, we recommend you install Windows Subsystem for Linux (WSL). This will allow you to run a Linux-based operating system natively within Windows, and to use Linux tools and utilities directly on your Windows machine, without needing to set up a virtual machine or dual boot the two operating systems.
##### C++ Tools
- You're almost ready to start using the Linux Subsystem. The only thing left is to set up C++:
```cmd
sudo apt update
sudo apt install build-essential
```
This will update your system's package list and install the necessary tools for C++ compilation and execution.
##### Using WLS
If you have experience working with Linux environments, you may skip the following instructions. However, if you are new to Linux, the following guidelines will be helpful in getting you started.
To open the Windows Explorer of your Linux Subsystem home directory, enter the following command in the terminal:
```cmd
explorer.exe .
```
This will launch a window displaying the contents of your home/username directory, which you can use to create directories and files for your assignments.
