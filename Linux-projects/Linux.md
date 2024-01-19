# File Manipulation
## Sudo command
* Short for superuser do.
* The sudo command enables the user to perform tasks which require administrative or root permissions.
* The user is promted for their account password following the command.
* Once access is granted, the user is allowed 15 minutes accesss after whcich they are again prompted for their password.
* Syntax: sudo (command) e.g sudo (apt update) i.e *sudo apt update*
![new photo](Images/sudo-command.png)
  
  * Options can be used with sudo to do a variety of things.
    e.g *sudo -l* allows the user to know which permissions they are allowed access to
  * the image below shows that I can do everything as sudo.


![new photo](Images/sudo-l.png)


*sudo -s* takes the user straight from the home directory into the root directory in which they can perform all tasks which require sudo privileges.

![new image](Images/superuser.png)


Sometimes we can forget to type in 'sudo' in a sudo command. Typing sudo followed by double exclamation marks executes the previous command using sudo privileges
Syntax: *sudo !!*

![new image](Images/sudo.png)



  
