# Git and Github

A quick tutorial on how to use git and github the online home for the world's open-source code.

## First: Overview

Git is a "version control" system.  

It takes snapshots of your code (or any files) called **commits** that act as little time-capsules.

At any time you can **checkout** a any moment in time that has been commited to the **repository** (the timeline of commits for your codebase).

![Demo picture of git commits](https://www.nobledesktop.com/image/blog/git-branches-merge.png)

The key reasons to use something like git are to:

* Protect your codebase against accidental errors/deletions/bugs (if you have a time-machine you can go back and restore the timeline)

* Allow remote sharing of resources/code between many team members

* Creating (**forking**) parallel universes called **branches** that let any team member make a xerox of the entire codebase and go full mad-scientist in their own world

* Take only the best parts of the mad-science and **merge** those parts back into the main codebase (the **master branch**).  When done on github this is called a **pull request**

* It is *very good* at taking two people's independent changes to the same file and merging the edits.

Git mixes google drive with the best parts of the blockchain, creating a permanent record of the timeline, and allowing sharing across teams.

## The Vocabulary:

* **commit** a snapshot of the codebase to be remembered forever `git commit -m "commit message here"`
* **branch** one cohesive of commits which can trace back every change (delta) from the beginning to that moment in history
* **master** the default branch which should be used for production worthy code with the fewest amount of errors
* **checkout** to leave one branch and load up another `git checkout somebranch` this can include previous commits
* **fork** to create a new branch from an existing branch `git checkout -b newbranch`
* **clone** to make an exact copy of a codebase into a new location `git clone URLHERE`
* **push** to take local commits and share them to the a central repository (like github)  `git push origin master`
* **pull** to grab commits from the central repository into your workspace `git pull origin master`
* **log** the record of commits on your current branch `git log`
