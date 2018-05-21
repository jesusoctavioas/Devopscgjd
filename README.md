# Hello Node
This is a very basic Hello World application with Node.
Esta es una aplicacion basica de hola mundo  + la configuracion de docker hub+ la configuracion de jenkins.

Incluye el dockerfile para construirlo en docker build y jenkins para el ejemplo de pipeline.

Develop all the process from Code to Version to Dockerized to Deploy (Source Code + Github + Jenkins + DockerHub).
Con esto vamos a hacer el ejemplo de un Devops Pipeline, para que no les digan, para que no les cuenten (Source Code + Github + Jenkins + DockerHub).

# Running locally via curl or yum
    $ curl --silent --location https://rpm.nodesource.com/setup_8.x | sudo bash -
    $ sudo yum install nodejs -y
    $ sudo yum install gcc-c++ make
    $ rpm -iUvh http://dl.fedoraproject.org/pub/epel/6/x86_64/epel-release-6-8.noarch.rpm
    $ sudo yum install docker-io -y
    $ sudo yum install nano -y
    $ sudo yum install w3m -y
    $ sudo service docker start
    $ sudo chkconfig docker on

# Running locally in a Container
    $ docker pull ryukusanagi/devops

## Create locally and manually the Container
    $ sudo docker build -t ryukusanagi/devops .

## Run locally, When the Container is already created or in Docker Store!
    $ sudo docker run -p 49160:8080 -d ryukusanagi/devops

# Visit
    http://127.0.0.1:49160/
