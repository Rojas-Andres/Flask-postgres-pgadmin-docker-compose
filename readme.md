Video youtube:
https://www.youtube.com/watch?v=I8HpI8E-ITc

Aws : 
 - amazon linux
 - t2.large
 - Aceptar todo el trafico 
 En la consola:
    - sudo yum update
    - sudo yum upgrade
    - sudo amazon-linux-extras install docker
    - Iniciar el docker engine
        - sudo service docker start
    - sudo yum install git 

    git clone https://github.com/Rojas-Andres/Flask-postgres-pgadmin-docker-compose.git 
    
    - sudo usermod -a -G docker ec2-user

Docker:
    - docker-compose build
    - docker-compose up
