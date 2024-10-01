# Docker compose example

This repo contains the necessary files to run the example code from 8.2.10.2 Docker-compose.yml example

To run this docker compose example, clone the repository:

```sh
git clone https://github.com/CedricHermansBIT/docker_compose_example.git
cd docker_compose_example
```

Next run the analysis using:

```sh
docker compose up
# alternatively you can just run a single service
docker compose up fastqc
docker compose up minimap2
```

You should find the output files in the data directory.
