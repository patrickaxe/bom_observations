# BOM Observations Docker Container

This repository contains a Docker container for downloading Australian 
Bureau of Meteorology (BOM) weather observations.  

When running it will download Australian BOM weather observations and save them 
in the dedicated directory `/app/data/tgz/` inside the container.  
Edit the docker compose file (`docker-compose.yml`) with a data directory  
to mount a host directory to access the weather data.

## Usage

To use this container, follow these steps:
1. Clone the repository to your local machine.
2. Build the Docker image by running `docker build -t bom_observations .`.
3. Run the Docker container by executing `docker-compose up -d`.