# Heimdall Docker

This is a simple Heimdall deployment using:

- [ ] Docker & docker-compose
- [ ] Traefik 
- [ ] Authentik SSO

## Deploy

To use this project make sure you have the correct routers and services lables and map an environment file of your choosing (or substitute the URL var). Also, this configuration makes uses the proxy auth method of Authentik for securing the portal and allowing SSO.

- [ ] Commands:

```bash
nano </heimdall-directory/.env> -> add environment variables
docker compose up -d
```