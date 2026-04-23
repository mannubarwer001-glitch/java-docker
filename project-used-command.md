# clone the project to local machine 
git clone < Repositorie link >
# make Docker image using Dockerfile 
docker build -t my-java-app .
# make and run docker container 
docker run -p 8080:80 -d <image-name> 
