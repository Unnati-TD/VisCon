***Unnati Development and Training Center*** 


**Viscon**


|**Sr. No.**|**Description**|**Image**|
| :-: | :-: | :-: |
|1\.|Docker's architecture consists of several components that work together to create a platform for building, shipping, and running applications in containers.|<img src="Images/Docker-Architecture.png" width=200 >|
|2\.|A container is a sandboxed process running on a host machine that is isolated from all other processes running on that host machine.|<img src="Images/What-is-Container.png" width=200 >|
|3\.|To run a Docker container, you need to use the docker run command followed by the name of the Docker image you want to use. This command will create and start a new container based on the specified image.|<img src="Images/how-to-run-a-container.png" width=200 >|
|4\.|This slide shows key points diffrentiating virtual machine with container.|<img src="Images/Difference-between-Vm-Container.png" width=200 >|
|5\.|This images shows different types of container images.|<img src="Images/Types-Of-Images.png" width=200 >|
|6\.|The docker rename command is used to rename a Docker container. It allows you to change the name of an existing container to a new name, making it easier to identify or manage containers in your Docker environment.|<img src="Images/Docker-rename.png" width=200 >|
|7\.|The docker rmi command is used to remove Docker images from your local system. It allows you to delete one or more images that you no longer need, freeing up disk space.|<img src="Images/Docker-rmi.png" width=200 >|
|8\.|Deploying a MySQL database and a WordPress application in a multitier architecture using Docker|<img src="Images/MySQL-container.png" width=200 >|
|9\.|Deploying a postgres database and a gogs application in a multitier architecture using Docker|<img src="Images/postgres-gogs.png" width=200 >|
|10\.|A network bridge is a default networking mode that allows containers to communicate each other and with the host system over a private internal network.|<img src="Images/Network(Bridge).png" width=200 >|
|11\.|Port forwarding, also known as port mapping, is a networking technique used to redirect network traffic from one port on a host system to another port on another host or container.|<img src="Images/Docker-httpd.png" width=200 >|
|12\.|Post forwarding of hello-openshift container|<img src="Images/Docker-openshift.png" width=200 >|
|13\.|Port forwarding for supermario container|<img src="Images/supermario.png" width=200 >|
|14\.|Volumes are persist data beyond the lifecycle of container. It allow to manage and store data separately from the container itself which is particularly useful for maintaining data between container restarts, updates, and when containers are removed.|<img src="Images/Docker-host-volume.png" width=200 >|
|15\.|This image shows how docker network host works.|<img src="Images/Network(Host).png" width=200 >|
|16\.|A Dockerfile is a text file that contains a set of instructions for building a Docker image. Each instruction in the Dockerfile corresponds to a specific action that is executed when the image is being built.|<img src="Images/dockerfile.png" width=200 >|
|17\.|The ADD command in Dockerfile is used to copy files/directories into a Docker image while building the image.|<img src="Images/Dockerfile (add).png" width=200 >|
|18\.|The COPY command in Dockerfile copies files or directories from the build context (where the Dockerfile is located) to the image. It's used to include application code, configuration files, and other assets.|<img src="Images/Dockerfile (copy).png" width=200 >|
|19\.|The WORKDIR command sets the working directory for any subsequent instructions. Commands like RUN, CMD, and ENTRYPOINT will be executed in the set working directory.|<img src="Images/Dockerfile (Working-Directory).png" width=200 >|
|20\.|The CMD in Dockerfile specifies the default command to run when a container is started. It can be overridden by providing a command when running the container.|<img src="Images/Dockerfile-cmd.png" width=200 >|
|21\.|The ENV in Dokcerfile is used to set environment variables in the image. These variables can be used by processes running in the container.|<img src="Images/Docker-env.png" width=200 >|
|22\.|In a Dockerfile, the USER instruction is used to specify the user that will be used to run commands when the container starts.|<img src="Images/Dockerfileuser.png" width=200 >|
|23\.|Similar to CMD, but provides a fixed command that can't be overridden directly when running the container.|<img src="Images/Dockerfile-cmd.png" width=200 >|
|24\.|The HEALTHCHECK instruction in a Dockerfile is used to define a health check for a container. A health check is a command or a script that Docker periodically runs to determine whether a container is healthy or not.|<img src="Images/Dockerfile-Healthcheck.png" width=200 >|
|25\.|The MAINTAINER instruction in a Dockerfile used to be used to specify the name and email address of the person or organization responsible for maintaining the image.|<img src="Images/Dockerfile (Maintainer).png" width=200 >|
|26\.|The docker load command is used to load images that have been previously saved using the docker save command. This command is used to restore Docker images from a tarball archive file created with docker save.|<img src="Images/Load.png" width=200 >|
|27\.|Docker Compose is a tool for defining and running multi-container Docker applications. It allows you to use a single configuration file to describe the services, networks, and volumes required for your application, .|<img src="Images/Docker-compose.png" width=200 >|
|28\.|Docker Swarm is Docker's native container orchestration platform that enables you to create and manage a cluster of Docker nodes (machines) to deploy and scale containerized applications. |<img src="Images/docker-swarm.png" width=200 >|
|29\.|The docker stack command is used to deploy and manage services defined in a Docker Compose file as part of a Docker swarm mode cluster.|<img src="Images/Docker-Stack-Architecture.png" width=200 >|
