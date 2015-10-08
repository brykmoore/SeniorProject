#Coding Standards and Naming Conventions
- use PascalCasing for class name and method names.
- use camelCasing for method arguments and local variables.
- prefix private variables with an underscore.
- prefix interfaces with the letter I/
- vertically align curly braces
- comments belong on their own line, not mixed with code

# Basic git commands:

git pull = git fetch + git merge

git push = sends commits to remote repo

git fetch = gets updates from remote and stores in local repo

git merge = integrates commits in your local branch

git commit = records changes to the repository
flags ->
-a = All changes
-m = Message
ex. git commit -a -m "#1230 Adding remove file functionality"

git add = adds specified file to be tracked for changes
git add -A = adds all files available

git status = shows the working tree (files to be committed, files not being tracked, etc.)

Typical git workflow:
- git pull
- git commit -a -m "Message"
- Resolve any conflicts - I use source tree for this
- git push
