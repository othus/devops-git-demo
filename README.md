# devops-git-demo
Devops git demo

## Common git commands
    git config 
       git config  --global user.name "<username>"
       git config  --global user.email "<useremail>" 
       git config --list
    git init

   git branch --list
   cd devops-git-demo/
   ls
   cat README.md
   vim README.md
   git add .
   git status
   git commit -m "first edite"
   cat README.md
   git push origin main -u
   git status
   git branch
   git pull
   git status
   git branch local-test-branch
   git branch --list
   git checkout test-branch
   git status
   git checkout local-test-branch
   git status
   git branch --list
   git checkout -b local-test-2
   git status
   git branch --list
   vim README.md
   git add .
   git commit -m "second commit"
   git push origin local-test-2
   git push
   git checkout local-test-branch
   git fetch origin local-test-2
   git status
   cat README.md
   git pull
   cat README.md
   git pull
   git branch --set-upstream-to=origin/local-test-2 local-test-branch
   git pull
   cat README.md
   git status
   git push
   git push origin local-test-branch
   git branch --list
