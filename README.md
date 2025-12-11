git init
git config --global user.name "Your Name"
git config --global user.email "Your email"
git remote add origin
git add .
git branch -M main
git push -u origin main
git log --oneline
git remote -v
git remote remove origin
git switch -c new-branch
git add .
git commit -m""
git switch main
git merge new-branch
git push -u origin main
git branch -d new-branch

# branch
git checkout -b new-branch
# make changes
git add .
git commit -m "new-branch-change"
git push -u origin new-branch

git checkout main
git pull origin main
git merge new-branch
git push origin main
git push origin --delete 2nd-branch


git show HEAD:index.html | sed -n '1,120p'

echo "Building student-portal"
ls -la
echo "Contents of index.html:"
sed -n '1,80p' index.html
