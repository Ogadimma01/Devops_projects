# Initializing a Git Repository

 ![photo](Images/gitinit.png)


# Making first commit

![photo](Images/gitcommit.png)

* The -m flag is used to provide a commit message. The message concisely explains why the commit was made.

# Make your first git branch

* Execute the command 'git checkout -b [new branch name]'

*  This command creates the new branch and switches you from the extant branch to the new one.

![photo](Images/brnch2.png)


# Listing your git branches

* Execute the command 'git branch' to list all the branches in your local git repository.

![photo](Images/branch.png)


# Switching to an old branch

* Execute the command 'git checkout [branch name] to change into an old branch.

![photo](Images/branch1.png)


# Merging one branch into another

* To merge say 'branch1' into barch 'main', first swithch to branch 'main'.

*  Then execute the command'git merge [branch1]'

![photo](Images/merge.png)


# Deleting a git branch

* Execute the command 'git branch -d [branch name]

![photo](Images/branch-d.png)

# Pushing your local git repository to your remote github repository

* To add a remote repository to your local git repository, use the following command:

  git remote add origin [link to your github repo]

![photo](Images/remote.png)

* After commiting all changes in your local repo, push the content to your rmote repo using the below command:

  git push origin [branch]

![photo](Images/gitpush.png)


# Cloning Remote Git Rrpository

* The git clone command is used to create a copy of a specific remote repository or branch within a repository into our local machine.

* The command to use is git clone [url of remote rpository]

![photo](Images/clone.png)

  
