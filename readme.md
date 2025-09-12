# Minecraft VPS
This repo houses docker, IaC, etc for my minecraft server setup. The goal here is DevOps-ify minecraft servers, as I like to play different older version of minecraft, and minimize server setup time based on the "Two week Minecraft Phase" we're all familiar with.

## Minecraft Server
I'm using the [Minecraft Docker Image](https://hub.docker.com/r/itzg/minecraft-server/) to host a few different Minecraft servers. A latest release version, a r1.6.4 and [Better Than Adventure](https://www.betterthanadventure.net/) server. Docker allows me to spin these servers up and down quickly, make changes using docker compose files and allow for ci/cd. 

## Github Actions
### minecraft-compose-transfer.yml
This transfers the docker compose files from this repo onto my VPS. 




