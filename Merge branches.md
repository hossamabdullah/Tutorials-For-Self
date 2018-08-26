how to merge your branch with master

First switch to master branch by checking it out
`git checkout master`

merge with your branch 
`git merge hotfix`

you can also rebase instead of merging
`git rebase hotfix`

then you can delete your branch safely
`git branch -d hotfix`


Merge vs Rebase
 - merge will whole merge code at once, without taking the commits made on the hotfix branch to master branch
 - rebase will merge code, but by adding them a commit by commit from the hotfix branch to master branch
 - The golden rule of git rebase is to never use it on public branches.
