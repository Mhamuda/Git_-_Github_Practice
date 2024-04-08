# <b>Command line commands (Windows)</b>

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

Or,
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

<br>
<br>
<br>

# <b>Git and Github commands</b>

<img src="./images/git-level.png">

<br>

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

### To add all files at once

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
### To see commit history in one line
```
git log --oneline
```

### Uncommiting

- ####  Undo the act of commiting & leaving everyting else intact
    ```
    git reset --soft HEAD^
    ```

- #### Undo the act of commiting & also removing from the stagging area
    ```
    git reset HEAD^
    ```

- #### Completely undo it, throwing away all uncommitted changes resetting everything to the previous commit
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

### To check which remote repository (URL) is connected 
```
git remote -v
```

### Remote repository connection
```
git remote add name REMOTE_URL
```
Here, name can be origin or other name.

### Clone a repository
```
git clone REPO_URL
```

### To push your changes to a remote Git repository
```
git push -u remote_name branch_name
```

### To pull changes from a remote Git repository into your local repository
```
git pull remote_name branch_name
```
### Creating branch
```
git branch branchName
```

### Switching branch
```
git checkout branchName
```

### Creating and switching branch
```
git checkout -b branchName
```

### Deleting branch
```
git branch -d branchName
```

### Merging branch
```
git checkout main
git merge branchName
```

### To see all branches
```
git branch
```
### Github issues (commit message)
```
message here #issueNumber
```
It will notify the issue number in the issue section. Close the issue automatically when the commit is merged.

### Two way merging (fast-forward)
```
git checkout main
git merge branchName
```

### Three way merging 
```
git merge targetBranchName
```
It will create a new commit with two parent commits.

### Merge conflict
```
<<<<<<< HEAD
code
=======
code
>>>>>>> branchName
```
Resolve the conflict and commit again.
(Delete the code that is not needed.Then add, commit and push the changes.)


### How to contribute to a project on Github:
1. Fork the repository
2. Clone the repository
3. Create a branch
4. Make changes
5. Commit the changes
6. Push the changes
7. Create a pull request
8. Review the code
9. Merge the pull request


### How to work as a collaborator on Github :
1. Clone the repository
2. Create a branch
3. Make changes
4. Commit the changes
5. Push the changes
6. Create a pull request
7. Review the code
8. Merge the pull request

### How to publish your website on Github :
1. Create a repository
2. Add html, css, js files
3. Go to settings
4. Scroll down to Github Pages
5. Select the source (main branch)
6. Save the changes
7. Copy the link
8. Paste the link in the browser


### Recommended youtube video
[Git & GitHub complete course Bangla (Beginner to Advanced)](https://www.youtube.com/playlist?list=PLgH5QX0i9K3qAW8DT6I0XOxC23qnA4FL-)


