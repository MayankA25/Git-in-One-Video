# init 

"git init" Initialise the git repository 


ls - shows all the files excluding hidden files
ls -lart show all the files including hidden files


# status

"git status" - shows the status of the files
"git status -s" - gives the summary of changes of all the files



first we have to stage the files then we have to commit 


# add
"git add file_name" ---> to add files one by one 
"git add ." ----> to add all files at once
"git add -A" ----> to add all files at once
add the files to the staging area


# commit
"git commit -m "some message"
to finalise the changes
"git commit -a -m "skipped staging aea" it skips the staging area for this we have to use add command at least once


# touch 

"touch file_name" it is used to create new file



# checkout
"git checkout file_name" it is used to roll back to the previous commit


"git checkout -f" it is used to roll back all te files to the previous commit 


# log

"git log" shows all the commits

"git log -p -(number_of_previous_commits)   shows the entered number of previous commmits


# diff
compares working tree with the staging area that means if i add those changes then diff will not show any changes

git diff --staged ----> compares the staging area with the last commit 



# rm(remove)

"git rm -f file_name" removes the file from working directory and staging area

"git rm --cached file_name" removes the file only from staging area but it will be present in wokring directory 

# ignore

.giiignore file cannot be created directly in the directory terminal should be used to create that file