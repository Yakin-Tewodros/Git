# Commands Run During first lesson on Git and Github

## Sanitized

mkdir LearningGit
git init
git config user.name "Yakin-Tewodros"
git config user.email "YakinTewodros@gmail.com"
git config --list
touch hello.md
git add .
git commit -m "initial commit"
touch hi.md
vim hi.md
vim hello.md
git commit -m "add more info"
mv hello.md git.md
git commit -m "rename hello.md to git.md"
nvim git.md
touch github.md
add git.md github.md
git add git.md github.md
git commit -m "add git.md and github.md"
nvim github.md
git branch -M main
touch README.md
vim README.md
git add README.md
git status
git commit -m "add README.md"
git log
cd LearningGit/

---

### some slight confusion happened here

#### [[commands_run#slight_confusion|Jump]]

---

#### back

git remote add origin https://github.com/Yakin-Tewodros/Git.git
git push -u origin main
git remote -v
git status
git rm hello.md
nvim git.md
git checkout -b version1
code .
git status
git add github.md
git status
git add git.md
git status
git commit -m "delete hello.md and changes"
git status
git push origin version1
git checkout main
git merge version1
git push -u origin main
bash

---

### slight_confusion

git remote remove origin https://github.com/Yakin-Tewodros/Git.git
git remote remove https://github.com/Yakin-Tewodros/Git.git
git remote remove Git
git remote get-url
git remote show
git remote remove origin
git remote add origin https://github.com/Yakin-Tewodros/Git
git remote rm origin
git config --global user.name "Yakin-Tewodros"
git config --global user.email "YakinTewodros@gmail.com"
git config -l --local
git config -l
git remote add origin https://github.com/Yakin-Tewodros/Git.git
git push -u origin main
git clone https://github.com/Yakin-Tewodros/first_repo.git
git clone https://github.com/Yakin-Tewodros/first_private_repo.git
cd LearningGit/
git config --unset user.name\ngit config --unset user.email
..
ll
cd first_repo/
git config --unset user.name\ngit config --unset user.email
..
git config -l
git clone https://github.com/Yakin-Tewodros/first_private_repo.git
cd first_repo/
git remote add origin https://github.com/Yakin-Tewodros/Git.git
git push -u origin main
git status
git remote rm origin
git remote -v
ll
..
ll

[[commands_run#back|Back]]
