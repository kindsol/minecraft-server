# The Minecraft Server

This project runs a simple minecraft server within Docker containers

This server is based on what seems to be the very cool [docker-minecraft-server](https://github.com/itzg/docker-minecraft-server) project by [Itzg](https://github.com/itzg).

This installs a [Bukkit/Spigot server](https://getbukkit.org/) so we can install the following mods:

 * WorldEdit
 

## Installation

 * clone this project

## Usage

to start server:

    docker-compose up

to stop server:

    docker-compose down

## RCON

RCON is enabled by default, so you can exec into the container to access the Minecraft server console:

    docker exec -i mc rcon-cli

