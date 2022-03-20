# Mattermost hosting playground

This repository contains a environment that allows to test [Mattermost](https://mattermost.com/) (OpenSource Slack
alternative) deployment.

Deployment is powered by Docker and `docker-compose.yml` file.

```sh
$ docker compose version
Docker Compose version 2.2.2
```

Let's start the services:

```sh
$ docker compose up -d mattermost --wait
```

Go to http://127.0.0.1:8065/

See also:

- [Mattermost Self-Hosted Changelog](https://docs.mattermost.com/install/self-managed-changelog.html)
