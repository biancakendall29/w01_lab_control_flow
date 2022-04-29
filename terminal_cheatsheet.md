# Terminal and Git cheatsheet

## Basic commands

| **Command** | **Description** |
| ------------- | ------------ | 
| Ctrl + U | deletes everything on a line to the left of the cursor |
| `ls`| lists the folders/files in the current directory |
| ` ls -a` | lists all folders/files, including hidden ones |
| `pwd` | shows the current directory path |
| `cd <folder name>` or `cd <folder1>/<folder2>` | moves to specified directory |
| ` cd ..` | moves up one level in the directory |
| ` cd -` | changes back to the last directory you were in |
| ` cd ~` or ` cd ` | changes to the home directory |
| ` touch <file name>.<file type>` | creates a new file |
| `open <file name>` or `code <file name>` or `code .`| opens file in default program for that file type |
| `nano <file name>` | opens file in terminal editor |
| `mkdir <folder name>` | creates a new folder/directory |
| ` mv <old_name> <new_name>` | changes the name of a file or directory |
| ` mv <file name> ~/<folder1>/<folder2>` | moves file into specified directory (absolute) |
| ` mv <file name> <./folder name>` | moves file into folder in current directory (relative) |
| ` cp <file name> <file name copy>` | copies a file to current directory |
| ` cp <file name> <folder name>` or `cp <file name> ~/<folder>/<new file name>` | copies a file to specified directory (optionally renaming the copied file)|
| ` cp -r <folder name> <folder name copy>` | copies a folder and its contents |
| ` rm <file name>` | deletes a file |
| ` rm -r <folder name>` | deletes a folder and its contents |
| `cat <file name>` | outputs contents of file |

## Procedure for Git

1. Create file in terminal.
2. Type `git init` to initialise.
3. `git status` tells you where you're at in the process.
4. `git add <file name>` to add file to stage, or `git add .` to add everything in current directory to stage.
5. `git commit -m"<message/label for commit>"` commits file to your machine along with a message description of the file.
6. `git log` = tells you what's been committed
7. Type `ssh-keygen -t rsa -b 4096 -C "biancakendall29@gmail.com"` to generates an SSH key (no need to enter a password or file name in which to save it).
8. Navigate to the directory in which the SSH key was saved.
9. Type `cat .ssh/id_rsa.pub` to print the SSH key to the terminal (copy this key.)
10. Go to GitHub online and add a repository by clicking the plus button in the top right corner.
11. Paste the SSH key into new repository input and create key.
12. Choose the option "…or push an existing repository from the command line" and copy the corresponding code to clipboard and paste in the terminal to execute.
13. The file should then upload to the repository in the GitHub cloud.








