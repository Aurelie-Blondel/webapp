
# Webapp

Creation of the image and deployment of the web application "webapp" with docker

### Require

1. docker installation

### User guide

1. clone the application
    `git clone https://github.com/diranetafen/static-website-example.git`

2. Create the Dockerfile in the same repository of application. 

3. Build the images: `docker build -t webapp:v1 .`

4. Test the images : 
    - `docker images`
    - `docker run --name webapp -d -p 80:80 webapp:v1`
5. open the browser on port 80
