# 0x01. Shell, permissions

## Learning Objectives
- What the commands `chmod`, `sudo`, `su`, `chown`, and `chgrp` do
- Linux file permissions
- How to represent each of the three sets of permissions as a single digit
- How to change permission, owner, and group of a file
- Why a normal user can't `chown` a file
- How to run a command with root privileges
- How to change user ID or become superuser

## Tasks

### 0. My name is Betty
Create a script that switches the current user to the user `betty`.
- Use exactly 8 characters for the command.
- Assume the user `betty` will exist when the script is run.

### 1. Who am I
Write a script that prints the effective username of the current user.

### 2. Groups
Write a script that prints all the groups the current user is part of.

### 3. New owner
Write a script that changes the owner of the file `hello` to the user `betty`.

### 4. Empty!
Write a script that creates an empty file called `hello`.

### 5. Execute
Write a script that adds execute permission to the owner of the file `hello`.
- The file `hello` will be in the working directory.

### 6. Multiple permissions
Write a script that adds execute permission to the owner and the group owner, and read permission to other users, to the file `hello`.
- The file `hello` will be in the working directory.

### 7. Everybody!
Write a script that adds execution permission to the owner, the group owner and the other users, to the file `hello`.
- The file `hello` will be in the working directory.
- Commas are not allowed for this script.

### 8. James Bond
Write a script that sets the permission to the file `hello` as follows:
- Owner: no permission at all
- Group: no permission at all
- Other users: all the permissions
The file `hello` will be in the working directory. Commas are not allowed for this script.

### 9. John Doe
Write a script that sets the mode of the file `hello` to -rwxr-x-wx
- The file `hello` will be in the working directory and commas are not allowed.

### 10. Look in the mirror
Write a script that sets the mode of the file `hello` to the same as `olleh`'s mode.
- Both files are in the working directory.

### 11. Directories
Create a script that adds execute permission to all subdirectories of the current directory for the owner, the group owner, and all other users. Regular files should not be changed.

### 12. More directories
Create a script that creates a directory called `my_dir` with permissions 751 in the working directory.

### 13. Change group
Write a script that changes the group owner to `school` for the file `hello`.


