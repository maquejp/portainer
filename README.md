# Install Portainer

https://www.youtube.com/watch?v=iX0HbrfRyvc

https://docs.portainer.io/start/install-ce/server/docker/linux

    docker volume create portainer_data

    docker run -d -p 8000:8000 -p 9443:9443 --name portainer --restart=always -v /var/run/docker.sock:/var/run/docker.sock -v portainer_data:/data portainer/portainer-ce:latest

https://localhost:9443
