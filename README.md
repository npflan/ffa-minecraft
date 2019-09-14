# ffa-minecraft
FFA Minecraft for NPF


## Quick Start
To get started in Docker by running this command.

```
docker run -d -it -e EULA=TRUE -e VERSION=1.14.4 -e MOTD="NPF Survival Server" -e MAX-PLAYERS=30 -e SPAWN-PROTECTION=0 -p 25565:25565 --name NPF01 itzg/minecraft-server
```