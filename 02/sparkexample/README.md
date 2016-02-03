https://blog.giantswarm.io/getting-started-with-java-development-on-docker/
#Installation
1. Install Docker `wget -qO- https://get.docker.com/ | sh`
2. Download Docker image from my hub `sudo docker pull antonil/sparkexample`
   This will install all the dependencies needed for container to process.
3. Run the container. `docker run -d -p 4567:4567 antonil/sparkexample`
4. Test server `curl localhost:4567`
