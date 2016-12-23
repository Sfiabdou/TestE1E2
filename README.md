@Author:Abdessamad SOUFI
@Date :23-12-2016
@Topic: Test NodeJS & FrontEnd - Bericolor

Ennancé de l'exercice 1:
---------------------

NodeJS: Pour ce premier exercice, il faudra faire un script js qui affichera sur la console
le dossier courant (équivalent à pwd en linux) puis créera un dossier "monDossier" à condition 
que celui-ci n'existe pas déjà: j'ai conscience que l'on peut faire ça assez facilement en bash 
mais je vous demanderai d'utiliser le module natif "fs" de nodeJS (pas de module externe donc). 

Réponse:
Veuillez voir le fichier 'nodejs.js' dans le dossier NodeJS.

Ennancé de l'exercice 2:
---------------------

FrontEnd: Pour ce second exercice, je vous demanderai de copier le html,
 le css et le javascript de la page http://www.vizircenter.ma/fr/contactpromo 
vous devrez le faire fonctionner en local avec une simple ouverture google chrome
 (le formulaire ne doit pas pouvoir être envoyé, mais on doit pouvoir cliquer sur
 le datepicker et choisir une date). Ensuite il faudra retravailler le design de 
quatre boutons que sont les éléments dont le "name" vaut date1, date2, adultes, 
enfants. L'idée est que le design soit uniforme.

la procédure suivée:
-------------------

1-Téléchargement de la totalité de la page (html,css,js):

>  wget -r -k http://www.vizircenter.ma/fr/contactpromo

2-Suppression  de l'attribut 'Action' du formulaire (il suffait de lui donner la valeur "#" ) pour ne pas être envoyé.

3-Modification de design des boutons: 
 +Pour que design soit uniforme , 
  pour les deux boutons 'adultes' et 'enfants' on  change l'attribut 'classe' des deux balises'select' de façon 
  qu'il soit : class="form-control col-lg-12 col-md-12".
  
NB: lien de la page: FrontEnd/www.vizircenter.ma/fr/contactpromo 
