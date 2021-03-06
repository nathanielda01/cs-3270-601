Assignment Submissions
================================================

For this class all assignments will be submitted by pushing code to a remote hosted on github for which
i have been granted access to.  The details on how you will need to setup your repository and how I will
retrieve the code for testing is defined below.   

## Git

For this course we will be using the git source control system.  Git provides the ability to be able to
synchronize all of your code and associated history.  There are a few important keywords that will be
used through out this document, they are defined below.   

* remote - A remote is a reference to an external git repo that you can sync your code with    
* upstream - the remote that should be considered the source of most changes.   
* origin - the default remote that git will push/pull from   
* pull - Synchronizing your local git repo with a remote's repo by retrieving all deltas from remote to local   
* push - Synchronizing remote repo with your local git repo by sending your deltas up to a remote   
* github - A hosted git management tool for working with remote repo.   
* commit - Capture all the current changes into a single delta and point current branch at the new delta    
* branch - A local pointer to the list of deltas to be using with your code.   
* master - The default branch that git repos use.    

## Commands

* `git clone <url>` - Downloads the git repository for specified location to your local hard drive   
* `git add <file>` - Takes the supplied file and tells git to add the changes to the next delta   
* `git commit -m <msg>` - Take the requested deltas and creates the commit    
* `git pull <remote> <branch>` - Pull the remote branch to your current local branch   
* `git push <remote> <branch>` - Push the current list of deltas to given remote.   
* `git remote add <remote> <url>` - Adds a new remote to the list of remotes   

## Assignment Steps

To work with the assignments for this course you will need to accomplish the below steps.   

1. Obtain github account with private access   
2. Create a new `private` repo named `<uvuid>-assignments` (do not select Initialize README or select anything from the dropdowns)   
3. Add the user `mikekwright` as a user with read access to the repo   
4. Email me the created repo to the address `mkwright+uvu@gmail.com`   
5. Clone the repo to your local machine.   `git clone <your url>`   
6. Navigate to the repo directory.  `cd <uvuid>-assignments`   
7. Add this repo as the classes upstream repo `git remote add upstream https://github.com/ninja-coders/cs-3270-601 or git@github.com:ninja-coders/cs-3270-601.git`   
8. Pull down the upstream remote to your local system.  `git pull upstream master`   
9. Add a file to the root of the repo named `student` fill that file with contents of `Your Name` and `UVUID`    
10. Add the new file to staged `git add student`
11. Commit the new file `git commit -m "Added student file"`   
12. Push the repo with commits to your github repo `git push origin master`   
13. Navigate to the repo in the browser of your choice and make sure it is visible   

