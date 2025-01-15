# tp-bachelor

git clone https://github.com/cecilev-axe/tp-bachelor.git
git remote remove origin
git remote add origin https://github.com/Phelioume11/projetgit.git
git remote -v
git add Singe.jpg
git add .
git commit -m "Ajout d'une quatrième image et d'un dot supplémentaire"
git log
git push origin main





Mes commandes : 

nolhannguillaume@ip-172-31-20-29:~$ cd sites/GitHub/projet_git
nolhannguillaume@ip-172-31-20-29:~/sites/GitHub/projet_git$ git clone https://github.com/cecilev-axe/tp-bachelor.git
Cloning into 'tp-bachelor'...
remote: Enumerating objects: 10, done.
remote: Counting objects: 100% (10/10), done.
remote: Compressing objects: 100% (6/6), done.
remote: Total 10 (delta 0), reused 10 (delta 0), pack-reused 0 (from 0)
Receiving objects: 100% (10/10), done.
nolhannguillaume@ip-172-31-20-29:~/sites/GitHub/projet_git$ cd tp-bachelor
nolhannguillaume@ip-172-31-20-29:~/sites/GitHub/projet_git/tp-bachelor$ git remote -v
origin  https://github.com/cecilev-axe/tp-bachelor.git (fetch)
origin  https://github.com/cecilev-axe/tp-bachelor.git (push)
nolhannguillaume@ip-172-31-20-29:~/sites/GitHub/projet_git/tp-bachelor$ git remote remove origin
nolhannguillaume@ip-172-31-20-29:~/sites/GitHub/projet_git/tp-bachelor$ git remote add origin https://github.com/Phelioume11/githubproject.git
nolhannguillaume@ip-172-31-20-29:~/sites/GitHub/projet_git/tp-bachelor$ git remote -v
origin  https://github.com/Phelioume11/githubproject.git (fetch)
origin  https://github.com/Phelioume11/githubproject.git (push)
nolhannguillaume@ip-172-31-20-29:~/sites/GitHub/projet_git/tp-bachelor$ git add Singe.jpg
nolhannguillaume@ip-172-31-20-29:~/sites/GitHub/projet_git/tp-bachelor$ git add .
nolhannguillaume@ip-172-31-20-29:~/sites/GitHub/projet_git/tp-bachelor$ git commit -m "Ajout d'une quatrieme image et d'un dot supplmentaire"                                           
[main 61b369a] Ajout d'une quatrieme image et d'un dot supplmentaire
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 Singe.jpg
nolhannguillaume@ip-172-31-20-29:~/sites/GitHub/projet_git/tp-bachelor$ git push origin main
Username for 'https://github.com': Phelioume11
Password for 'https://Phelioume11@github.com': 
Enumerating objects: 13, done.
Counting objects: 100% (13/13), done.
Delta compression using up to 2 threads
Compressing objects: 100% (9/9), done.
Writing objects: 100% (13/13), 99.29 KiB | 2.68 MiB/s, done.
Total 13 (delta 1), reused 9 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (1/1), done.
To https://github.com/Phelioume11/githubproject.git
 * [new branch]      main -> main
