## Docker Symfony

# Description

This project objectif is to dockerize a symfony project with mysql, phpmyyadmin and an apach server.

# Prerequirement

- Docker
- Symfony CLI
- Composer

# How to use

- Copy / clone the project
- In the docker-compose file, change what is between {} and delete the {}
- Open your Terminal to the project directory
- Run the command to create a symfony webapp project (the webapp name must be identical to what you add in the docker-compose file) :

        symfony new { webapp name }  --version="7.0.*" --webapp
- In the .env file in your webapp directory, comment line 29 then uncomment and change line 27 or 28 to link mysql database with the project

