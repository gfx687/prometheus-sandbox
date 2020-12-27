# Prometheus with docker-compose

Configuration to run prometheus with docker-compose on machine's HOST network.
 If everything started without problems, Prometheus UI should be available at `localhost:9090/graph`

**NOT A PRODUCTION-READY CONFIG!**

Meant to be used for development purposes, for testing metrics of your services while coding

## Usage

MacOS:  `docker-compose -f %REPO_DIR%/docker-compose/docker-compose.mac.yml up`

Linux: yet to add

## Configuration

To add your service to prometheus scrape, update configuration file `docker-compose/docker-compose.mac.yml` (for mac)



