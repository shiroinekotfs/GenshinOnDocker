# GenshinOnDocker

Running Genshin Impact server on Docker

## Start

1. Editing the `.env` file with these following params

```
MONGODB_ADMIN=mongodb
MONGODB_PASSWORD=<YourPassword>
```

2. Update the git submodules

```bash
git submodule update --init --recursive
```

3. Start the instance (firewall must be open for the services in `docker-compose.yml`)

```bash
docker compose up -d
```
