# ecom-shop
This website is ecommerce website where you can buy product and make payment online via paypal.
docker stop container --force 
docker build -t python-app /var/lib/jenkins/workspace/pipe/socialapp
docker run -d --name python-app-run -p 8008:8008 python-app


sudo usermod -G docker current user
sudo usermod -G docker jenkins
newgrp docker

sudo /etc/sudoers
jenkins ALL=(ALL) ALL

sudo passwd jenkins
su jenkins

################################
DOCKER COMPOSE
sudo apt docker-compose
vi docker-compose.yml
version: '3.0'

services:
  image-name:
    image: nginx
    ports:
      -9090/80
  databse:
    image: redis

docker-compose up -d (in detach mode)
docker-compose down (for downing the image)
docker-compose up -d scale database=4 (for creating multimle image of database)


