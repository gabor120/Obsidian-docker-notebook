## Commands used:
- docker container run --publish 8080:80 nginx
	- Run nginx container from docker hub
	- Publish internal (from container) 80 port to external (to host) 8080 port
- docker container run --publish 8080:80 --detach --name webhost nginx
	- --name: name the container
- docker container logs webhost
	- show logs for the container named "webhost"
- docker container top webhost
	- List processes in container named "webhost"
- docker container ls -a
	- List (running) containers
	- List all containers, not just the running ones
- docker container stop/start/rm CONTAINER_ID
	- stop/start/remove container with CONTAINER_ID
- docker container rm -f CONTAINER_ID
	- remove container with CONTAINER_ID even if it is running
	
