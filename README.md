
# Pour faire fonctionner l'application en local sur votre pc

## 2 étapes :

1) Créer un fichier __params.php__
2) y ajouter vos codes personnels de connection à la BDD.


ex à mettre entre deux balises php :

``
  $servername = "localhost";  
  ``  
  ``
  $dbname = "nom_de_ma_BDD";  
  ``  
  ``
  $dbuser = "nom_utilisateur";  
  ``  
  ``
  $dbpassword = "mon_mot_de_passe_secret";  
``  

 Si à votre tour vous voulez partager ce dossier, noublier pas d'ajouter votre fichier params.php à un fichier .gitignore.
