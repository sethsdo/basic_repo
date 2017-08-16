Commands for project:
mkdir basic_repo
cd basic_repo
git init
touch index.html
touch style.css
touch readMe.txt
git status
git add .
git status
git commit -m "Change were made to index.html and to readMe.txt”
git remote add origin https://github.com/sethsdo/basic_repo.git
git push -u origin master
git status
git commit -m "There are some new changes to index.html and text.css"
git push