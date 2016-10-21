# Demo project for Git Workshop.

## What you're doing
- Creating a fork ("version") of my Git repo that is hosted on GitHub on your account
- Creating a new local branch `add_cool_program` off of master
- Creating a new file within the `add_cool_program` branch
- Commiting the changes, i.e. a new file, within the `add_cool_program`
- Merging the changes within the `add_cool_program` branch into the `master` branch
- Pushing the changes in your local branch into your remote repository host on GitHub
- Requesting that I merge your changes in your fork of the repo into the original repo

## Instructions
1. Fork this project by clicking the Fork button and selecting your account
1. Clone the project onto your machine `git clone https://github.com/USERNAME/git-workshop.git`
1. Go into the cloned directory folder `cd git-workshop`
1. Create a new branch from master `git branch add_cool_program`
1. Observe your list of branches `git branch`
1. Check out the new branch `git checkout add_cool_program`
1. Write a program that prints out "Hello world" in your favorite language
1. Add the file to the stage e.g. `git add HelloWorld.java`
1. Commit the new file, e.g. `git commit -m "Add hello world program"`
1. Switch to the master branch `git checkout master`
1. Merge the `add_cool_program` branch into master `git merge add_cool_program`
1. Push your changes to GitHub `git push origin master`
1. Delete your merged branch `git branch -d add_cool_program`
1. On your git-workshop fork GitHub page, github.com/USERNAME/git-workshop, select New pull request
1. Select the green button that says Create pull request 
1. Confirm the pull request

*Don't forget to use `git status` before each of the commands as a sanity check*
