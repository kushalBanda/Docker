## Docker Commands

``` bash 
docker build -t welcome-app .
``` 
* Command to build the docker file 

``` bash 
docker ps
``` 
* Will show you how many containers are running.

``` bash 
docker stop
``` 
* To stop the container 

``` bash 
docker image rm -f new-app
``` 
* To remove the docker image

``` bash 
docker tag old_name new_name
``` 
* To change the name of docker image

``` bash 
docker push new-app: latest
``` 
* To push the content to the docker 
* Latest will add the tag 

``` bash 
docker pull new-app:latest
``` 
* To pull the content from the docker 

``` bash 
docker run -d -p 5000:5000 new-app:latest
``` 
* To run the docker image 

``` bash 
docker ps
``` 
* To check the running docker container

``` bash 
docker stop ‘CONTAINER-ID’
``` 
* To stop the specific docker container

``` bash 
Docker login
``` 
* To login into Docker

``` bash 
Docker compose up
``` 
* Builds, (re)creates, starts, and attaches to containers for a service.
