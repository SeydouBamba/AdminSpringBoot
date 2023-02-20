# AdminSpringBoot
# Creation de la base de données
Nous avons utiliser Spring boot pour la création de notre base de données.
Nous avons choisis "maven" comme projet, "java" comme langage, et "2.7.8" comme version de spring boot. Nous avons également ajoutés les dépendances suivantes :
- Web
- JPA
- Actuator
- Mysql
- Lombok
- DevTools

![image](https://user-images.githubusercontent.com/124637366/219950700-f54a956c-1168-4d06-addd-34fb06fc799d.png)

Structure de la base de données admindb
![image](https://user-images.githubusercontent.com/124637366/220100803-75c823cb-5797-4703-a6fd-c071aa34801e.png)

Structure de la table approles de la base de données admindb aprés insertion de quelques données
![image](https://user-images.githubusercontent.com/124637366/220101771-63d7a347-a24d-49e9-a634-443be703bf92.png)

# Insertion des données dans la base de données, affichage du contenu de la base, connexion à la base à l'aide du id.
Ouvrer un navigateur et taper le lien suivant: http://localhost:8081/swagger-ui.html

Cela vous donne la possibiité d'effectuer trois opérations à savoir: 
- insertion de données dans la base
- affichage du contenu de la base
- connexion à la base à l'aide du id

En validant le lien vous avez la page suivante:

![image](https://user-images.githubusercontent.com/124637366/219951494-b990dbca-c1dc-491c-9b7e-9b7fddd47a41.png)

#  Insertion des données dans la base de données

Le resultat de l'insertion de l'utilisateur "DIARRA Abou" dans la base est:

![image](https://user-images.githubusercontent.com/124637366/219952182-69240921-734b-47de-bd71-80f3e6e64e3c.png)

# Affichage du contenu de la base

Le resultat de l'affihage du contenu de la base est:

![image](https://user-images.githubusercontent.com/124637366/219952546-16dd8a08-53f4-49a8-84d1-f9ab90b89c11.png)

# Connexion à la base à l'aide du id

le resultat de la connexion à la base avec l'id "2" est:

![image](https://user-images.githubusercontent.com/124637366/219952723-c7a21d57-fc96-40b4-88be-41f2b2d3e97d.png)

# Utilisation de l'application Postman

Il est aussi possible d'effectuer les opération d'insertion, d'affichage et de connexion avec Postman.
Pour ce fait, nous avons créer dans "Projet Ecole", une collection nommée "admin". Dans cette collection nous avons ajouter un folder appélé "user" dans lequel
nous avons ajouter des request  "all" pour l'affichage, "findById" et "login" pour la connexion.

Structure de admin dans postman

![image](https://user-images.githubusercontent.com/124637366/219877675-b8758fd8-0c8d-4ede-9137-60ab2227609d.png)

Le resultat de l'affichage de tous les utilisateurs de la base est :

![image](https://user-images.githubusercontent.com/124637366/219900109-32d3c1a5-8a33-41d6-84ba-239466c17219.png)

Le resultat de la connexion par id est : 

  #Pour id=1
  
![image](https://user-images.githubusercontent.com/124637366/219900159-a3f96948-44d4-435c-928b-550fd05dad18.png)

  #Pour id=3
  
 ![image](https://user-images.githubusercontent.com/124637366/219900206-264a6802-e14c-417a-80a2-028a94c42230.png)

Le lien est le suivant:
github.com/SeydouBamba/AdminSpringBoot
