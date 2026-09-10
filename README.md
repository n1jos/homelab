# homelab

This repository contains the configuration for my personal homelab.

It includes Docker Compose stacks, service-specific documentation, and the configuration files I use to deploy and manage the services running in my environment.

> [!WARNING]
> This repository contains my personal homelab setup and configurations, shared as-is.
> Use them at your own risk—what works in my environment may not work in yours.
> I am not responsible for any damage, data loss, downtime, or other issues caused by using this setup.

## Repository Structure

```text
homelab/
├── stacks/
│   ├── stack-name/
│   │   ├── README.md
│   │   └── docker-compose.yaml
│   └── ...
├── LICENSE
└── README.md
```

The `stacks/` directory contains the individual services and application stacks used in the homelab.

Each stack may contain:

- `README.md` — documentation, notes, setup instructions, and other stack-specific information
- `docker-compose.yaml` — Docker Compose configuration
- Additional configuration files required by the stack

## Notes

This repository primarily serves as:

- Documentation for my homelab
- Version control for my Docker Compose configurations
- A reference for rebuilding or migrating services
- A source of examples that others may adapt for their own environments

Configurations may change over time as the homelab evolves.

## Security

Sensitive information such as passwords, API keys, tokens, and other secrets should not be committed to the repository.

Any example environment variables or configuration values should be reviewed and replaced before use.

## License

This project is licensed under the [MIT License](./LICENSE).

You are free to use, modify, and distribute the contents of this repository in accordance with the terms of the license.
