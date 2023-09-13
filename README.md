# Docker MongoDB Replica Set

Based on https://github.com/sntnupl/devcontainers-mongodb-replica-set-with-docker

### Generate `file.key`
```bash
openssl rand -base64 700 > file.key
chmod 400 file.key
sudo chown 999:999 file.key
```

## Build
```bash
docker-compose up
```

## Run
```bash
docker-compose start
```

```bash
docker-compose stop
```