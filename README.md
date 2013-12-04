NuitInfo2013
============

Repository Nuit de l'info 2013 des "Sangliers d'Evry"


Utilisation de github :

Dans votre dossier de projet,

Pour récupérer/update les projets lancez les commandes suivantes :

  git init
  
  git remote add origin https://github.com/lesSangliersEvry/nom_repository.git (ici nom_repository = "NuitInfo2013")
  
  git pull -u origin master


Pour envoyer vos modifications les projets lancez les commandes suivantes :

  git remote add origin https://github.com/lesSangliersEvry/nom_repository.git (ici nom_repository = "NuitInfo2013")
  
  git push -u origin <branche>  


pour créer une nouvelle version (branche) :

  git checkout -b new_feature
  
  
  une fois sur la nouvelles branches toutes les autres actions concernerons la nouvelle branche.
  pour revenir à la branche master ou pour changer de branche :
  
  git checkout master (ou la branche souhaitée)
  
  
  pour fusionner deux branches :
  
  se positionner sur la branche receveuse par exemple master.
  
  git merge new_feature
  
  la branche "new_feature" sera ajouté à "master"

  
example pour sf2Project j'ai taper les commandes :

  git init
  
  git remote add origin https://github.com/lesSangliersEvry/sf2Project.git
  
  git pull -u origin master
  
  afin de récupérer le projet vide.
  
  
  Ensuite j'ai récupérer sur le site de Symfony le framework que j'ai ajouter dans mon dossier projet.
  Puis j'ai tapé les commandes suivantes pour merge avec la version master :
  
  
  ajouter les nouveaux dossiers fichiers :
  
  git add <fichier/dossier>
  
  
  envoyer :
  
  git remote add origin https://github.com/lesSangliersEvry/sf2Project.git
  
  git push -u origin master
  
  
  ajout de vendor dans la branche 1.0 :
  
  git checkout -b 1.0
  
  git add vendor
  
  git commit -m "Ajout vendor"
  
  git push origin 1.0
  
  
  puis merge sur master : 
  
  git checkout -b master
  
  git merge 1.0
  
  git push origin master

  
Pour le login et password demandez par email :
benjamin.petit91@gmail.com
  
