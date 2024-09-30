#Demo 2

local repo

Git init initialize the git dir

New 
# Test

echo "# Test" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin git@github.com:yasir-762/Test.git
git push -u origin main

git restore README.md #to restore file before adding to stage to its unmodified state

git rm --cached README.md # To remove from staging

New Branch
