git learning tutorial 

git init(create a local git repository)
git status(show repository current state)
git diff(show difference compare with last)
git reset --hard HEAD^(version rollback)
git log(show version historys. parameter:--pretty=oneline)
git reflog(show all version historys)
git remote add origin git@github.com:github-lqw/learngit.git(add remote repo)
git push -u origin master(push local to remote)
git clone git@github.com:github-lqw/gitskills(clone a remote repository)
git checkout -b dev(create a new branch 'dev' and switch it)
the last command to be equivalent to the fallowing two command:
  git branch dev(create a new branch 'dev')
  git checkout dev(switch to branch 'dev')
git branch(show all branches)
git merge dev(merge 'dev' to current branch)
git branch -d dev(delete the branch 'dev')
git log --graph --pretty=oneline --abbrev-commit(show branch merge situation)
git merge --no-ff -m "merge with no-ff" dev(merge with no-ff)
git stash(save working directory)