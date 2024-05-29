<header>

<!--
  <<< Author notes: Course header >>>
  Include a 1280×640 image, course title in sentence case, and a concise description in emphasis.
  In your repository settings: enable template repository, add your 1280×640 social image, auto delete head branches.
  Add your open source license, GitHub uses MIT license.
-->
Most used commands
command	explain	shorthand
docker image ls	Lists all images	docker images
docker image rm <image>	Removes an image	docker rmi
docker image pull <image>	Pulls image from a docker registry	docker pull
docker container ls -a	Lists all containers	docker ps -a
docker container run <image>	Runs a container from an image	docker run
docker container rm <container>	Removes a container	docker rm
docker container stop <container>	Stops a container	docker stop
docker container exec <container>	Executes a command inside the container 	docker exec
# Exercice 1.1
EXERCISE 1.1: GETTING STARTED
Since we already did "Hello, World!" in the material let's do something else.

Start 3 containers from an image that does not automatically exit (such as nginx) in detached mode.

Stop two of the containers and leave one container running.

Submit the output for docker ps -a which shows 2 stopped containers and one running.
# Exercice 1.2
EXERCISE 1.2: CLEANUP
We have containers and an image that are no longer in use and are taking up space. Running docker ps -a and docker image ls will confirm this.

Clean the Docker daemon by removing all images and containers.

Submit the output for docker ps -a and docker image ls
