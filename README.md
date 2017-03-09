# Git tips
##A list of useful commands

Create a new branch using a parent

    git checkout -b child_branch parent_branch
Undo add before commit

    git reset {filename}

Update commit message after push

    git commit --amend -m "New commit message"
    git push --force origin {branch}

Delete local branch

    git branch -d the_local_branch

Rename a local branch

    git branch -m {newname}

Restore local branch as remote

	git checkout mybranch
    git fetch origin 
    git reset --hard origin/mybranch

Delete remote branch

    git push origin --delete tu_branch

Cherry pick

    git cherry-pick {hash}

Revert merge (only in new versions of git)

    git merge --abort

