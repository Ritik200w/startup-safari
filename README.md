docker network create my-network


docker run -d --network my-network   --name mysql   -e MYSQL_ROOT_PASSWORD=root    -e MYSQL_DATABASE=finalyear   -p 3306:3306   mysql:8


docker ps


docker run -d --network my-network -p 8080:8080 startup:latest


sudo usermod -aG docker $USER
newgrp docker 
