# MySQL container run with a volume attached
docker run -d -p 3306:3306 --name mysql-local -v mysql-data:/var/lib/mysql --network app-net mysql-local:1.0.0
# App run
docker run -d -p 8080:8080 --name app-local --network app-net app-local:1.0.0
 # Link for docker hub app image
https://hub.docker.com/repository/docker/kulakovmaksym/todoapp/tags/2.0.0/sha256:a89f88da90de19bcaf0fa69d551ca67c5e05f328adffb34b53e6bf4de43a7f09
 # Get app
http://localhost:8080/

