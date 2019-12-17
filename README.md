# dockerjavaprojects

how to run demo project:

- ./mvnw package  -->builds jar
- docker build -t greeting-app . --> build image from Dockerfile
- docker run -d -p 8090:8080 greeting-app -->run image in background and expose port 8080 in docker to port 8090 locally to access app's endpoint
