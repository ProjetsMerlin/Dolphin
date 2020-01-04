# Radis
Résumé des commandes git bash
<br>
git init -> initie le dossier en cours au versionning<br>
git log -> aperçu du versionning<br>
git status -> statut du versionning<br>
<br>
git add test.php -> maj du fichier dans le versionning<br>
git add . -> maj de tout le dossier dans le versionning<br>
git commit -m "commentaire" -> maj du versionning si fichier modifié avec commentaire<br>
git commit -a -m "commentaire" -> Raccourci pour faire la maj du versionning de tous les fichiers du dossier
<br>
git checkout SHADuCommit -> revenir à cette version<br>
git checkout master -> revenir à la branche principale<br>
git revert SHADuCommit -> annulé cette versiont git<br>
git revert --hard -> tout annulé<br>
<br>
git clone https://github.com/GitHM/POO-PHP-tutorial -> cloner un projet sur sa machine<br>
git push origin master -> mettre son projet sur github<br>
git pull origin master -> mettre à jour son projet local depuis github<br>
<br>
git branch -> affiche la branche courrante<br>
git branch ma-branchee -> ajout d'une nouvelle branche<br>
git checkout ma-branche -> se placer dans une branche<br>
git checkout -b ma-branche -> raccourci des 2 commandes précédentes : on créé et on s'y place<br>
git branch -d ma-branche -> supprime la branche<br>
git merge brancheB -> met à jour la branche actuelle vers la branche détaillée<br>
<br>
git blame nomdufichier.extension -> voir le détails des modifications des fichiers - retourne un code par ligne<br>
git show coderetourné -> détaille de la modification<br>
<br>
.gitignore -> nom du fichier qui liste les chemins des fichiers qu'il ne faut pas publiés !!
<br>
git stash -> arreter le travail en cours et passer sur d'autres branches<br><br>
git stash pop -> reprendre le travail quin'est pas terminé<br>
git stash apply -> la commande stash pop delete stash. Pour la garder, ajouter apply<br>
git push origin --delete [nom_de_la_branche] -> supprime une branche sur Github<br>
<br>
principale :<br>
<br>
git commit -a -m "commentaires" -> met à jour tout le travail<br>
<br>
