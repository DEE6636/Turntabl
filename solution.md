## Exercise 1
Git was created by Linus Torvalds in 2005

**The essence of Git is to**

    -Tracks changes to files over time
    -Allows multiple developers to work on the same project simultaneously
    -Maintains a complete history of changes
    -Enables branching and merging of different lines of development

## Exercise 2 
   * Git: The actual version control software that runs locally on your computer

   * GitHub: A cloud-based hosting service for Git repositories with collaboration features (owned by Microsoft)

   * GitLab: Similar to GitHub but also offers self-hosted options and more extensive DevOps features

## Exercise 3
* Centralized VCS:
    Subversion (SVN)
    Concurrent Versions System (CVS)
    Perforce

* Distributed VCS:
      Mercurial (Hg)
      Bazaar (Bzr)
      Fossil

* Other:
    Apache Teamware
    BitKeeper (proprietary)

## Exercise 4
**git init**: Initializes a new Git repository in the current directory. It creates a hidden .git folder that contains all the necessary repository files.

**git status**: It displays which changes have been staged, which haven't, and which files aren't being tracked by Git.


## Exercise 5
     It permanently stores changes from the staging area to the repository history
![image for question 5](images/Screenshot%202025-09-09%20153128.png)

## Exercise 6
    Git ignores files using a .gitignore file. Git does not track files and directories in this file
![image for question 6](images/Screenshot%202025-09-09%20160139.png)


## Exercise 7
    git log displays the commit history of the repository.
![image for question 7](images/Screenshot%202025-09-09%20161029.png)


## Exercise 8
    git add moves changes from your working directory to the staging area (also called index). It prepares changes to be included in the next commit.

## Exercise 9
    The staging area (also called index) is where Git stores changes that are prepared for the next commit. It's an intermediate area between your working directory and the repository history.
![image for question 9](images/Screenshot%202025-09-09%20161812.png)


## Exercise 10
    You use the -m flag followed by your commit message in quotes

**Examples**:

    git commit -m "Fix login bug" 
    git commit -m "Add user authentication feature"

## Exercise 11
**git pull**: Does a git fetch followed by a git merge. It downloads changes and immediately integrates them into your current branch.

**git push**: Uploads your local commits to a remote repository.

**git fetch**: Downloads changes from a remote repository but doesn't integrate them into your local branches. It's like checking what's new without applying changes.

## Exercise 12
Using **git remote show** [remote-name] to see detailed information about a remote
![image for question 12](images/Screenshot%202025-09-09%20163755.png)


## Exercise 13
-**Merge** combines branches by creating a new commit that has two parents.

-**Rebase** moves or combines a sequence of commits to a new base commit.
![image for question 13](images/Screenshot%202025-09-09%20165719.png)


## Exercise 14
**git checkout**: is used to switch branches or restore working tree files.

**Alias**: git switch (for branches) and git restore (discard chages in a files)
![image for question 14](images/Screenshot%202025-09-10%20002156.png)


## Exercise 15
**Tags** are references to specific points in Git history, typically used to mark release points.

Two types of tags:<br>
**Lightweight tags**: Simple pointers to specific commits

**Annotated tags**: Store extra metadata (tagger name, email, date, message)

## Exercise 16
    Yes, you can delete a branch in Git.

**Difference between `-d` and `-D`:**<br>
**-git branch -d branch-name**:Safe delete - only deletes if the branch has been fully merged

-**git branch -D branch-name**: Force delete - deletes the branch even if it has unmerged changes
![image for question 17](images/Screenshot%202025-09-10%20003709.png)


## Exercise 17
    Yes, you can rename branches.
![image for question 17](images/Screenshot%202025-09-10%20004212.png)


## Exercise 18
**Reset**: Moves the branch pointer to a previous commit (rewrites history)

**Rever**t: Creates a new commit that undoes the changes from a previous commit (safer for shared history)

**Differences**<br>
Reset Rewrites history while Revert Adds new commit

Reset Dangerous for shared branches  while Revert  Safe for shared branches

Reset Local changes only  while Revert  Undoing public commits

## Exercise 19
![image for question 19](images/Screenshot%202025-09-10%20020744.png)
![image for question 19](images/Screenshot%202025-09-10%20021449.png)



