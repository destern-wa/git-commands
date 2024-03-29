# Git Commands Cheat Sheet

## Initialise repo

`git int .`
	- Creat new repo with the current folder
	
`git init REPO-NAME`
	- create new repository in a new folder REPO-NAME

## Stage changes
`git add FILE-NAME`

## Commit Changes
`git commit -m "Meaningfull commit message"`

## Show commit details
`git show`

## Show log of commits
`git log`

`git log --graph --oneline --decorate --all` - nicer version

## Create an alias for a command with options
`git config --global alias.YourAlias "command --with --options"`

e.g.
```
git config --global alias.adog "log --graph --oneline --decorate --all"
```
Omitting --global creates the alias for the current repo only

## Configure the current repo's User NAME
`git config user.name "USER'S NAME HERE"`

## Configure the current repo's User Email
`git config user.email email@address.com`

## Configure the global User NAME
`git config --global user.name "USER'S NAME HERE"`

## Configure the global User Email
`git config --global user.email email@address.com`

## View the current repo's configuration
`git config --list`

## View the global configuration
`git config --global --list`

## Get status of the project
`git status`
