# Project-Examples-
This repo will be used to house all project examples for my personal development 

## Git Commands

1. See status of your branch/main 
'''
git status
'''

2. Clone the repository: 
'''
git clone https://github.com/JALech11811/Project-Examples-.git
'''

3. Create new branch 
'''
git checkout -b CANTYPENAMENOSPACES
git checkout -b 'IFYOUWANTTOADDSPACES'
'''

4. Check into another branch
'''
git checkout ADDBRANCHNAME
git checkout main : this takes you to the main branch
'''

5. Ensure your branch is updated
'''
git fetch : this fetches all remote branches or tags
git pull : fetch any code from remote main repo that is not on local 
'''

6. See list of branches
'''
git branch -a  : fetches all branches 
'''

7. Add changes to file / index new and modified files
'''
git add .   adds all changes 
git add -A  adds all changes 
'''

8. Committing changes from local to remote
''' 
git commit -m "TYPE WHAT YOU WANT IN SPACES"
git commit -m TYPEWHATYOUWANT

'''

9. Git push changes to remote from local
'''
git push origin
if it fails means you need to publish the branch, you will get something like this
git push --set-upstream origin addcommandstomakefile  -> this is the name of the branch
'''

10. Help 
'''
git help
--help
'''


## CLI Commands

1. List the directory contents 
'''
ls 
'''

2. Make a new directory
'''
Mkdir NAMEOFDIRECTORY
'''

3. Navigate to directory
'''
cd DIRECTORYNAME
'''

4. Display current file path 
'''
pwd
'''

5. Deleting
'''
rm FILENAME  deletes a file
rm -r DIRECTORYNAME  deletes a directory
rm -f FILENAME  force deletes a file
'''

6. Update file access/create a file if it doesn't exist 
'''
touch FILENAME
'''

7. Moving/renaming
'''
mv OLDFILENAME NEWFILENAME
mv FILENMAE DIRECTORYNAME
'''

8. Copy 
'''
cp FILENMAE DIRECTORYNAME
'''