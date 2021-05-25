# GoSchool Git tutorial

Git tutorial 

git add <filename> => adds <filename> to staging
    1) git add <filename> => adds individual file
    2) git add <filename1> <filename1> => adds 2 files
    3) git add . => adds all files in folder

git restore <file> ... => restores file/s => provided not added

git restore --staged <file> ... => removes file from staging, back to working stage


git commit -m "insert message" => commits with message

git branch => shows existing branches 

git branch <branch name> => creates new branch

git checkout <branch name> => moves head to branch => working repo is now in branch

git merge <branch name> => merges branch to main
    Steps:
    1) checkout to main
    2) git merge <branch name>

git status => shows the status of git


