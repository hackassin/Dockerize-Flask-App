# Dockerize-Flask-App
How to package a flask app into a docker container

### Important Pointers
1. Dockerfile is an executable file that helps in creating our own custom docker images. We have the privilege to mention all the requirements 
in terms of packages, software etc. that need to be installed. 
2. From: A docker file starts with a from. It tells us about the requirement of a docker file.
3. Run: It is used to instal dependencies.
4. Copy: It copies files from local to the container.
5. CMD: It is a command which is run when an image starts. The difference between run and cmd is that unlike run, cmd does not create layers for the images.
6. Expose: It informs docker which port to use at runtime
7. Push: It is used to share your images in the Docker hub registry.

