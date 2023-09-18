# Docker MongoDB Replica Set

Based on https://github.com/sntnupl/devcontainers-mongodb-replica-set-with-docker

### Generate `file.key`
```bash
openssl rand -base64 700 > file.key
chmod 400 file.key

# Only in Windows
sudo chown 999:999 file.key
```

### Move the file.key into .docker/mongodb directory

### Edit hosts file
```
127.0.0.1 mongo1 mongo2 mongo3
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