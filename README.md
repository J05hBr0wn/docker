# docker
<h1>List of useful docker commands</h1>

<h3>docker container --help</h3> # lists all available docker commands

<h3>docker --version</h3> # shows the current version of docker

<h3>docker info</h3> # displays system wide information about docker

<h3>docker login</h3> # logs in to docker (gives you access to your repositories)

<h3>docker image ls [-a]</h3> # shows the list of runnable docker images

<h3>docker container ls [-a]</h3> # shows the list of docker containers currently running

<h3>docker run [dockerfile]</h3> runs a built dockerfile
  
<h3>docker build -t [dockerfile]</h3> # builds dockerfile for current directory
  ex: docker build -t example
  
<h3>docker stop [container id]</h3> # stops a running container
  
<h3>docker kill [container id]</h3> # kills a running container (basically cmd + q)
  
<h3>docker rm [container id]</h3> #removes a docker container from the list of available containers
  
 
