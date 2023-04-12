# Docker cheatsheet
General-purpose commands and guides <br />
Remember `sudo` !
<br />
<br />

### General purpose commands
General purpose command
<br />
List running containers.
<br />
`sudo docker ps`
<br />
`sudo docker start container-name`
<br />
`sudo docker stop container-name`
<br />

### Docker-Compose
A way to declare a configuration for your docker deployment.
<br />
Getting started...
<br />
Make directory for container
<br />
`mkdir container-name`
<br />
<br />
Inside the containers directory, make your Docker Compose-file. <br />
Use any text-editor, in this example it's `nvim`.
<br />
`nvim docker-compose.yml`
<br />
<br />
Start the container in the background with "-d"
<br />
`sudo docker-compose up -d`
<br />
<br />

### Examples for docker-compose
This example is for a Nginx-webserver. A custom index.html file can be provided in a "html"-folder in the same directory.
<br />
```docker
version: '3'

services:
  web:
    image: nginx:latest
    ports:
      - "80:80"
    volumes:
      - ./html:/usr/share/nginx/html
```
<br />
<br />
