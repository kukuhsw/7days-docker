## 🚀&nbsp; List of Docker Command

### Docker Container Command

n this section you will find the most important commands related to the lifecycle of Docker containers.

Create a container (without starting it):
```shell
docker create [IMAGE]
```

Rename an existing container:
```shell
docker rename [CONTAINER_NAME] [NEW_CONTAINER_NAME]
```

Run a command in a new container:
```shell
docker run [IMAGE] [COMMAND]
```
- docker run --rm [IMAGE] – removes a container after it exits.
- docker run -td [IMAGE] – starts a container and keeps it running.
- docker run -it [IMAGE] – starts a container, allocates a pseudo-TTY connected to the container’s stdin, and creates an interactive bash shell in the container.
- docker run -it-rm [IMAGE] – creates, starts, and runs a command inside the container. Once it executes the command, the container is removed.

Delete a container (if it is not running):
```shell
docker rm [CONTAINER]
```

Update the configuration of one or more containers:
```shell
docker update [CONTAINER]
```