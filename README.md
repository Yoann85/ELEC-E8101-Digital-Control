# Tutorial
[Good stuff about git](http://rogerdudler.github.io/git-guide/)

Before doing any modifications, be sure to work with the latest version (git pull). 
Before leaving, be sure to send your modifications (if they are useful).

## To set up everything (do this only once)

### Create a github account
Then send me your nickname so I can add you as contributor

### Follow this tutorial
[Install the BASH, set you USERNAME and EMAIL](https://help.github.com/en/github/getting-started-with-github/set-up-git#setting-up-git)

Then give me your username so I can add you as contributor.

### Create your local copy
Type these commands one by one in the bash console.
(be sure to open the console in the folder in which you want to receive all the files of this project).
You can past text in console using the mouse's middle button.
```
git init
git remote add origin https://github.com/Yoann85/ELEC-E8101-Digital-Control.git
git pull origin master
git push --set-upstream origin master
```
Now you should have all the files.

### Send your first modifications
Modify the READM.md file for test purpose.
Save it and then try this command:
```
git status
```
You should see the readme file in red because it has been modified in you local copy of the project but is not added yet to any commit.

You can add modified files to your commit (here only README.md):
```
git add .
```
Then you can create the commit and try to send it
```
git commit -m "my first commit"
git push --set-upstream origin master
```
If you have a problem, please tell me. For all next moficication, `git push` without following parameters is enough.
Don't forget to `git pull` every time you want to work on the project to have the latest versions of files.

# Useful commands

To get latest versions from github
```
git pull
```

To see local modifications, actual status of commits ...:
```
git status
```

To add specific modified file to next commit:
```
git add <filePath>
```

To add all modified files to commit:
```
git add .
```

To create the commit with a message:
```
git commit -m "Describe the modifications here"
```

To push the commit to the github repository:
```
git push
```