# springboot-encuesta-api

## Requirements

For building and running the application you need:

- [Docker](https://docs.docker.com/get-docker/)
- [Postman](https://www.postman.com/)

## Running and Installation the application

Steps & Commands

- [x] Open a command line
- [x] pull mongo image from docker hub **`docker pull mongo:latest`**
- [x] Open a command line in the project folder
- [x] dockerize spring boot application **`docker build -t springboot-survey:1.0 .`**
- [x] check docker image springboot-survey:1.0 is present **`docker images`** 
- [x] Open a command line in the project folder and run the command **`docker-compose up`**
- [x] To add a poll use the POST method in the Postman program as follows 'http://localhost:8080/encuestas' **`{
  "email": "jperez@gmail.com",
  "musicStyle": "pop"
  }`** 
- [x] You can use Postman to create a GET request using the route 'http://localhost:8080/encuestas' and execute it, this way you get the polls stored in the Database
