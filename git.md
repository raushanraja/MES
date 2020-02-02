1.Initializing git in local repository

    git init



2.Adding files to git

    git add .



3.Adding initial commit message

    git commit -m "Initial Commit"



4.Adding remote url with the local repository

    git remote add origin master replpaceWithRemoteURL



5.Getting remote branch details

    git remote -v



6.Replacing local commits on top of the newly updated origin/master (or origin/yourBranch: git pull origin yourBranch).

    git pull --rebase origin master




7.Pushing local commits to remote

    git push origin master


# Merge

1.git checkout merge
2.git pull origin merge
3.git checkout raushan-material
4.git merge merge





# Empty Branch
git checkout --orphan <branchname>

This will create a new branch with no parents. Then, you can clear the working directory with:

git rm --cached -r .

and add the documentation files, commit them and push them up to github.

A pull or fetch will always update the local information about all the remote branches. If you only want to pull/fetch the information for a single remote branch, you need to specify it.


remove all the untracked files:
    ```git clean -fdx```
