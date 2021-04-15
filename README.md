# How to run simple java program in docker container
Run java program inside docker
Configure docker on your host machine.
Then follow the steps
 1. build the docker image using Dockerfile. use appropriate tag
 
    ```  docker build . -t hasans30/java:latest ```
 2. run the container
 
    ```  docker run  --rm hasans30/java:latest ```
    
## if you want to mount local folder inside the container use following option
``` docker run  -v /mnt/c/t/volume/:/mydisk --rm -it hasans30/java ```
