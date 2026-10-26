# Docker Nginx Lab

Esercitazione:
- Dockerfile basato su nginx:alpine
- Pagina HTML servita tramite Nginx
- Login con HTML, CSS e JavaScript
- Build e avvio del container Docker
- Immagine pubblicata su Docker Hub

##build
docker build -t docker-nginx-lab:v2 .

##avvio
docker run -d --name web-gateway -p 8082:80 --rm docker-nginx-lab:v2

##accesso
http://localhost:8082
