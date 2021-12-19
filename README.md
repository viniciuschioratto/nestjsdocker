# NestJS with Docker
## Whats is this project?
This project is a example about how we can run a NestJS application using docker. Here is possible to see the necessary configurations to do it.
## Steps
### New NestJS project
To create a new NestJS project we can use the NestJS CLI using NPM. Firstly we should install the NestJS CLI and then run a command to create the project.
```sh
npm i -g @nestjs/cli
nest new nestjs-docker
```
### Docker configuration
We need to create the Dockerfile and docker-compose. Both are necessary to execute our service using docker.
The necessary configuration we can at the code.

### Running Docker
To run our application with docker, after do the necessary configuration we can execute the follow command to run it in dev or prod environment.
```sh
docker-compose up dev
docker-compose up prod
```