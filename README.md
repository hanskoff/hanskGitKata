# GITHUB

groovy HelloGitKata.groovy

# Standard way
1. Fork it (click on github repo)
2. Clone it (git clone git://github.com/balanced/balanced-dashboard.git)
3. Create your feature branch (git checkout -b my-new-feature)
4. Write your code and unit tests 
5. Ensure all tests pass :)
6. Verify your code to commit
7. Commit your changes (git commit -am 'Add some feature')
8. Push to the branch (git push origin my-new-feature:my-new-feature)
9. Create new pull request


# LEGIT way
1. Fork it (click on github repo)
2. Clone it (git clone git://github.com/balanced/balanced-dashboard.git)
3. Create your feature branch (git sprout master my-legit)
4. Write your code and unit tests 
5. Ensure all tests pass :)
6. Verify your code to commit
7. Commit your changes (git cola)
8. Push to the branch (git publish my-legit)
9. Create new pull request

[legit](http://www.git-legit.org)
sudo apt-get install git-cola

LEGIT

# Daily workflow with git

$ git sync
# Syncronizes current branch. Auto-merge/rebase, un/stash.

$ git switch <branch>
# Switches to branch. Stashes and restores unstaged changes.

$ git publish <branch>
# Publishes branch to remote server.

$ git unpublish <branch>
# Removes branch from remote server.

$ git branches
# Nice & pretty list of branches + publication status.

or https://github.com/kennethreitz/legit#the-interface

EXAMPLE
git branch -a               --> git branches
git checkout master         --> git switch master
PULL
git pull --rebase           --> git sync
PUSH
git push origin my-feature  --> git sync
DEL
git push origin :my-feature --> git unpublish my-feature

DEL localy
git branch -d my-feature

git harvest master
BONUS (aliases)
append ~/.gitconfig
[alias]
  lg = log --graph --pretty=format:'%Cred%h%Creset -%C(yellow)%d%Creset %s %Cgreen(%cr) %C(bold blue)<%an>%Creset' --abbrev-commit --date=relative







CONTRIBUTION
1. znajdujemy ciekawy projekt np. fabtools :)
2. fork https://github.com/hanskoff/fabtools
3. git clone
4. feature-branch? master? git cola? git sync?
5. github pull request na oryginalnym repo


