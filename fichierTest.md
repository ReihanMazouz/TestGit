#Présentation commandes Git :

git init =initialise
git status = observer l'état des fichiers dans le répertoire
git add fichier = ajoute le fichier dans Git
git log = observer les modifications dans le repertoire
git commit -am "explication modife"= ajouter une modife avec son explication

#Pour retourner sur une ancienne version :
1/ taper git log
2/ copier l'id après commit
3/taper dans le terminal git checkout id

#Pour revenir au code actuel:
git checkout master

#Attention : On ne peut pas supprimer une version

#Pour copier un code présent sur github :
1/ Aller sur l'url github où est présent le
2/ A droite des fichiers, sous SSH, cliquer sur HTTPS
3/Copier l'url
Sur la console
4/vérifier le répertoire
5/ git clone url
#Les fichiers voulu seront importer dans ce répertoire

#Pour créer son repository sur github :
1/ Aller sur son compte github
2/ Aller sur "create a new repository"
3/ compléter

#Pour envoyer mon code sur github
1/ Aller sur le repository où l'on veut envoyer le
2/ Copier l'url
3/ git remote add origin url
4/ git push -u origin master
