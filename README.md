# python_docker

# How to start an application using docker-compose
docker-compose -f docker-compose.dev.yml up --build

# Check if application is running - curl from another terminal tab

 curl http://localhost:5000/
 
 curl http://localhost:5000/initdb

 curl http://localhost:5000/widgets
 
 
