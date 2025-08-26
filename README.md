# Dolphin

## Introduction

Le projet "Dolphin" a 2 objectifs :

1. Il donne à travers ce fichier "**.md**" un exemple de l'utilisation du langage **"Markdown"**
2. Il liste une série de commandes _GIT_ pour la mise en place d'un projet _versionné_

## Résumé des commandes principales

```
.ssh-keygen
copier-coller sha256 ... dans la key deploy zone
vérifier la connexion : ssh -T git@github.com
command git :
    git init
    git commit -a -m "first commit"
    git push origin main
```

## Liste des commandes

| Commandes  | Explications |
| ------------- |-------------|
|   git init   | initie le dossier en cours au versionning |
|   git log    | aperçu du versionning |
|   git status | statut du versionning |
|   git add test.php    |   maj du fichier dans le versionning  |
|   git add .   |   maj de tout le dossier dans le versionning  |
|   git commit -m "commentaire" |   maj du versionning si fichier modifié avec commentaire  |
|   git commit -a -m "commentaire"  |   Raccourci pour faire la maj du versionning de tous les fichiers du dossie   r
|   git checkout SHADuCommit    |   revenir à cette version |
|   git checkout master |   revenir à la branche principale |
|   git revert SHADuCommit  |   annulé cette versiont git   |
|   git revert --hard   |   tout annulé |
|   git clone https://github.com/GitHM/POO-PHP-tutorial |   cloner un projet sur sa machine |
|   git push origin master  |   mettre son projet sur github    |
|   git pull origin master  |   mettre à jour son projet local depuis github    |
|   git branch  |   affiche la branche courrante    |
|   git branch ma-branchee  |   ajout d'une nouvelle branche    |
|   git checkout ma-branche |   se placer dans une branche  |
|   git checkout -b ma-branche  |   raccourci des 2 commandes précédentes : on créé et on s'y place |
|   git branch -d ma-branche    |   supprime la branche |
|   git merge brancheB  |   met à jour la branche actuelle vers la branche détaillée    |
|   git blame nomdufichier.extension    |   voir le détails des modifications des fichiers - retourne un code par ligne |
|   git show coderetourné   |   détaille de la modification |
|   .gitignore  |   nom du fichier qui liste les chemins des fichiers qu'il ne faut pas publier |
|   git stash   |   arreter le travail en cours et passer sur d'autres branches|    |
|   git stash pop   |   reprendre le travail qui n'est pas terminé  |
|   git stash apply |   la commande stash pop delete stash. Pour la garder, ajouter apply   |
|   git push origin --delete [nom_de_la_branche]    |   supprime une branche sur Github |


### Quelques exemples avec Markdown

###### List Unordered
* Déjà pris
    * Dolphin ✓
    * Carassin ✓
    * Vulcain ✓
    * Marlin ✓
    * Pingouin ✓
    * Babouin ✓
    * Pelerin ✓
    * Tamarin ✓
    * Lérotin ✓
    * Lamantin ✓

* Pas Pris
    * Capucin
    * Viverrin
    * Arlequin
    * Grand murin
    * Lapin
    * Muscardin
    * Ragondin
    * Requin

## Images
![Dolphin](image/dolphin.jpg "Ceci est une image de Dauphin.")

## Lien du projet
Voilà le lien du projet : [ici](https://projetsmerlin.github.io/Dolphin/).

## Blockquotes
> Markdown is a lightweight markup language with plain-text-formatting syntax, created in 2004 by John Gruber with Aaron Swartz.
>
>> Markdown is often used to format readme files, for writing messages in online discussion forums, and to create rich text using a plain text editor.


Réalisé par `Merlin`.
