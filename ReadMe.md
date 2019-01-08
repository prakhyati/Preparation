#Git and Github

### What is Source/Version control?
* A way of tracking your files progress over time or a view of how your project progressed over time
* It is usually saved in a series of snapshots and branches,which you can move back and forth between.
* Allows distribute ur file changes over time.
* prevent against data loss/damage by creating backup snapshots.
* manage complex project structures easily.
  
### What is Git?
* Git is a source control.
* popular 
* lot of docs and support
* lots of integration with other application eg github,


### Difference between git and github
* github is an application allowing to store remote repositories(hub to git).
* Github can interact with local machine through push/pull system on ur local machine.
* Github used primarily to allow other people to add to the project (ex open source projects).
* Github allows more people than just you to see and interact with the repository.
* Github is sort of platform to use git.
* Git is version control software allowing you to take snapshots & distribute yout creation and modifications over time.
* Github is an application allowing you to store and interact with ur repositories on a remote server as well as adding more features () eg: publicity,license,collaboartors.
* Git is bones and flesh of SC while github gives u the platform to work with ur repository easier.

### Installing Git
  > 





https://git-scm.com/downloads



git --version  version of git installed





if u r windows user then



contro .program turn windows feature on and off

windows subsytem for linux restart





window store install ubuntu 



git workflow



before git tracks a change , it goes through a long chain of operations and tasks

many of these tasks are user controlled and are required for changes to be tracked correctly







repositories



data storage sore full history and source control of projects

can be hosted either locally or on a shared server such as github



most repo are stored on github , while contributors make copies of the repo on their machine and update the repo using the push/pull system



any repo stored somewhere other than locally is called a remote repository



repo is timelines of entire project including all previously changes 



directories or wrkng directoris are projects at their current state in timelines



any local directory interacting with a repo is technically a repo itself .



however call it as local repository





wrknf dir -git add -staging area -git commit -repository

wd : ur proj current state and time 

staging area : bundle of all modifications to the project that are going to be commit





commit is similar to taking snapshot of the current state of the project , then storing it on a timelines





creating new repository

my project 

add a text file there



and then using git add command 





error :not in agit repo 



before u run any git u need to git init(initialize a repo)



to check how ur staging area looks like



u do git status





no files are currently being tracked 

theres nothing to commit





add files to staging area





we see there is a file whose changes are to be committed



adding multiple files together in staging area



all files in staging area





if we remove/delete some files it doesnt stage for committed



if u dont want to track some files

  this completely removes the files





  do cache , it will be now in untracked files





  setting up username email





  initiale committed



  commit untrack files



  git log : list all logs



now if we want to go back to initial committed



git ccheckout <commit id>



<going back in time>

head is at different commit





mastrer branch



git checkout master (goes back in time you will see all commits)

and then u can go to the commit u want





  





