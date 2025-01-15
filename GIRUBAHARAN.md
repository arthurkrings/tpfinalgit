#Travail fait sur le répo de Arthur : 

git clone https://github.com/arthurkrings/tpfinalgit.git
git branch brancheDishanth
git checkout brancheDishanth
git config user.email "dishanth2478@gmail.com" 
git config user.name "GDishanth"
touch mobile.css
nano mobile.css 
git status 
git add mobile.css
git status
git commit -m "Ajout du fichier mobile.css"
git push origin brancheDishanth 
git fetch origin brancheBaptiste
git fetch origin arthur
git branch -a 

Pour afficher toute les branches, je vais changer de branche à chaque fois : 
git checkout brancheBaptiste 
git checkout arthur 

nano mobile.css 

Depuis branche master : 
git config pull.rebase false 
git pull origin master 
git commit -m "Ajout du fihcier mobile.css"
git push origin master

git pull origin master (pour récupérer les moddification de Baptiste)
git merge brancheDishanth (pour fusionner ma branche à la branche master)

git pull origin master (depuis ma branche pour récupérer le contenue de master)
J'ai modifier (ajouter) du contenue dans l'index, je vais maintenant le push dans le master pour que mes camarades le récupère. 
git pull origin master (car arthur avait push quelque chose)

git add GIRUBAHARAN.md 
git add index.html 
git commit -m "ajout de mon fichier md et html modifier avec les pièces manquantes du moteur"
git push origin branchDishanth 










#(Bonus)
#Sur mon repo avant de changer sur celui de Arthur : 

Cd Documents 
mkdir RepoProjetFinale 
ls -a 
git --version 
git init 
git remote add origin https://github.com/GDishanth/RepoTpFinaleGit.git 
git config user.email "dishanth2478@gmail.com" 
git config user.name "GDishanth" 
touch mobile.css
nano mobile.css 
git status 
git add mobile.css
git status
git commit -m "Ajout du fichier mobile.css"
git branch brancheDishanth
git branch
git checkout brancheDishanth
git push origin brancheDishanth
git checkout master
touch test.md
nano test.md
git add test.md
git commit -m "Ajout du fihcier test.md"
git push origin master
