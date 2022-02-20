# Introduction de l'application:

Nous avons créé une petite application amusante Python Flask qui affiche des .gifs aléatoire à chaque fois qu'elle est chargé.

## Ce que vous devez faire:

Ecrire le fichier Dockerfile pour faire tourner l'application.
Pour cela deux étapes importantes:

1. construire une images docker
2. Lancer un container basé sur l'image
3. Lancer un navigateur web pour voir le résultat de l'application (Il faut acutaliser la page plusieurs fois)

## Comment livre votre travail:

1. Sur Github dans un dépôt publique avec le code de l'application et le fichier Dockerfile
2. sur DockerHub dans un répo avec l'image docker.

NB: il est important de mettre à jour le fichier Readme.md et d'ajouter les commandes que je dois lancer pour faire fonctionner votre application.

docker build -t exam_img .
docker run -d --name exam_cnt -p 8080:5000 exam_img
tag exam_img khadija1997/examen8:v0
push khadija1997/examen8:v0 
git status