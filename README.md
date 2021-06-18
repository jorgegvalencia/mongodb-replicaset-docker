# Docker MongoDB Replica Set

Based on https://github.com/sntnupl/devcontainers-mongodb-replica-set-with-docker

### Generate `file.key`
```bash
openssl rand -base64 700 > file.key
chmod 400 file.key
```