## Overview
The game provides us a username and password to login into a remote server via SSH. The objective of this level is to find the password for the next level, which is hidden inside a file called "Readme" located in the home directory.
## Solution
To connect to the server host, open the terminal and excute the following command:
```bash
ssh -p 2220 bandit0@bandit.labs.overthewire.org

 ### *Explaination*
 ssh:The Secure Shell protocol used to securely connect to remote servers.
 -p 2220: set 2220 as the destination port for the connection.
 bandit0@bandit.labs.overthewire.org: The login credentials combining the username and the target remote hostname.

 After connecting successfully and entering the password, you will land in /home/bandit0.
 *If you are unsure of your current location? 
 Run the command: ```bash pwd
 Use this command to list all file in your current directory.
 ```bash 
 ls -al 
Excute following command to read contents of the readme file
 ``` bash 
 cat readme
 Game over!!!
