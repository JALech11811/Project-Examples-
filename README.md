# Project-Examples-
This repo will be used to house all project examples for my personal development


## High Level Git Steps
```bash
1. Clone prod code using git clone
2. Create dev branch with git checkout
3. Do the code changes
4. Check what we have modified with git status
5. Index the modified files with git add .
6. Commit the files/changes with git commit -m’Message’
7. Push from local branch to remote branch using git push origin
8. Create a PR for code review
    a. Let colleagues review if required
9. Merge to master branch
10. Checkout of dev branch once changes have been merged to master using git checkout main
11. Pull the remote changes from main branch into local machine using git pull on main branch
```

## Git Commands

1. See status of your branch/main
```bash
git status
```

2. Clone the repository:
```bash
git clone https://github.com/JALech11811/Project-Examples-.git
```

3. Create new branch
```bash
git checkout -b CANTYPENAMENOSPACES
git checkout -b 'IFYOUWANTTOADDSPACES'
```

4. Check into another branch
```bash
git checkout ADDBRANCHNAME
git checkout main : this takes you to the main branch
```

5. Ensure your branch is updated
```bash
git fetch : this fetches all remote branches or tags
git pull : fetch any code from remote main repo that is not on local
```

6. See list of branches
```bash
git branch -a  : fetches all branches
```

7. Add changes to file / index new and modified files
```bash
git add .   adds all changes
git add -A  adds all changes
```

8. Committing changes from local to remote
```bash
git commit -m "TYPE WHAT YOU WANT IN SPACES"
git commit -m TYPEWHATYOUWANT

```

9. Git push changes to remote from local
```bash
git push origin
if it fails means you need to publish the branch, you will get something like this
git push --set-upstream origin addcommandstomakefile  -> this is the name of the branch
```

10. Create a Pull Request for code review
```bash
in git itself you click create pull request
or
after you run git push
you can ctrl/command click the link
```

11. Help
```bash
git help
--help
```

12. Search for something in Window
```bash
shift+command+p
this is an easy way to open the search bar on top to review/search for something
```

13. Search log
```bash
git log    contains information about actions
can add or commit from here if needed
```


## CLI Commands

1. List the directory contents
```bash
ls
```

2. Make a new directory
```bash
Mkdir NAMEOFDIRECTORY
```

3. Navigate to directory
```bash
cd DIRECTORYNAME
```

4. Display current file path
```bash
pwd
```

5. Deleting
```bash
rm FILENAME  deletes a file
rm -r DIRECTORYNAME  deletes a directory
rm -f FILENAME  force deletes a file
```

6. Update file access/create a file if it doesn't exist
```bash
touch FILENAME
```

7. Moving/renaming
```bash
mv OLDFILENAME NEWFILENAME
mv FILENMAE DIRECTORYNAME
```

8. Copy
```bash
cp FILENMAE DIRECTORYNAME
```
