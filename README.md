# Dev-portable

Dev portable is configuration for building and maintaining your own local projects

## Prepare configs

First create 4 separete directories inside `/srv`:

```bash
sudo mkdir /srv/gitlab
sudo mkdir /srv/gitlab-runner
```

Next add permission to write:

```bash
sudo chmod 0644 /srv/gitlab
sudo chmod 0644 /srv/gitlab-runner
```

## Default config

In [.env](.env) file you can find default configuration for services like port used to connect gitlab, jenkins or nexus.

## Start of services

To start all services you need to have docker compose installed. Next use this command to bring up all:

```bash
docker compose up -d
```

You need to wait ~5 mins when all servcies will be available. If you want to kill all your services use:

```bash
docker compose down
```
