# Tp3_mundia_mvcthymeleaf

Ce projet est un exemple d'application Spring Boot avec Thymeleaf.  
Il permet de gérer des produits dans une base de données, avec affichage dans une interface web simple.

Les captures d'écran sont dans le dossier captures.

---

## Technologies utilisées

- Java 17  
- Spring Boot 3  
- Spring Data JPA  
- Thymeleaf  
- H2 / MySQL  
- Maven  

---

## Fonctionnalités

- Ajouter et afficher des produits  
- Sauvegarde automatique de quelques produits au démarrage  
- Interface web simple avec Thymeleaf  
- Gestion de la base de données via Spring Data JPA

La première image montre le fichier qui contient la méthode principale de lancement de l'application :  

![Capture du TP](captures/img.png)

La classe produits : 
![Capture du TP](captures/img_1.png)

L'interface qui gere l'acces a la table produits 
![Capture du TP](captures/img_2.png)

La configuration de securite 
![Capture du TP](captures/img_3.png)

Les username et mots de passe des differents utilisateurs 
![Capture du TP](captures/img_4.png)

La classe qui contient la methode principale de lancement de l'application contient aussi les donnees de base comme vu ici (computer...etc) 
![Capture du TP](captures/img_5.png)

Le fichier des proprietes qui contient toutes les dependances du projet 
![Capture du TP](captures/img_6.png)

On s'authentifie en accedant au lien localhost:8096 
User 1 et son mdp 
![Capture du TP](captures/img_7.png)

La base de donnees s'affiche devant nous avec les donnees entrees 
![Capture du TP](captures/img_8.png)

En s'authentifiant en tant qu'admin on a la meme interface mais on a aussi l'option d'ajouter des produits et de les supprimer 
![Capture du TP](captures/img_9.png)

Ici on teste en ajoutant un produit par exemple 
![Capture du TP](captures/img_10.png)

Le produit est ajoute a la base directement 
![Capture du TP](captures/img_12.png)


## Conclusion

Ce TP permet de se familiariser avec le développement d'une application web Spring Boot utilisant Thymeleaf.  
Il illustre la gestion des données via Spring Data JPA, l'affichage dynamique des produits sur une interface web simple et l'intégration d'une base de données H2/MySQL.  
Grâce à ce projet, on comprend le fonctionnement global d'une application Spring Boot avec Thymeleaf, de la couche back-end à l'affichage front-end.
















