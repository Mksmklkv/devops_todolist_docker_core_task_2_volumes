# MySQL container run with a volume attached
docker run -d -p 3306:3306 --name mysql-local -v mysql-data:/var/lib/mysql mysql-local:1.0.0
# App run
 docker run --name app-local -p 8080:8080 app-local:1.0.0
 # Link for docker hub app image
 https://hub.docker.com/repository/docker/kulakovmaksym/todoapp/tags/2.0.0/sha256:2ca561737318aca43afbb632b29d2fc28684bd6c7249c5a702cf998c1ed3382e
 # Get app
http://0.0.0.0:8000/

