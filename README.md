# commandeGitNew

=====locallll
git reset --soft HEAD~1 == supprimer le commit sans supprimer les modifications
git reset --hard HEAD~1 == supprimer le commit et les modifications

git commit --amend -m "commit_01062025_update" == modifier un commit en ajoutant un fichier ou une modification sur un fichier du commit


============config git
installer git
configurer 
git config --global user.name "serge"
git config --global user.email "serge@email.com"



==========
Premier commit 
champs username + label username
champs password + label password
git 




Modification d'un commit plus ancien sans la perte de l'historique recent
identifier le commit a modifier
git log --oneline

git rebase -i 

git rebase -i iiiiii~1

Remplacez pick par edit devant l'ancien commit à modifier :
 
git add . 

git commit --amend

git rebase --continue


Traitement d'un conflit dans un fichier et dans un repos
=>
Un fichier modifié sur la meme ligne par Fabi et Amadou 
=>
Un fichier a été supprimé par fatou  et modifié par Amadou