git config --global user.name "Nigil2604"
git config --global user.email "24203037@srcas.ac.in"

cd E:/devpg1

git init

git add .
git commit -m "Initial commit"
git remote add origin https://github.com/Nigil2604/practical.git

git push -u origin master
git pull origin master

git add "file_name.txt"
git commit -m "commit message"

git checkout -b feature_branch

git add .
git commit -m "Feature updates"

git push origin feature_branch
