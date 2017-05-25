Exercice 
========

OC / Git & GitHub - Partie 2 Activité
-------------------------------------

Pour cet exercice qui a pour objectif de mettre en pratique les notions acquises dans les deux premières parties du cours sur Git et Github, Je vais utiliser à titre d'exemple un simple fichier html exporté depuis le site [si.gnatu.re](https://si.gnatu.re/) - d'ou le nom du repository - en le modifiant légèrment pour faire les commits demandés

- commit 1 = ajouté ma "photo"
- commit 2 = ajouté réseaux sociaux
- commit 3 = modification de la couleur du texte : #666666 au lieu de #0C344D
- commit 4 = ajouté l'énoncé de l'exercice dans le README

### Création du repository en local

	Last login: Wed May 24 15:23:45 on ttys001
	MacBookPro-2:~ franckgallio$ cd Documents/FORMATION/GIT
	MacBookPro-2:GIT franckgallio$ mkdir signature
	MacBookPro-2:GIT franckgallio$ cd signature
	MacBookPro-2:signature franckgallio$ touch README.md

### Initialisation du repository

	MacBookPro-2:signature franckgallio$ git init
	Initialized empty Git repository in /Users/franckgallio/Documents/FORMATION/GIT/signature/.git/

### Ajout des fichiers

	MacBookPro-2:signature franckgallio$ git add README.md
	MacBookPro-2:signature franckgallio$ git add signature.html