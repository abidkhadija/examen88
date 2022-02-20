# clonné le projet 
git clon git@github.com:abidkhadija/examen88.git
# construction de l'image
docker build -t exam_img .
docker run -d --name exam_cnt -p 8080:5000 exam_img
# lancer le navigateur la commande suivante 
localhost:8080 
