
# DOCKER COMMANDS

COMMAND TO CREATE  NETWORK

```
docker create network <network-name>
```

Commmand to build the images


```
docker build -t <image name>:<tag-name> .
```

Command to run the container useing image in the network

```
docker run -d --name <container-name> --netork <network-name> <image-name>:<tag-name>
```

