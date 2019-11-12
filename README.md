# Tutorial
In order to send modifications, you should add them to a commit, then create a commit and finally push your commit to repository. 
Before doing any modifications, be sure to work with the latest version. 
Before leaving, be sure to send your modifications (if possible, tested modifications). 

## To set up everything (do this only once)

### Create a github account
Then send me your nickname so I can add you as contributor

### Follow this tutorial
[Install the bash, set you username and email](https://help.github.com/en/github/getting-started-with-github/set-up-git#setting-up-git)

Then give me your username so I can add you as contributor.

### Create your local copy
Type these commands one by one in the bash console.
(be sure to open the console in the folder in which you want to receive all the files of this project).
You can past text in console using the mouse's middle button
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
You should see the readme file in red because it has been modified in you local copy of the project.

You can add modified files to your commit (here only README.md):
```
git add .
```
Then you can create the commit and try to send it
```
git commit -m "my first commit"
git push --set-upstream origin master
```
If you have a problem, tell me. For all next moficication, `git push` without following parameters is enough.
Don't forget to `git pull` every time you wnat to work on the project so have the latest versions of files.

# Useful commands

To get latest version from github
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