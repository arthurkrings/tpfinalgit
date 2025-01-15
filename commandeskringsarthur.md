
Commandes de KRINGS Arthur :
mkdir tpfinalgit
cd tpfinalgit
git init
git remote add origin https://github.com/arthurkrings/tpfinalgit.git
touch readme.md && touch .gitignore && touch license.md
nano readme.md
git add -A
git commit -m "Premier envoi"
git status
git config user.name arthurkrings
git config user.email arthur.krings@gmail.com
git push origin master
git branch
git checkout -b Arthur
touch style.css
nano style.css
git add style.css
git config user.email arthur.krings@gmail.com
git config user.name arthurkrings
git commit -m "envoi css premiere version"
git status
git push origin Arthur
git branch -a
git fetch origin brancheBaptiste
git checkout brancheBaptiste
git checkout Arthur
git fetch origin brancheDishanth
git checkout brancheDishanth
git checkout Arthur
git branch
nano style.css
mkdir css
ls
mv style.css css/style.css
git add css
git commit -m "CSS version 2"
git status
git push origin Arthur
git add css
git commit -m "envoi de la version 2 du css sur master"
git status
git push origin master
git checkout master
git branch
git pull origin Arthur
git config user.email arthur.krings@gmail.com
git config user.name arthurkrings


git add -A
git commit -m "envoi de la version finale sur master"
git reset css
git status
git fetch origin master
git pull origin master
git config pull.rebase false
git commit -m "envoi de la version finale sur le master"
git checkout Arthur
git merge Arthur
nano license.md
mkdir html
cd html
touch page2.html
nano page2.html
git checkout master
git add html
git commit -m "envoi de la deuxième page"
git checkout Arthur
mkdir images
git checkout master
git pull origin master
git add images
git commit -m "envoi des images"
git push origin master
