# memogit
Vérifier sa version de GIT
$ git - - version

Définir son nom : 
$ git config - - global user.name « mon nom »

Définir mon adresse mail :
$ git config - - global user.email « mon email »

Repo = dépôt = collection de fichiers liées à un projet

Activer Git pour un répertoire
$ git init 

Créer un nouveau dossier
$ mkdir nomdudossier

Naviguer dans un dossier
$ cd nomdudossier

Lister les éléments dans un dossier
$ ls

Vérifiez l'état des modifications dans un dépôt
 $ git status

Afficher les modifications apportés aux fichiers
$ git diff

Ajouter les modifications d'un fichier à soumettre
$ git add <FILENAME>

Pour ajouter toutes les modifications d'un seul coup
$ git add .

Pour soumettre les modifications que vous avez ajoutées avec un court message décrivant les modifications
$ git commit -m "nom ducommit "

Pour revenir a une étape antérieur
git checkout numéro du commit 

revenir a la derniére version 
git pull origin master


revenir en arriére tous en supprimant les étapes intermédiaires 
git revert 

afficher les tag existant 
git tag

créer un tag
git tag '-a si on veut mettre un com' "nom tag" '-m'

push un tag 
git push origin "nom du tag"

push tous les tag
git push --tag

savoir ou je suis 
pwd 

upload sur github 
git push

download en local 
git pull

conflit :
il y a un conflit quand deux personne modifie la même ligne de code git ne sait pas lors quel version prendre il affiche donc une erreur 
du coup il faut retourner sur son code et la vscode affiche les deux versions dans des coloris différents il suffit de corriger le code manuellement 
puis de créer un nouveau commit "conflict merge par exemple " puis de la push une nouvelle fois pour ecraser le conflit précédent 