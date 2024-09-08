## The docker is an container that has images and volumes
- it let's you deploy run applications very quickly 
- while adding tags and images 
- even if the information might be deleted you can quickly adapt 
- you can use both back and front end while the db as well 


### the yaml file guides the docker how to run the application.


## this docker app has also express js and node while we are fecthing data from mongodb


### if you want to persist data even after a container is deleted, you can use a volume.



### The volumes element that is nested in todo-database tells Compose to mount the volume named database to /data/db in the container for the todo-database service.

- The top-level volumes element defines and configures a volume named database that can be used by any of the services in the Compose file.
- When working with containers, you usually need to create a Dockerfile to define your image and a compose.yaml file to define how to run it.
-  to create all of these files we need docker init 
-  but always we don't want to overwrite so we say no 
-  docker compose up starts the project 