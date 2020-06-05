# Git Commands and Terminology

Here are some commands and terms you should be familiar with when starting to learn Git:

* **Repository** - A repository is like a folder for your project.  The repository contains all of the project's files and stores each file's revision history.
  * [Additional Help](https://help.github.com/en/github/creating-cloning-and-archiving-repositories/about-repositories)
* **Clone** - A local copy of the remote repository on GitHub to your local machine. Cloning a repository to your computer makes it easier to work with (ex. Allowing you to use your editor of choice, adding or removing files, etc.)
  * [Additional Help](https://help.github.com/en/github/creating-cloning-and-archiving-repositories/cloning-a-repository)
* **Fork** - A fork is a copy of the repository which allows you to freely experiment with changes without affecting the original project.  Forks are used to either propose changes to someone else's project, or use someone's project as a starting point for your own idea.
  * [Additional Help](https://help.github.com/en/github/getting-started-with-github/fork-a-repo)
* **Branch** - A branch off the main "default" branch that allows for isolated development work without affecting other branches in the repository.  Typically, you might create a branch from the "master" branch of your repository.
  * Creating a branch: *git branch [name of branch]*
  * Checking out a branch: *git checkout [name of branch]*
  * Creating AND Checking out a branch at the same time:  *git checkout -b [name of branch]*
  * [Additional Help](https://help.github.com/en/github/collaborating-with-issues-and-pull-requests/about-branches)
* **Commit** - "git commit" is similar to saving a file.  A commit is a change to one or more files to your branch.  When making a commit you must include a commit message that briefly describes the changes.
  * Creating a commit:  *git commit*
  * [Additional Help](https://help.github.com/en/desktop/contributing-to-projects/committing-and-reviewing-changes-to-your-project)
* **Merge** The Git Merge command lets you take the independent lines of development created by "git branch" and integrate them into a single branch.  It will combine multiple sequences of commits into one unified history
  * Creating a merge:  *git merge*
  * [Additional Help](https://www.atlassian.com/git/tutorials/using-branches/git-merge)
* **Checkout** - Git command that switches branches or restores working tree files
  * *git checkout [branch]*
  * [git checkout Documentation](https://git-scm.com/docs/git-checkout)
* **Push** - updates the remote repository along with any commits made locally to a branch. 
  * *git push*
  * [git pull Documentation](https://git-scm.com/docs/git-push)
* **Pull** - updates the local line of development with updates from its remote counterpart.  Use this command to update commits made on a remote branch to reflect on their local environment
  * *git pull*
  * [git pull Documentation](https://git-scm.com/docs/git-pull)
* **Remote Add** - adds a new remote
  * *git remote add [name of new remote][url]*
  * [Documentation](https://help.github.com/en/github/using-git/adding-a-remote)
* **Remote Remove** - removes a remote. All remote-tracking branches and configuration settings for the remote are updated
  * *git remote remove [name of remote]*
  * [git remote remove Documentation](https://git-scm.com/docs/git-remote)
* **Remote Show** - gives some information about the remote
  * *git remote show [name of remote]*
  * [git remote show Documentation](https://git-scm.com/docs/git-remote)
* **Status** - shows the status of changes in the working tree as untracked, modified, or staged
  * *git status*
  * [git status Documentation](https://git-scm.com/docs/git-status)
* **Master Branch** -  the main branch or ‘trunk’ of a repository


[Back to Index](README.md)
