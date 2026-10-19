# Docker Nginx Lab

Esercitazione:
- Dockerfile basato su nginx:alpine
- Pagina HTML servita tramite Nginx
- Build e avvio del container Docker

##build
docker build -t docker-nginx-lab:v1 .

##avvio
docker run -d --name web-gateway -p 8080:80 --rm docker-nginx-lab:v1

##accesso
http://localhost:8080
