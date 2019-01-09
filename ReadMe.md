# Git and Github

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
* Github is an application allowing to store remote repositories(hub to git).
* Github can interact with local machine through push/pull system on ur local machine.
* Github used primarily to allow other people to add to the project (ex open source projects).
* Github allows more people than just you to see and interact with the repository.
* Github is sort of platform to use git.
* Git is version control software allowing you to take snapshots & distribute yout creation and modifications over time.
* Github is an application allowing you to store and interact with ur repositories on a remote server as well as adding more features () eg: publicity,license,collaboartors.
* Git is bones and flesh of SC while github gives u the platform to work with ur repository easier.

### Installing Git
* We need kind of shell or a command prompt
* https://git-scm.com/downloads
* gitbash
![gitbash](https://user-images.githubusercontent.com/43897511/50851841-92e92400-1343-11e9-9f1b-fc0461ba74dd.PNG)
* Test git is working or not
  * Open gitbash
  * git --version  (_version of git installed_)
  
### Repositories
* data storage sore full history and source control of projects
* can be hosted either locally or on a shared server such as github
* most repo are stored on github , while contributors make copies of the repo on their machine and update the repo using the push/pull system
* any repo stored somewhere other than locally is called a remote repository
* repo is timelines of entire project including all previously changes whereas directories or wrkng directoris are projects at their current state in timelines
* any local directory interacting with a repo is technically a repo itself,however call it as local repository

### Git workflow
* before git tracks a change , it goes through a long chain of operations and tasks
* working directory(projects at their current state in timelines) -> changes/modification -> Staging area(bundle of all modifications to the project that are going to be commit) -> commit(similar to taking snapshot of the current state of the project , then storing it on a timelines) -> local repo -> push -> remote repo

### Creating new repository
1) Create a local directory "Projects/Learning"
2) Add a text file in the folder "learngit.txt"
3) Move to the terminal and go to the path "/c/Users/leo_a/Documents/Projects/Learning"
4) now we try to add the file using git 
![gitaddnostagingarea](https://user-images.githubusercontent.com/43897511/50918794-d48ed300-1406-11e9-8087-a5f5a4e7e368.PNG)
_not in git reporsitory,we need to initialize it_
5) ![gitinit](https://user-images.githubusercontent.com/43897511/50918966-3cddb480-1407-11e9-8176-81979b6e86e3.PNG)
new git repository initialized which have all detailed about the project 
![initfolder](https://user-images.githubusercontent.com/43897511/50919075-7f06f600-1407-11e9-93d9-268d849b0425.PNG)
6) Check staging area current status7)
![gitstatus](https://user-images.githubusercontent.com/43897511/50919300-0ce2e100-1408-11e9-8885-0b6353c7aff8.PNG)
_staging area have no commits_
7) Add a file in staging area
"git add learngit.txt"
8) Check staging area status 
![addstatus](https://user-images.githubusercontent.com/43897511/50919439-706d0e80-1408-11e9-8f42-d2556e8f7996.PNG)
_one file added for commit in atging area_
9) Working with  multiple files 
![1](https://user-images.githubusercontent.com/43897511/50919782-5ed83680-1409-11e9-8330-e836587d9d0c.PNG)
Adding/Deleting/Updating in the staging area
![2](https://user-images.githubusercontent.com/43897511/50919835-83cca980-1409-11e9-9e2a-d406efe11018.PNG)
![3](https://user-images.githubusercontent.com/43897511/50919866-9c3cc400-1409-11e9-895c-d67146f17964.PNG)
![4](https://user-images.githubusercontent.com/43897511/50919872-a1017800-1409-11e9-837a-9d5213043b78.PNG)
10) Removing file from directory "git rm <filename>" or force remove "git rm -f <filename>"
11) Untrack some files/ignore files or just remove files from staging area(do not delete from directory) "git rm --cached <filename>"
12) Commit (takes a snapshot of all the changes done at the time and store them in a tree)
 ![gitcommitbefrusername](https://user-images.githubusercontent.com/43897511/50920926-52a1a880-140c-11e9-9d10-5331e45c0b13.PNG)
  _no username and account assigned, we have assign that before any commit , its juts one time process_
  _git config --global user.email "ricky_198922@yahoo.co.in"_
  _git config --global user.name "ricky"_
 13) Now we can commit 
  ![commit](https://user-images.githubusercontent.com/43897511/50921245-2d616a00-140d-11e9-9ed5-3a9715210358.PNG)
  _ m flag is for message , you can put any message according to your wish_
  14) If you want to commit only tracked files use
  _git commit -a - m "Your message"
  commit untrack files
  15) See history of changes
  git log
  ![log](https://user-images.githubusercontent.com/43897511/50921441-b082c000-140d-11e9-833f-a7b8087c8abf.PNG)
15) 
  now if we want to go back to initial committed



git ccheckout <commit id>



<going back in time>

head is at different commit





mastrer branch



git checkout master (goes back in time you will see all commits)

and then u can go to the commit u want





  





