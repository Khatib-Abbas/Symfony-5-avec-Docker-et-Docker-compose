#Symfony 5 avec Docker et Docker-compose
#video 
https://www.youtube.com/watch?v=tRI6KFNKfFo&list=PLxEJ5uJLOPDykEApcRHzprbFNWHHdYKAM
article
https://yoandev.co/un-environnement-de-developpement-symfony-5-avec-docker-et-docker-compose
https://insider.windows.com/en-us/for-business-getting-started#flight

Lancer docker avec ses composants:
docker-compose up -d


demander a docker d'installer une nouvelle version de symfony
docker exec www_docker_symfony composer create-project symfony/website-skeleton project
puis nous mettre en propio - linux
se mettre dans le /projet
ls -l pour si on est proprio son on l'est pas ouvrir l'interpréteur linux
$ sudo chown -R $USER ./

si erreur apache docker-compose build


entrer en ligne de commande version docker
docker exec -it www_docker_symfony bash
