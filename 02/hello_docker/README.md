Sandboxing hello_world.java inside Docker container using Java 7 image
# Installation
1. Install Docker `wget -qO- https://get.docker.com/ | sh`
2. Download Docker image from my hub `sudo docker pull antonil/hello_docker`
   This will install all the dependencies needed for container to process.
3. Run the container. `docker run -it --rm --name java_hello antonil/hello_docker`
  
