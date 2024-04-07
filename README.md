# Command line commands (Windows)

### Clear screen
```
cls
```

### To see command info
```
command/?
```
Example: What does the cls command do?
```
cls/?
```

### Show all folders and files

```
dir /a
```

### Show Current directory
```
cd
```

### Change directory (forward)
```
cd directoryName
``` 

### Previous directory
```
cd ..
```

### Creating folder
```
mkdir "folder name1" "folder name2" "folder name3"
```

### Deleting folder
```
rmdir /s "folder name"

```

### Opening folder with vscode
```
code .
```

### Creating file
```
echo. > "file name.extention"
```

or
```
type null > "file name.extension"
```

### Deleting file
```
del "file name.extension"
```

### Opening file with notepad
```
notepad fileName.txt
```

### Opening file with vscode
```
code fileName
```

### Writing on file
```
echo write text here > fileName.txt
```

### Read file
```
type fileName.txt
```

### Adding text without overriding 
```
type write extra text here >> fileName.txt
```

### Recommended youtube video
[Windows Command Line Crash Course in Bangla](https://www.youtube.com/watch?v=kbyNSrhxuuI)



# Git and Github commands

### Git version check
```
git --version
```

## Git configuration
```
git config --global user.name "userName"

```
```
git config --global user.email "userEmail@email.com"
```

### Show git user name and email
```
git config --list
```

### Initializing git
```
git init
```

### Checking status
```
git status
```
### To track files (unstaging to staging area)
```
git add fileName
```

To add all files at once

```
git add .
```

### To see changes
```
git diff
```

### To discard changes in working directory
```
git restore
```

### To commit
```
git commit -m "commit message here"
```

### Staging and commiting directly
```
git commit -am "message here"
```

### To see commit history
```
git log
```
or to see few details

```
git log --oneline
```

### Uncommit
```
git reset
```

#### 1. Undo the act of commiting & leaving everyting else intact
```
git reset --soft HEAD^
```

#### 2. Undo the act of commiting & also removing from the stagging area
```
git reset HEAD^
```

#### 3. Completely undo it, throwing away all uncommitted changes resetting everything to the previous commit
```
git reset --hard HEAD^
```

### Show commit details
```
git show commit_id
```

### Switching commit
```
git checkout commit_id
```

### .gitignore file will ignore these files (sample file names)
```
test.txt
.env
*.txt
!main.txt
test?.txt
temp/
```

### Checking remote repository is connected or not
```
git remote
```

### to check which remote repository (URL) is connected 
```
git remote -v
```

### Remote repository connection
```
git remote add name REMOTE_URL
```
name = origin or others

### Clone a repository
```
git clone REPO_URL
```

### To push your changes to a remote Git repository
```
git push remote_name branch_name
```

### To pull changes from a remote Git repository into your local repository
```
git pull remote_name branch_name
```