# DeployFrontend
Go to github setting and pages and it will be deployed

$ git log --online
<!-- change unpushed wrong commits -->
$ git commit --amend --no-edit


<!-- basic statsh -->
 $ git stash
 git stash pop
<!-- basic statsh -->

<!-- advance stash  -->
git stash save consoledummycode
git stash list
git stash apply 0
<!-- advance stash  -->

git branch -m mucho

git log --graph  --oneline --decorate

<!-- to check bad commits -->
git bisect start
$ git bisect bad
 git bisect good last_commit_id
<!-- to check bad commits -->
 
 
 git rebase main --interactive
 use squash insted of pick to merge multipl commit then type escape and :wq

only if something wrong 
 git rebase --abort 

or do below way

git commit -- fixup fb2f677 
git commit -- squash fc2f55 
git rebase -i --autosquash


git hooks
npm i husky -D
to test 

s