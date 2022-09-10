# 0x03. Shell, init files, variables and expansions

## Learning Objectives

### General
- What happens when you type `$ls -l *.txt`

### Shell Initialization Files
- What are the `/etc/profile` file and the `/etc/profile.d` directory
- What is the `~/.bashrc` file

### Variables
- What is the difference between a local and a global variable
- What is a reversed variable
- How to create, update and delete shell variables
- What are the roles of the following reserved variables: HOME, PATH, PS1
- What are special parameters
- What is the special parameter `$?`

### Expansions
- What is expansion and how to use them
- What is the difference between single and double quotes and how to use them properly
- How to do command substitution with `$()` and backticks

### Shell Arithemtic
- How to perform arithmetic operations with the shell

### The alias Command
- How to create an alias
- How to list aliases
- How to temporarily disable an alias

### Other help pages
- How to execute commands from a file in the current shell

## Tasks

### 0. \<o\>
Create a script that creates an alias with the name `ls` and the value `rm \*`.

### 1. Hello you
Create a script that prints `hello user`, where user is the current Linux user.

### 2. The path to success is to take massive, determined action
Add `/action` to the `PATH`. `/action` should be last directory the shell looks into when looking for a program.

### 3. If the path be beautiful, let us not ask where it leads
Create a script that counts the number of directories in the `PATH`.

### 4. Global variables
Create a script that lists environmental variables.

### 5. Local variables
Create a script that lists all local variables and environment variables, and functions.

### 6. Local variable
Create a script that creates a new local variable named `BEST` with the value `School`.

### 7. Global variable
Create a script that creates a new global variable with the name `BEST` and the value `School`.

### 8. Every addition to true knowledge is an addition to human power
Write a script that prints the result of the addition of 128 with the value stored in the environment variable `TRUEKNOWLEDGE`, followed by a new line.

### 9. Divide and rule
Write a script that prints the result of `POWER` divided by `DIVIDE`, followed by a new line. Both are global variables.

### 10. Love is anterior to life, posterior to death, initial of creation, and the exponent of breath
Write a script that displays the result of `BREATH` to the power `LOVE`. Both are global variables.

### 11. There are 10 types of people in the world -- Those who understand binary, and those who don't
Write a script that converts a number from base 2 to base 10. The number in base 2 is stored in the environment variable `BINARY`. The script should display the number in base 10.

