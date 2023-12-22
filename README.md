Wishlist Application
Architecture du Projet
Conception de la Base de Données
La conception de la base de données a été réalisée à l'aide des diagrammes MCD/MLD/MPD. Les membres du groupe ont collaboré pour parvenir à un consensus sur l'architecture de la base de données.

Backend (Mehdi et Mohamed)
Le backend a été développé en utilisant Node.js et Express, avec la base de données créée grâce à Prisma. Les étapes comprenaient :

Mise en place de l'environnement de développement par Mohamed et Mehdi pour assurer l'utilisation cohérente des mêmes versions de logiciels.
Création de la base de données avec Prisma par Mehdi.
Création des endpoints de l'API dans le dossier des routes par Mohamed.
Mise en place des fonctions de création, récupération, mise à jour et suppression dans le dossier des controllers.
La documentation de l'Api a été réalisé avec Swagger qui permet de générer automatiquement des documentations d'API

Frontend (Fannick et Abdelaziz)
En collaboration avec l'équipe backend, le frontend a été développé en utilisant Next.js. Les étapes comprenaient :

Création de la page d'accueil affichant les listes existantes par Abdelaziz.
Création du dossier d'action par Abdelaziz pour la manipulation des listes, des cadeaux et des images.
Implémentation des boutons de création pour les listes, les cadeaux et les images.
Création des composants de page, tels que les swiper, les cartes pour les cadeaux, les listes et les images, par Fannick.
Intégration des requêtes à l'API pour rendre les boutons fonctionnels.
De plus, une fonction de tri pour les listes et les cadeaux a été ajoutée en réponse à un défi du professeur de gestion de projet.

En raison de problèmes avec des erreurs de code ajoutées sans raison apparente, un seul commit final a été réalisé. Veuillez noter que le fichier .gitignore est utilisé pour exclure les variables d'environnement du push sur Git.

Variables d'Environnement
Au cas où il y aurait des problèmes d'exécution du code, voici les variables d'environnement nécessaires :

SERVER_PORT=9000
DATABASE_URL='mysql://nztj8omfadg3xumro7tf:pscale_pw_9RBegKT53io45JSRyCucxvv2U8WSco8x05wjp9FQiIW@aws.connect.psdb.cloud/projet_architecture_web?sslaccept=strict'
NEXT_PUBLIC_API_URL=http://localhost:9000
