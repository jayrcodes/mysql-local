
A standalone mysql docker container.

Usually the mysql docker container is part of the main app's docker compose setup.

This setup is to have a separate mysql docker container that can persist data even if the main app's docker container is deleted.

### How to setup

```
cp .env.example .env
docker compose up -d
```
