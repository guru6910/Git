
**Configure Your Email and Name in GitBash with Commands**
````
git config --global user.email "email-id"
git config --global user.name "name"
````
**git init : To initialize our folder as git working directory**
````
git init
````

**git clone : To clone git repository to our machine from github.com**
````
 git clone <project-repo-url>
````

**git status : It will display staged , un-staged and un-tracked files**

````
 git status
````

- Staged Files : The files which are added for commit

- Un-Staged Files : The files which are modified but not added for commit

- Un-tracked files : Newly created files

**git add : It is used to add file(s) to staging area**

````
git add <file-name>
git add .
````
**restore staged file**
````
git restore --staged  <filename>
````
**git commit : It is used to commit staged files to git local repository**

````
git commit -m 'reason for commit'
````


**git push : To push changes from git local repository to git central repository**

````
git push
````
**Branch: to check all branches**
````
git branch
````
**Create new branch and checkout**
````
git branch <branchname>
git checkout <branchname>
git checkout -b <branchname>
````
**delete branch**
````
git branch -d <branchname>
````
**pull remote repository to local**
````
git pull https://github.com/abhipraydhoble/Project-Student-App.git
````
**fetch remote repository to local**
````
git fetch https://github.com/abhipraydhoble/Project-Student-App.git
````
**Merge two branch**
````
git merge <branchname>
````
**push file in branch or push branch on remote**
````
git push origin <branchname>
````
**delete and forcefully delete branch**
````
git branch -d <branchname>
git branch -D <branchname>
````


