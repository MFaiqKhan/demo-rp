# demo-rp
#clone this repo through git cli command

#Command for showing hidden files in windows(cmd)

---> dir /ah

# ----git basic commands and walkthrough basic git change and push repo-----

#for checking git version: 
git --version
#To clone the repo in local folder:
git clone (whole https url from github repo itself ending with .git)
#checking git status, for seeing any modified files or untracked files before we commit it into repo
git status
#before we commit the files for the snapshot so we can push it to main repo we first add the modified and untracked files
#using git add (specific file) #if we want to commit a single file or
'git add .' #which means we are telling git to track the all the files listed here, which includes modified and untracked files
#Now we check status by 'git status' and see files ready to be committed
#then we commit by 
git commit -m
#here -m is for any message and we have to write any message or even a letter but it has to do with what is being added
#or being modified so we will do like this:
# git commit -m "Added pracc.html" -m "some does description in README.md"
#now it will give some changes like what thing added and how many files change and lines of insertions to be added

#still this all changes are saved locally we yet have to change in main repo live in github by pushing applying push #command, which will be origin is an option set for us  here, and is basically a word that stands for  
#the location of our Git repository. Master is the  branch that we want to push to

# git push origin master #master is just the name of the branch it can be "main" in some cases

#after that our code changes will be live on github repo, and we will be able to see our commits live on github or locally
#On our pc

# that's it.your code is now live on github

Author identity unknown
*** Please tell me who you are.

Run

  git config --global user.email "you@example.com"
  git config --global user.name "Your Name"

to set your account's default identity.
Omit --global to set the identity only in this repository.