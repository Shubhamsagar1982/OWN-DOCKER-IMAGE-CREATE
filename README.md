# OWN-DOCKER-IMAGE-CREATE

Hey guys just done with docker introduction and it has been a great experience till now !!
Today i have done just small but important lab on docker image creation thus created my own docker image !!
Steps:

1] install your own os such as rhel8 on virtual machine like oracle virtual box
2]install docker on rhel8 os 
3] download docker images of differnt os on your rhel8 os to create docker containers
command - docker pull os_name
for ex- docker pull centos:7 
4] Link - hub.docker.com
5] create your docker container
docker run -it --name shubham centos:7 
6]configure your docker container according to your requirements
7] install packages and programs you like
8] clone or copy the docker container you installed 
command- docker commit shubham your_image_name:tag 
for ex- docker commit shubham myownimage:v1
9] thats all you are done!!


