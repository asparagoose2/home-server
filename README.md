# home-server

## Installation
Install `docker` and `docker-compose`

Optionally install `avahi-daemon` to publish the new host on the local domain

## Usage
Run: `sudo docker-compose up`

The containers should auto restart.

## Features
* Transmission web client
* homeassistant
* Plex server
* Samba server with 2 shares:
    * Config folder for other services
    * Media dir with movies and tv folders.
