# Portainer

Portainer is a comprehensive management UI for Docker and Kubernetes containers. It provides dashboards for viewing container health, logs, volumes and networks. You can start, stop and configure containers without touching the CLI. It supports role-based access and stack deployment for teams. An essential tool for anyone managing a containerized environment.

## Setup

### Docker Run
```shell
docker run -d -p 8000:8000 -p 9443:9443 --name portainer --restart=always -v /var/run/docker.sock:/var/run/docker.sock -v portainer_data:/data portainer/portainer-ce:latest
```

### Update
1. `docker stop portainer`
2. `docker rm portainer`
3. `docker pull portainer/portainer-ce:latest`
4. `docker run`

## Sources
- [Website](https://www.portainer.io)
- [GitHub](https://github.com/portainer)
