# git
git notes &amp; cheatsheet

```
git config --global user.name “[firstname lastname]”
git config --global user.email “[valid-email]”
git config --global color.ui auto

git config --global alias.co checkout
git config --global alias.br branch
git config --global alias.ci commit
git config --global alias.st status
git config --global alias.unstage 'reset HEAD --'

git init
git clone [url]

git status
git add [file]
git reset [file]    # unstage, keep changes
git diff
git diff --staged
git commit -m '[message]'

git checkout -b [new branch name]
git branch                # list branches
git branch [new branch name]
git checkout [branch]     # switch to another branch
git merge [branch]        # merge [branch] into current branch

git log
git log branchB..branchA  # show whats in A, not B
git log --follow [file]   # commits on a file, even renames
git diff branchB..branchA # diffs across branches
git show [sha]

git remote add [alias] [url]
git fetch [alias]
git merge [alias]/[branch]
git push [alias] [branch]
git push -u origin [branch]
git pull

git rm [file]
git mv [curfile] [newfile]
git log --stat -M          # log w/any paths that moved

git rebase [branch]
git reset --hard [commit]  # clear all staged/unstaged changes

git stash
git stash list
git stash pop
git stash drop
```
