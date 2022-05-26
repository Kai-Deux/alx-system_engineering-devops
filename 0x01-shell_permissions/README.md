<<<<<<< HEAD
8 Write a script that sets the mode of the file hello to this: 
   * -rwxr-x-wx 1 julien julien 23 Sep 20 14:25 hello
* 9 Write a script that sets the mode of the file hello to this: 
   * -rwxr-x-wx 1 julien julien 23 Sep 20 14:25 hello
* 9 Write a script that sets the mode of the file hello to this: 
   * -rwxr-x-wx 1 julien julien 23 Sep 20 14:25 hello
=======
About Bash projects
Unless stated, all your projects will be auto-corrected with Ubuntu 20.04 LTS.

Resources
Read or watch:

Permissions
man or help:

chmod
sudo
su
chown
chgrp
id
groups
whoami
adduser
useradd
addgroup
Learning Objectives
At the end of this project, you are expected to be able to explain to anyone, without the help of Google:

Permissions
What do the commands chmod, sudo, su, chown, chgrp do
Linux file permissions
How to represent each of the three sets of permissions (owner, group, and other) as a single digit
How to change permissions, owner and group of a file
Why can’t a normal user chown a file
How to run a command with root privileges
How to change user ID or become superuser
Other Man Pages
How to create a user
How to create a group
How to print real and effective user and group IDs
How to print the groups a user is in
How to print the effective userid
Requirements
General
Allowed editors: vi, vim, emacs
All your scripts will be tested on Ubuntu 20.04 LTS
All your scripts should be exactly two lines long ($ wc -l file should print 2)
All your files should end with a new line (why?)
The first line of all your files should be exactly #!/bin/bash
A README.md file, at the root of the folder of the project, describing what each script is doing
You are not allowed to use backticks, &&, || or ;
All your files must be executable
0. My name is Betty
Create a script that switches the current user to the user betty.

You should use exactly 8 characters for your command (+1 character for the new line)
You can assume that the user betty will exist when we will run your script
Repo:

GitHub repository: alx-system_engineering-devops
Directory: 0x01-shell_permissions
File: 0-iam_betty
1. Who am I
Write a script that prints the effective username of the current user.

Repo:

GitHub repository: alx-system_engineering-devops
Directory: 0x01-shell_permissions
File: 1-who_am_i
2. Groups
Write a script that prints all the groups the current user is part of.

Note: depending on the user, you will get a different output.

Repo:

GitHub repository: alx-system_engineering-devops
Directory: 0x01-shell_permissions
File: 2-groups
3. New owner
Write a script that changes the owner of the file hello to the user betty.

Repo:

GitHub repository: alx-system_engineering-devops
Directory: 0x01-shell_permissions
File: 3-new_owner
4. Empty!
Write a script that creates an empty file called hello.

Repo:

GitHub repository: alx-system_engineering-devops
Directory: 0x01-shell_permissions
File: 4-empty
5. Execute
Write a script that adds execute permission to the owner of the file hello.

The file hello will be in the working directory
Repo:

GitHub repository: alx-system_engineering-devops
Directory: 0x01-shell_permissions
File: 5-execute
6. Multiple permissions
Write a script that adds execute permission to the owner and the group owner, and read permission to other users, to the file hello.

The file hello will be in the working directory
Repo:

GitHub repository: alx-system_engineering-devops
Directory: 0x01-shell_permissions
File: 6-multiple_permissions
7. Everybody!
Write a script that adds execution permission to the owner, the group owner and the other users, to the file hello

The file hello will be in the working directory
You are not allowed to use commas for this script
Repo:

GitHub repository: alx-system_engineering-devops
Directory: 0x01-shell_permissions
File: 7-everybody
8. James Bond
Write a script that sets the permission to the file hello as follows:

Owner: no permission at all
Group: no permission at all
Other users: all the permissions
The file hello will be in the working directory You are not allowed to use commas for this script

Repo:

GitHub repository: alx-system_engineering-devops
Directory: 0x01-shell_permissions
File: 8-James_Bond
9. John Doe
Write a script that sets the mode of the file hello to this:

The file hello will be in the working directory
You are not allowed to use commas for this script
Repo:

GitHub repository: alx-system_engineering-devops
Directory: 0x01-shell_permissions
File: 9-John_Doe
10. Look in the mirror
Write a script that sets the mode of the file hello the same as olleh’s mode.

The file hello will be in the working directory
The file olleh will be in the working directory
Note: the mode of olleh will not always be 664. Make sure your script works for any mode.

Repo:

GitHub repository: alx-system_engineering-devops
Directory: 0x01-shell_permissions
File: 10-mirror_permissions
11. Directories
Create a script that adds execute permission to all subdirectories of the current directory for the owner, the group owner and all other users. Regular files should not be changed.

Repo:

GitHub repository: alx-system_engineering-devops
Directory: 0x01-shell_permissions
File: 11-directories_permissions
12. More directories
Create a script that creates a directory called my_dir with permissions 751 in the working directory.

Repo:

GitHub repository: alx-system_engineering-devops
Directory: 0x01-shell_permissions
File: 12-directory_permissions
13. Change group
Write a script that changes the group owner to school for the file hello

The file hello will be in the working directory
Repo:

GitHub repository: alx-system_engineering-devops
Directory: 0x01-shell_permissions
File: 13-change_group
14. Owner and group
Write a script that changes the owner to vincent and the group owner to staff for all the files and directories in the working directory.

Repo:

GitHub repository: alx-system_engineering-devops
Directory: 0x01-shell_permissions
File: 100-change_owner_and_group
15. Symbolic links
Write a script that changes the owner and the group owner of _hello to vincent and staff respectively.

The file _hello is in the working directory
The file _hello is a symbolic link
Repo:

GitHub repository: alx-system_engineering-devops
Directory: 0x01-shell_permissions
File: 101-symbolic_link_permissions
16. If only
Write a script that changes the owner of the file hello to betty only if it is owned by the user guillaume.

The file hello will be in the working directory
Repo:

GitHub repository: alx-system_engineering-devops
Directory: 0x01-shell_permissions
File: 102-if_only
17. Star Wars
Write a script that will play the StarWars IV episode in the terminal.

Repo:

GitHub repository: alx-system_engineering-devops
Directory: 0x01-shell_permissions
File: 103-Star_Wars
>>>>>>> 0394a595c02fa4fe294a5eb69b3af983552c8684
