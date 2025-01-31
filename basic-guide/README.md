# Project 0 - Basics Guide

## Command line git

For each command, include a brief definition of what it does, and a sample of how to use it. `status` has a sample of what a well done entry looks like.  For some commands, we can visually demonstrate that you have played with them in order to brush up your skills.  For each topic that should be viewable in your repository, there will be a note added of what the demonstrated element will be that we are checking for.

Entries that are currently crossed out we will get to later in the course.  You are welcome to update your guide at later points in the course and add details.

- status
  - Shows status of the local repository. This status includes:
    - number of local commits that have not been synced with remote (GitHub)
    - list of files in local folder than are NOT being tracked by git
    - list of files in local folder that have changes that need to be committed
  - `git status`
- log
    - Shows the commit history of the repository.
    - Very helpful for tracking things with multiple changes happening overtime.
    - Two ways to use this command, the first way shows just a long list of commits
    - `git log`
    - The second way provides users a condensed view
    - `git log --oneline`
- clone
    - Creates a local copy of a remote repository.
    - `git clone <repository_url>`
- add
- rm
  - separately note how to remove from tracking versus fully remove a file from teh repository and working directory
- commit
  - **DEMONSTRATE** Your GitHub repo should have a commit history of more than one.  Commit messages should state changes at points in time
- push
- fetch
- merge
  - **DEMONSTRATE** A commit in your GitHub history should have a standard message that content was merged.  Sample:
    - `Merge branch 'main' of github.com:WSU-kduncan/ceg3120f23-pattonsgirl`
- pull
- branch
  - **DEMONSTRATE** Your GitHub repo should have more than the `main` branch.  We can switch to the other branch and see content that may not be synced to `main`
- tag
- checkout
- init
- remote

## git files & folders

Provide descriptions of expected contents and what these are used for

- .git folder
- .gitignore file
  - **DEMONSTRATE** Your GitHub repo should contain a `.gitignore` file that shows you are ignoring a set of files (or a folder) to prevent accidentally tracking them
- ~~.git/hooks~~

## GitHub

Provide basic how-to-use guides.  This should be short and sweet so that you can refer to it as a quick guide.

- Pull Requests
  - should include what it is & how to perform one
  - **DEMONSTRATE** Generate and complete a Pull Request in your repository in GitHub.  Pretend you are two people.
- ~~Actions~~
- ~~Releases~~

## SSH

Provide basic how-to-use guides.  This should be short and sweet so that you can refer to it as a quick guide.

- SSH authentication to repositories
- SSH authentication to an AWS instance
- Using the `config` file in the `.ssh` folder

## Resources
Other resources are welcome, just cite them (you can do lazy citations here, or use markdown to make links throughout your guide).  This one is to an online book and covers anything you'd like to do with `git`
