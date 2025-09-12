# Personal VPS
This repo houses all the code, etc for my personal VPS. 

## Minecraft Server
I'm using the [Minecraft Docker Image](https://hub.docker.com/r/itzg/minecraft-server/) to host a few different Minecraft servers. A latest release version, a r1.6.4 and [better than adventure](https://www.betterthanadventure.net/) server. Docker allows me to spin these servers up and down quickly, make changes using docker compose files and allow for ci/cd. 

## Github Actions
### Minecraft Transfer
This transfers the docker compose files from this repo onto my VPS. 

