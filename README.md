# Docker-compose script to set up the local Gitlab instance (with blackjack and hookers)

The `docker-compose` file was generaged by [Llama2 Chatbot](https://www.llama2.ai/).

## Pre requirements

Both [Docker](https://docs.docker.com/get-docker/) and [Docker Compose](https://docs.docker.com/compose/) should be installed.

Use [Docke Toolbox](https://docs.bitnami.com/containers/how-to/install-docker-in-windows/) if you have Windows Home Edition.

## How to run the Gitlab instance

Use environmenr variable `GITLAB_ROOT_PASSWORD` to specify the password of the user `root`

After that, you can run the local Gitlab instance with the `docker-compose` command:

```
docker-compose up -d
```

After that, you can access Gitlab user interface on the [port `3000` of your localhost](http://127.0.0.1:3000).

## How to stop the Gitlab instance

To stop your local Gitlab instance, run the ollowing command:

```
docker-compose down
```
