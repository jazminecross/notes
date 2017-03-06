# Notes
## Udacity Courses 

### Git & Github
#### 1. Setting up your system
<ul>
    <li>Launch your Texteditor from the command line: https://www.udacity.com/wiki/ud775/sublime</li>
    <li>Set up your workspace</li>
        <ol>
            <li>create a version-control directory aka folder to hold files</li>
            <li>Create a sub-directory where you will place your plain text file s .txt like you did in the course (see lesson_1_reflections.txt) </li>
        </ol>
        Table of commands for Gitbash or terminal

        cd ~                             # change directories to your home directory
        mkdir version-control            # make version-control directory
        cd version-control               # go to version-control directory
        mkdir reflections                # create reflections directory
        cd reflections                   # go to reflections directory
        subl lesson_1_reflections.txt    # launch sublime with file called lesson_1_reflections.txt 
</ul>

<li>Use following commands to double check your setup</li>

        pwd                         # print working directory - shows what directory you are in
        ls                          # list the files in this directory

### 2. Git Repositories and Directories
  git init  - initializes an empty git repository or reinitialize an existing one 
  git log - to see what commits you already have (if any). If none, you get 
  git log --stat   will show which change in commits with +++ or ---   
  fatal error
  git add [name of file] - adds the commit 
  git status - shows you the untracked and tracked file 
  git clone exampleclonedandcopiedurl.git 
  git commit -m "commit message here" - to add a commit message, make this 
  concise and specific 
           *while you can make a message whatever you want, you should use best practices for the messages especially if working on a team*/
           http://udacity.github.io/git-styleguide


### 3. Comparing files in git 
    git diff file1name file2name

### 4. Adding a branch to your repository
    git status    #shows you the branch you are on, probably the master branch 
    git branch    #will create the branch - but still on master 
    git branch easy-mode  #will add easy-mode but any changes will still be on master 
    git checkout easy-mode   # will make all changes from here on the easy-mode branch and not the master 

    


Markdown 
install - http://plaintext-productivity.net/2-04-how-to-set-up-sublime-text-for-markdown-editing.<!DOCTYPE html>

