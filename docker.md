# Docker Notes

## Commands

### docker image
- Lists all images

### docker ps
- Lists all active containers
- -a tag to list all containers

### docker container start [container_name]

### docker container stop [container_name]

### docker run -d -p [access port : mapped port] --name [container_name] [image_name]
- -d runs detached so in the background
- -p publishes ports to host

### docker build -f [Project/Dockerfile] -t test_experiment .
- -f sets dockerfile directory
- -t gives image a tag
- . represents current directory (directory in which command runs)
