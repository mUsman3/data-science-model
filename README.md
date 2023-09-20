# Instruction
## Clone the project on local machine
## Install docker on local machine
## Create a user on hub.docker.com 
## Navigate to the project and open terminal in there
## Run "docker login" # enter your credentials
## Try building image on locally with following command 
   docker build -t docker-hub-username/ds-model-image . 
## onece image is build trying pushing to dockerhub with following command 
   docker push docker-hub-username/ds-model-image

## once image is available on hub.docker.com on your account
## create a app service and use your docker image:
  docker-hub-username/ds-model-image
