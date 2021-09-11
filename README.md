# docker-learning
This repository contains docker learnings

## Docker Commands and Concepts

### List Container Images 

docker images

### Trying to find out the size of a specific container image. Say, we want all info for container ubuntu

docker images | awk '{ if($1 == "ubuntu") {print }}' 
