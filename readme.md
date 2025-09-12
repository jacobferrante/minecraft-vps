# Personal VPS
This repo houses all the code, etc for my personal VPS. 

## Minecraft Server
I'm using the [minecraft docker image](https://hub.docker.com/r/itzg/minecraft-server/) to host a few different minecraft servers. A latest release version, a r1.6.4 and [better than adventure](https://www.betterthanadventure.net/) server. Docker allows me to spin these servers up and down quickly, make changes using docker compose files and allow for ci/cd. 

I'm using github actions to copy over the docker compose files.
