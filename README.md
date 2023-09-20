# AKS-training

on a machine where docker is already installed an running 

clone this repository , it contains a dockerfile and index.html file 

on the same level of the location of the files run the following command to generate a docker image from the dockerfile :

#docker build -t <image_name>

and then run the following command to spawn a container from the previously created image :

#docker run -d -p 8080:80 <image_name>

you can check the created image on your host by running 

#docker images

and you can list the running containers with :

#docker ps
