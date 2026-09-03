# Watchtower

Watchtower is a Docker container that automatically updates your running containers whenever a new image is available. It checks Docker Hub or your image registry periodically and applies updates safely. This ensures your services stay up to date without manual intervention. It’s configurable to ignore specific containers or trigger scripts after updates. A must-have tool for automating container maintenance.

## Setup

- [docker-compose-mail.yaml](./docker-compose-mail.yaml)
- [docker-compose-discord.yaml](./docker-compose-discord.yaml) webhook

### CRON timings

- hourly `0 0 * * *`
- weekly on sunday at 8AM `0 0 8 ? * SUN`

## Sources
- [GitHub Archive](https://github.com/containrrr/watchtower/)
- [GitHub Fork](https://github.com/nicholas-fedor/watchtower)
