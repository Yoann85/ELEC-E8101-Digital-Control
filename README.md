# Basic commands
In order to send modifications, you should add them to a commit, then create a commit and finally push your commit to repository. 
Before doing any modifications, be sure to work with the latest version. 
Before leaving, be sure to send your modifications (if possible, tested modifications). 

## To set up everything (do this only once)
### Create a github account
Then send me your nickname so I can add you as contributor

### Follow this tutorial
[Follow step 1 and 2 is enough](https://help.github.com/en/github/getting-started-with-github/set-up-git#setting-up-git)

Then give me your username so I can add you as contributor.

### Create your local copy
Type these commands one by one in the bash console.
(be sure to open the console in the folder in which you want to receive all the files of this project).
You can past text in console using the mouse's middle button
```
git init
git remote add origin https://github.com/Yoann85/ELEC-E8101-Digital-Control.git
git branch
git push --set-upstream origin master
```

If you have a problem, tell me.

## To get latest version from github
`git pull`

## To see local modifications, actual status of commits ...:
`git status`

## To add specific modified file to next commit:
`git add <filePath>`

## To add all modified files to commit:
`git add .`

## To create the commit with a message:
`git commit -m "Describe the modifications here"`

## To push the commit to the github repository:
`git push`