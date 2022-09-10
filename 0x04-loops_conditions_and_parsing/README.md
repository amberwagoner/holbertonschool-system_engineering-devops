# 0x04. Loops, conditions, and parsing

## Learning Objectives
- What is the advantage of using `#!/usr/bin/env bash` over `#!/bin/bash`
- How to use `while`, `until`, and `for` loops
- How to use `if`, `else`, `elif`, and `for` loops
- How to use the `cut` command
- What are files and other comparison operators, and how to use them

## Tasks

### 0. For Best School loop
Write a Bash script that displays `Best School` 10 times. Must use `for` loop.

### 1. While Best School loop
Write a Bash script that displays `Best School` 10 times. Must use `while` loop.

### 2. Until Best School loop
Write a Bash script that displays `Best School` 10 times. Must use `until` loop.

### 3. If 9, day Hi!
Write a Bash script that displays `Best School` 10 times, but for the 9th iteration, displays `Best School` and then `Hi` on a new line. Must use `while` loop and `if` statement.

### 4. 4 bad luck, 8 is your chance
Write a Bash script that uses `while` loop and `if`, `elif`, and `else` statements. Displays:
- `bad luck` for the 4th loop iteration
- `good luck` for the 8th loop iteration
- `Best School` for the other iterations

### 5. Superstitious numbers
Write a Bash script that uses `while` loop and `case` statement. Displays numbers 1 through 20 and:
- `4` and then `bad luck from China` for the 4th loop iteration
- `9` and then `bad luck from Japan` for the 9th loop iteration
- `17` and then `bad luck from Italy` for the 17th loop iteration

### 6. Clock
Write a Bash script using the `while` loop that displays the time for 12 hours and 59 minutes:
- displays hours from 0 to 12
- displays minutes from 1 to 59

### 7. For ls
Write a Bash script using a `for` loop that displays:
- The content of the current directory
- In a list format
- Where only the part of the name after the first dash is displayed

### 8. To file, or not to file
Write a Bash script that gives you information about the `school` file with `if` and `else`.
Your Bash script should check if the file exists and print:
- if the file exists: `school file exists`
- if the file does not exist: `school file does not exist`
If the file exists, print:
- if the file is empty: `school file is empty`
- if the file is not empty: `school file is not empty`
- if the file is a regular file: `school is a regular file`
- if the file is not a regular file: (nothing)

### 9. FizzBuzz
Write a Bash script that displays numbers from 1 to 100.
Requirements:
- Displays `FizzBuzz` when the number is a multiple of 3 and 5
- Displays `Fizz` when the number is a multiple of 3
- Displays `Buzz` when the number is a multiple of 5
- Otherwise, displays the number
- In list format
