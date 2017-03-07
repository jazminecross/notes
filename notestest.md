# Notes
## Udacity Courses 

### Git & Github
#### 1. Setting up your system

* Launch your Texteditor from the command line: https://www.udacity.com/wiki/ud775/sublime
    * Set up your workspace
    
        - Create a version-control directory aka folder to hold files
        - Create a sub-directory where you will place your plain text file s .txt like you did in the course (see lesson_1_reflections.txt)
        
* Table of commands for Gitbash or terminal

         
```
cd ~                             # change directories to your home directory
mkdir version-control            # make version-control directory
cd version-control               # go to version-control directory
mkdir reflections                # create reflections directory
cd reflections                   # go to reflections directory
subl lesson_1_reflections.txt    # launch sublime with file called lesson_1_reflections.txt

```


Use following commands to double check your setup

```
pwd                         # print working directory - shows what directory you are in
ls                          # list the files in this directory
```

### 2. Git Repositories and Directories
  ```
  git init  - initializes an empty git repository or reinitialize an existing one
  git log - to see what commits you already have (if any). If none, you get 
  git log --stat   will show which change in commits with +++ or ---   
  git add [name of file] - adds the commit 
  git status - shows you the untracked and tracked file 
  git clone exampleclonedandcopiedurl.git 
  git commit -m "commit message here" - to add a commit message, make this 
  concise and specific 
           *while you can make a message whatever you want, you should use best practices for the messages especially if working on a team*/
           http://udacity.github.io/git-styleguide
```

### 3. Comparing files in git 
```    
git diff file1name file2name
```

### 4. Adding a branch to your repository
```
git status    #shows you the branch you are on, probably the master branch 
git branch    #will create the branch - but still on master 
git branch easy-mode  #will add easy-mode but any changes will still be on master 
git checkout easy-mode   # will make all changes from here on the easy-mode branch and not the master 
```
    
### 5. Adding a Remote 
* adding a remote takes 2 arguments: remote name, remote URL 
```
git remote add origin https://...git   #sets a new remote to the link 
git remote -v  #verify new remote 
example: 
C:\Users\Jaz\Desktop\udacityFrontendResume\notes>git remote -v
origin  https://github.com/jazminecross/notes.git (fetch)
origin  https://github.com/jazminecross/notes.git (push)

git push origin master  # push your commit to github 
```
### 6. Pulling Changes 

```
git pull origin master  #pulling the new changes that are made on github to put them on local repository. Have master branch checkedout 
git log #to see new commit with chanhes on local repository
```

### 7.Forks, Clones and Branches  
1. fork repository (only used within the context of github)
2. clone (this is done on your local to another spot on your computer)
3. create branch (this is done on your local)
4. pull down the branch to your local 
5. make changes on your branch and push that to your fork

### 8. Viewing an old Submission 
- if you have started a crazy experiment, but you are not sure if you want to keep it or not, you can look at the state of a project before you had started the project. 
```
git log --oneline #shows you the id's of the revisions 
git checkout <id number> 
```
*see (https://www.atlassian.com/git/tutorials/undoing-changes) for details


Markdown 
install - http://plaintext-productivity.net/2-04-how-to-set-up-sublime-text-for-markdown-editing.<!DOCTYPE html>

