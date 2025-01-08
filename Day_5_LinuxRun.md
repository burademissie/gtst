## some advanced user commands
- **To change password of user**
    - sudo passwd <username>
- To change user id 
	- sudo usermod -u <new_id> <username>
- To delete user
	-Sudo userdel -r <username>
- To change users on terminal
	- su - username
## sudo mkhomedir_helper <username>
- used to create a home directory for a specified user in linux , typically when the user is being added to the system without an existing home directory.
## sudo usermod <username> -s /bin/bash



## create a New Group (if not created):
- sudo groupadd <groupname>
## Add User to the Group
- sudo usermod -aG <groupname> <username>
## Verify the User's Group Membership:
- groups <username>
## Remove User from the Group:
- sudo gpasswd -d <username> <groupname>
- verify the User's Group Membership:
	  - groups <username>


# Sudoers file

the sudoers file is a file Linux and Unix administrators use to allocate system rights to the system users.
the user you created doesn't have power to use sudo as the original one.
This is Becuase it is not added in the sudoers file
to access this file     **sudo visudo**


# Linux File Permission

every file on linux have their own 
	- Owner
	- Permissions
There is 5 main parts on the listing 
	1 Permission
	2 Owners
	3 Date
	4 Size
	5 filename

## To change the owner of the file -->> chown user:group filename

## There are 3 types of permissions
	-Read(r)  -- . 4
	-Write(w) -- 2
	-Execute(x) --1
The folders and files are differ with the 'd' and '-' on the begining of the permission


There are Still the permission have three parts.
	-User - group - other
command to change permission of file
	- chmod <option> filename
	- example :- sudo chmod u+x filename <- this will add x to the user group but if we want to add to all the command would be sudo chmod +x filename
	
# special file permissions
	- There are another 3 special permissions
			- SUID bits(s)=set user ID - add 4 infront of our numeric value --> 4000
			- SGID bits(S )=set group ID bit - the same but this change to 2 --> 2777
			- Sticky bits(t) - change to 1 --> 1602
# Package Installation on Linux

On linux to install software u use package managers like apt , pacman , pkg 

## Advanced package tool /apt/
apt is a free-software user interface that work with an online server to handle the installation and removal of software on Debian and Debian based Linux distributions. Used for online and offline purpose.

### Syntax
- sudo apt update
- sudo apt search <softwarename>
- sudo apt install <softwarename>
- sudo apt remove <softwarename>
- sudo apt upgrade 
- sudo apt purge <softwarename>

## Package Dependencies 
A software can be built based on another program called 'modules' . so a program to work properly the dependencies have to be installed successfully. Those package managers install the software + dependencies.

### Dpkg /Debian Package manager/
Dpkg is an offline package managing program. 
pacakges on debian have an extension '.deb'
 ### syntax
	 - sudo dpkg -i <packagename>
	 - sudo dpkg -r <packagename>
	 - sudo dpkg -P  <packagename>
