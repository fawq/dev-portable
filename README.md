# Dev-portable

Dev portable is configuration for building and maintaining your own local projects

## Prepare configs

First create 4 separete directories inside `/srv`

```bash
sudo mkdir /srv/gitlab
sudo mkdir /srv/gitlab-runner
sudo mkdir /srv/jenkins
sudo mkdir /srv/nexus
```

Next add permission to write

```bash
sudo chmod 0777 /srv/gitlab
sudo chmod 0777 /srv/gitlab-runner
sudo chmod 0777 /srv/jenkins
sudo chmod 0777 /srv/nexus
```

## Troubleshooting

If nexus has problem with permission just run:

```bash
sudo chown -R 200 /srv/nexus/
```
