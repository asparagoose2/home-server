# home-server

### setup + run 
```
sudo apt update && sudo apt install git docker docker-compose avahi-daemon && git clone https://github.com/asparagoose2/home-server.git && cd home-server && sudo docker-compose pull && sudo docker-compose up -d && echo "Done! containers will restart on reboot"
```

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
