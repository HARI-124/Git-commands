### Useful git commands

1) `git commit -am "first commit"` this will add to the staging area and commits the code
2) To create alias in git use `git config --global alias.ac "commit -am"` in the ac is the alias for  commit -am so to use it `git ac 'noice'` will add and commit the code.
3) `git commit --amend -m "nice"` this command will update the recent commit with the desired commit name.
4) To add the new changes to the last commit itself use `git commit --amend --no-edit` followed by `git add .`.
5) To overwrite the remote commit use `git push origin branchname --force`.
6) `git revert "update" ` wil remove the last commit.
7) `git stash save coolstuff` to save changes without commiting but to use them again use `git stash list` to find it and use `git stash apply i` where `i` is the index of the change in the list.
8) `git commit --fixup commitId` and `git commit --squash commitId` will save all the commits into a single commit or we can use `git rebase -i autosquash`.
9) 