# docker-nodejs-python
That is a quick example how to dockerize python and nodejs application. 

## Requirments 
* Docker
* Git


# How to start
### Clone the repository

    git clone 
    
#### Build Node application image
    cd node-app
    docker build -t node:latest .
    
#### Build Python application image
    cd python-app
    docker build -t python:latest .
    
 ##### Run
     docker run --name node-app -p 3000:3000 -d --rm node:latest
     docker run --name python-app -it --rm python:latest

