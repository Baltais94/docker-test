# docker-test
0. npm install --registry=https://registry.npmjs.org/
1. Install Docker (win or mac or lin);
2. If successful installation, running command 'docker' in CLI should print out all commands;
3.0 Run docker as admin, otherwise containers wont start
3. Dockerfile is an image create it
4. run command "docker build ."  it runs Dockerfile in that directory
5. then run command "docker run -p 3000:3000 eaa84a60c5c6", 3000:3000 opens up port in container and analog on localhost, -p means publish
6. 

Basic docker commands

To build image: `$ docker build .`

To run build image: `$ docker run -p 3000:3000 <container_id>`

To view running containers: `$ docker ps`

To stop docker container: `$ docker stop <container_name>` (may take some seconds to stop)

To start docker container: `$ docker start <container_name>`
