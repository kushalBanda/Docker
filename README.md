Docker Commands 

docker build -t welcome-app . 
* Command to build the docker file 

docker ps
* Will show you how many containers are running.

docker stop
* To stop the container 

docker image rm -f new-app
* To remove the docker image

docker tag old_name new_name
* To change the name of docker image

docker push new-app: latest
* To push the content to the docker 
* Latest will add the tag 

docker pull new-app:latest    
* To pull the content from the docker 

docker run -d -p 5000:5000 new-app:latest 
* To run the docker image 

docker ps
* To check the running docker container

docker stop ‘CONTAINER-ID’
* To stop the specific docker container

Docker login
* To login into Docker
 
Docker compose up
* Builds, (re)creates, starts, and attaches to containers for a service.
