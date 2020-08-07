# PROJET_VOISINAGE

Pour demarrer l'api

- 1ère etape:
	Importer le la base de donnéé sur mysql ou utiliser les commande suivante au niveau de la ligne de commande du terminal de l'API:
	1)Projetvoisinage > php bin/console doctrine:database:create
	2)Projetvoisinage > php bin/console make :migration
	3)Projetvoisinage > php bin/console doctrine:migrations :migrate

- 2ème etape:
	Demarrer l'API avec cette commande: php -S 127.0.0.1:8000 -t public
	Ensuite on copie l'adresse https fournit et on le colle au niveaud de la barre d'adresse du navigateur

- 3ème etape:
	Effectuer les test a l'aide d'un outil de test d'API comme Postman en utilisants les routes fournies dans la documentation

