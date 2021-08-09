# ShaminKurreembokus_6_09082021
Projet 6 d'Openclassrooms contenant les parties frontend et backend

Pour faire fonctionner le projet, vous devez installer :

NodeJS en version 12.14 ou 14.0 
Angular CLI en version 7.0.2.
node-sass : attention à prendre la version correspondante à NodeJS. Pour Node 14.0 par exemple, installer node-sass en version 4.14+.
Sur Windows, ces installations nécessitent d'utiliser PowerShell en tant qu'administrateur.

Après avoir cloné le dépôt,

1) Lancer PowerShell
2) Aller dans le dossier frontend : > cd frontend
3) Entrer la ligne de commande
      npm install
      ng serve
(Veillez à avoir toujours un terminal qui exécute ng serve)

4) Ouvrer un terminal et aller dans le dossier backend:   > cd backend
5) Installer nodemon : npm install -g nodemon
6) Démarrer nodemon server
(Veillez à avoir toujours un terminal qui exécute nodemon)

Fonctionnalités à tester:

- Création d'un utilisateur :
        - l'utilisateur doit renseigner une adresse mail qui n'a pas été encore utilisée pour un autre compte
        - le mot de passe doit contenir :
                                          - Au moins 8 caractères
                                          - au moins une majuscule et un minuscule
                                          - au moins un chiffre
        - le mot de passe doit être chiffrer dans la base de données
                                          
 Une fois l'utilisateur créé, il pourra donc se connecter à l'application
 
 - Création de sauce: L'utilisateur peut ajouter une saucer via le formulaire en renseignant:
                  - Le nom de la sauce (name)
                  - le fabricant (manufacturer)
                  - une description
                  - ajouter une image
                  - les ingrédients (Main Pepper Ingredient)
                  - l'échelle de la force du piment
                  
  - Suppression et modification de sauce:
                  - L'utilisateur peut supprimer ou modifier uniquement les sauces qu'il a ajoutées
  
  - Likes et dislikes:
                  - L'utilisateur peut:
                                        - liker une sauce
                                        - enlever le like
                                        - disliker une sauce
                                        - enlever le dislike
