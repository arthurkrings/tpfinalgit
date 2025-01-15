TP Git 
Partie : 
Baptiste -> HTML
1-	git clone https://github.com/arthurkrings/tpfinalgit.git 
2-	cd tpfinalgit
3-	git checkout -b brancheBaptiste
4-	touch  index.html
5-	nano index.html
a.	<H1> Bonjour </H1>
6-	git add index.html
7-	git config user.email baptiste.guellier@efrei.net
8-	git config  user.name baptisteguellier
9-	git commit -m "ajout du fichier index.html"
10-	git push origin brancheBaptiste

test
11-	git fetch origin brancheDishanth
12-	git pull origin brancheDishanth
13-	git branch -a 
14-	git checkout brancheDishanth
15-	git pull origin brancheDishanth

16-	git fetch origin arthur
17-	git pull origin arthur
18-	git branch -a 
19-	git checkout arthur
20-	git pull origin arthur 

21-	git checkout branchebaptiste
22-	git add index.html
23-	git commit -m “ajout du fichier index.html dans master “
24-	git push origin master

25-	git checkout master
26-	git pull origin brancheBaptiste
27-	 ls
28-	Git add index.html
29-	Git commit -m ajout du fichier index.html
30-	Git push origin master
31-	Git pull origin master
Ou 
32-	Git merge brancheBaptiste
