# VEX-10743

## How to use GitHub

1. Download the project

git clone https://github.com/VinHao2010/VEX-10743.git
cd VEX-10743

2. Pull changes from the web

git checkout xyz (any branch name)
git pull origin main (unless you want to pull from a different branch)

3. After editing code

git add .
git commit -m 'your message here'

4. Push your new branch

git push -u origin new-feature (push the branch to github)

5. Combine to main (DO NOT DO UNTIL CODE IS REVIEWED AND TESTED)

git checkout main (switch to main branch)
git pull (make sure it's up to date)
git merge xyz (merge your branch)
git push (push updated main)


## Useful commands

We will be using branches for our code. Think of branches as a seperate version of the code, a 'experiment' where we can merge it with the real code if we are satisfied.

git branch (shows local branches on your laptop)
git branch -a (shows all branches)
git status (shows your current branch)
git switch xyz (switch branches)
git branch -d xyz (delete branch, local)
