# Wedding Invitation

A responsive, dependency-free wedding invitation served by Nginx for Alloy development sessions.

## Run with Alloy Compose

```sh
docker compose -f docker-compose.alloy.yaml up -d
```

The frontend listens on port `3000`. Alloy proxies it at `http://localhost:8080`.
