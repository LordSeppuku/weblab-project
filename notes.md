# Agenda

- command line
- git

## Command Line

*Your computer's secret menu!* 
Also known as the terminal, it manages files, coding, Git commands, and more!

### Demo/Commands

- "pwd" : means "print working directory". prints current directory.
- "ls" : lists out all files and folders in current directory.
- "cd" : changes current directory to that folder.
- "rm" : removes target file.
- "touch" : creates target file.
- "mkdir" : makes a specified directory.
- "rmdir" : remove directory.
- "mv <src> <dst>" : move from source to destination.
- "cp <src> <dst>" : copy from source to destination.

## Git

A version control system that allows for asynchronous collaboration!

### Comands

- git init : initialize a new repo in the working directory
- git status : get the status of the repo
- git add : adds files to the commit
- git commit -m "mesg" : commits files
- git remote add : adds an upstream repo to push to
- git branch -M <branch> : creates a new branch
- git push -u origin <branch> : pushes all staged commit to repo
- git push --set-upstream origin master : *always* do this for first push!