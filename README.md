# Create-an-Image-from-a-Container-and-push-it-to-the-docker-hub.
Create an Image from a Container and push it to the docker hub.
- Launch an instance


- Connect to the instance


- The docker is installed and running.
- Pull the image using **sudo docker pull nginx**


- Run the container using **docker run -d nginx**


- To check the running containers use **sudo docker ps**
- To check the images available use **sudo docker images**


- To go inside the container we use **docker exec -it containerID bash**


- create an image of that container.
- to create an image from the container use **docker commit conatinerID**
- to see the images use **docker images**
- to give a name to the image use **docker tag d21 imagename:version**


- login to the docker hub and create a repository.


- login to the docker hub using the CLI.


- push the image to the docker hub.


- Refresh the docker hub, and you will find the image.


You have successfully pushed an image to the docker hub.
