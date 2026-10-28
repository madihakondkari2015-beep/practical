git config --global user.email madihakondkari2015@gmail.com
 mkdir practical
cd practical
 git init
git remote add origin https://github.com/madihakondkari2015-beep/practical.git
git remote -v
echo "hello" > hello.txt
git add hello.txt
git commit -m "fisrt commit"
git branch -M main
git push -u origin main
git pull origin main
git branch feature
git branch
git switch feature
git branch
echo "New feature added" > feature.txt
git add feature.txt
git commit -m "Added new feature"
git switch main
git merge feature
git log --oneline
