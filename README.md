docker build -t docker-webserver .   
docker run -d -p 80:80 -p 4242:4242 docker-webserver
