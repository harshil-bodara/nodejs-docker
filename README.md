step: for docker stup in nodejs

first of all, login in local
---------------------------
docker login

Show the all conatiner
------------------------------
docker ps || docker container ls

Run the container
------------------------------
docker conatiner run -d -p [DOCKER_IMAGE_NAME].[TAG]

Stop the docker container
------------------------------
docker container stop [CONTAINER_ID]

Remove the docker container
----------------------------------------
docker container rm [CONTAINER_ID]
