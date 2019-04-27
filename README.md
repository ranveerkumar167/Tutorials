# Tutorials
  git --version
  git init
  git remote add origin "https://github.com/ranveerkumar167/Tutorials.git"
  
  git pull origin master
  git status
  
  git add TestFile.txt
  
  git commit -m "adding first commit in local"
  
  git config --global user.email "ranveersharma4u@gmail.com"
  git config --global user.name "Ranveer"
  
  git add -A
  git commit -m "Multiple file commit"
  git commit -a -m "Multiple file commit"
  git log
  
  git branch firstBranch
  
  git checkout firstBranch
  
  git add -A
  
  git commit -m "making changes in firstbranch"
  
  git commit -a -m "my first commit to first branch"
  
  git checkout master
  ls
  clear
  git merge firstBranch
  ls
  git checkout firstBranch
  git push --set-upstream origin firstBranch
  git push --set-upstream origin master
  