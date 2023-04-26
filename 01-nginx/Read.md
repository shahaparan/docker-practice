# Introducing Nginx

- [ ] Getting started with Docker and Nginx
  - [ ] Pull image from Docker
  - [ ] Run Nginx container
  - [ ] Docker stop container
  - [ ] Verifying your installation
    - [ ] Nginx -v
    - [ ] Docker top web
    - [ ] curl localhost
    - [ ] Browser localhost:8080
  - [ ] Basic Service management
    - [ ] service nginx start
    - [ ] service nginx stop
    - [ ] Nginx commands
      - [ ] -h
      - [ ] -v -V
      - [ ] -t -T
      - [ ] -s signal
  - [ ] Nginx default folder /usr/share/nginx/html
  - [ ] Docker-compose file - using volumes
  - [ ] Serving custom pages - index.html
  - [ ] Building a new Nginx image
    - [ ] DockerFile

## code

```bash
Docker pull & Run from Dockerhub
docker pull nginx
docker run -it --rm -d -p 8000:80 --name website nginx
Test URL: http://localhost:8000/


docker build -t webserver .
docker run -it --rm -d -p 8000:80 --name website webserver

docker top website
nginx -h
```
