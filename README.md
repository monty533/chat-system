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
