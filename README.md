# R5Reloaded Docker
This runs R5Reloaded from a docker container, this makes setting up servers a bit easier

## Setup

### Install

1. Clone this directory `git clone https://github.com/Radiicall/r5reloaded-docker.git`
2. Grab a server 7z file from the <a href="https://discord.gg/r5reloaded">R5Reloaded Discord Server</a>
3. Place server[.]7z in the cloned directory
4. Rename the server 7z to `server.7z`
5. Run `docker build -t r5reloaded-server -f Dockerfile` while still in the cloned directory

### Configuration

Inside the `docker-compose.yml` file you'll see the environment variables, these can be changed to configure the server

### Running

Run the docker compose file `docker compose -p r5reloaded up -d`
