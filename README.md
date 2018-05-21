# Hello Node
This is a very basic Hello World application with Node.
Esta es una aplicacion basica de hola mundo  + la configuracion de docker hub+ la configuracion de jenkins.

Incluye el dockerfile para construirlo en docker build y jenkins para el ejemplo de pipeline.

Develop all the process from Code to Version to Dockerized to Deploy (Source Code + Github + DockerHub + Jenkins).
Con esto vamos a hacer el ejemplo de un Devops Pipeline, para que no les digan, para que no les cuenten (Source Code + Github + DockerHub + Jenkins).

# Running locally 
    $ npm install
    $ npm start or $ node main.js
    $ yum install docker -y
    $ yum install nano -y

# Running locally in a Container
Agregar esta madre.

## Create locally and manually the Container
    $ sudo docker build -t ryukusanagi/devops .

## Run locally, When the Container is already created or in Docker Store!
    $ sudo docker run -p 49160:8080 -d ryukusanagi/devops

# Visit
    http://127.0.0.1:49160/
