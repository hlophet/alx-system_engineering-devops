
0X01 SHELL PERMISSIONS
======================



THE DIFFERENT SCRIPTS & THEIR PURPOSES:


0 - My name is Betty: Creates a script that switches the current user to the user betty.

1 - Who am I: Prints the effective username of the current user.

2 - Groups: Pints all the groups the current user is part of.

3 - New owner: Changes the owner of the hello file to the user betty.

4 - Empty!: Creates an empty file called hello.

5 - Execute: Adds execute permission to the owner of the file hello.

6 - Multiple permissions: Adds execute permission to the owner and the group owner, and read permission to other users, to the file hello.

7 - Everybody!: Adds execution permission to the owner, the group owner and the other users, to the file hello.

8 - James Bond: Sets the permission to the file hello as follows:
owner: no permission at all, group: no permission at all, other users: all the permissions.

9 - John Doe: Sets the mode of the file hello to this: -rwxr-x-wx

10 - Look in the mirror: Sets the mode of the file hello the same as olleh’s mode.

11 - Directories: Adds execute permission to all subdirectories of the current directory for the owner, the group owner and all other users. Regular files should not be changed.

12 - More directories: Creates a directory called "my dir" with permissions 751 in the working directory.

13 - Change group: Changes the group owner to school for the hello file.

14 - Owner and group: Changes the owner to vincent and the group owner to staff for all the files and directories in the working directory.

15 - Symbolic links: Changes the owner and the group owner of _hello to vincent and staff respectively.

16 - f only: Changes the owner of the file hello to betty only if it is owned by the user guillaume.

17 = Star Wars: Play the StarWars IV episode in the terminal.
