

- [X] Create local repository 

*Put your code below*

````
#Put your code after this line

git init

````
- [X] Set remote repository  to sync with

*Put your code below* 

````
#Put your code after this line 

git remote add origin git@github.com/firedot/git-tests.git

````

- [X] Pull branches & files from remote repository to the local one 

*Put your code below* 

````
#Put your code after this line 

git pull origin master

````

- [X] Set an upstream to be tracked (mapping the local repository to the remote)

*Put your code below* 

````
#Put your code after this line 

git branch --set-upstream-to=origin/master master

````

- [X] Create a new branch 

*Put your code below* 

````
#Put your code after this line 

#Switch to branch master

git checkout master

#Create branch f-addTaskfile and switch to it

git checkout -b f-addTaskfile

````

- [X] Add files that will be pushed to the remote repository

*Put your code below*

````
#Put your code after this line

git add ./Tasksfile

````

- [X] Commit changes

*Put your code below* 

````
#Put your code after this line 


git commit -m "Added Tasksfile"

````

- [X] Push local repository to the remote one

*Put your code below* 

````
#Put your code after this line 

git push --set-upstream origin f-addTasksfile

git push

````





