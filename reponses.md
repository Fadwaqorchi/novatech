1. l’identifiant court du premier commit :  40f09b5
2. le commit correspondant à l’ajout de la page Contact : 878c401 added the contact page
3. le nombre actuel de commits : 8 
4. la commande utilisée pour afficher l’historique sous forme graphique : git log --graph

et la commande pour afficher tous les commit un par ligne et sous forme graphique afin de voir les branches et les fusions : git log --oneline --graph --all

5. La commande utilisée pour examiner précisément le commit correspondant à l’ajout de la page Contact : 
git log --oneline(pour trouver l id de la commande ou bien dans ce cas je l ai déjà)
git show 0f49cac


##Mission 8
Commande utilisée : git reset --mixed HEAD~1
Le commit n avait été partagé avec personne, donc on peut réécrire l'historique local avec reset.(et par défaut c est mixed)
Les modifications sont toujours présentes car reset --mixed déplace seulement la branche
vers le commit précédent : il annule le commit et vide le staging, mais ne touche pas
aux fichiers de travaill
La methode qui aurait aussi supprimé les modifications du fichier : git reset --hard HEAD~1