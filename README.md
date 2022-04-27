# Go Dockerized dev environment
A template to start developing go apps inside docker with hot-reload


## Quickstart


Just have docker installed and started, change the `GO_VERSION` on Dockerfile to the desired go version and change the `GO_PORT` occurencies if you want to expose a port(if you're developing an API for instance).

Then run
```
docker compose build
docker compose run --rm app go mod init github.com/YOUR-USER/REPOSITORY-NAME
docker compose run --rm app air init
```
And finally:
```
docker compose up
```
