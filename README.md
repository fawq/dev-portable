# Dev-portable

Dev portable is configuration for building and maintaining your own local projects

## Default config

In [.env](.env) file you can find default configuration for services like port used to connect gitlab, jenkins or nexus.

## Start of services

To start all services you need to have docker compose installed. Next use this command to bring up all:

```bash
docker compose up -d
```

You need to wait ~5-7 mins when all servcies will be available. If you want to kill all your services use:

```bash
docker compose down
```
