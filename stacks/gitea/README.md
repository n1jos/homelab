# Gitea

Gitea is a lightweight, self-hosted Git service similar to GitHub or GitLab. It offers repository hosting, issue tracking, code reviews and a web-based UI. Designed for simplicity and speed, it’s ideal for teams or individuals who want to manage their own Git servers. It’s easy to deploy and low on system resources. Gitea is perfect for developers wanting version control without cloud dependency.

## Setup

- [docker-compose.yaml](./docker-compose.yaml)

### Add Gitea runner

**generate config file:**
```shell
docker run --entrypoint="" --rm -it gitea/act_runner:latest act_runner generate-config > config.yaml
```

## Sources
- [Website](https://about.gitea.com)
- [GitHub](https://github.com/go-gitea/gitea)
